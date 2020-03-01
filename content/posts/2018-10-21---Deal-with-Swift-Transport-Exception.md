---
title: "Deal with Swift-Transport-Exception when sending Gmail from Laravel application"
date: "2018-10-21 13:50:53.169+0900"
template: "post"
draft: false
slug: "deal-with-Swift-Transport-Exception"
category: "Tech"
tags:
  - "Laravel"
  - "PHP"
  - "CentOS"
  - "Tech"
description: "When you use Gmail to send a mail from Laravel server without the permisson you will get this error. This my quick solution to deal with it."
socialImage: "/media/movable-type.jpg"
---

## Swift_TransportException Connection could not be established

The problem has occured when we send a mail from production server using Gmail. The notice of exception is shown below.

```
Swift_TransportException Connection could not be established with host smtp.gmail.com [Permission denied #13]
```

### Causes

This problem is caused by SELinux. So we will run some command for accepting httpd can open socket and send mail to outside destination.

### Solution

To allow for HTTPD (i.e. PHP) to make Network Socket connections

``` bash
setsebool -P httpd_can_network_connect on
```

To allow for HTTPD (i.e. PHP) to send out mail.

``` bash
setsebool -P httpd_can_sendmail on
```