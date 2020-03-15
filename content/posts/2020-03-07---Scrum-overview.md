---
title: Scrum Overview (Tổng quan về scrum)
date: "2020-03-07T09:15:56+0900"
template: "post"
draft: false
slug: "scrum-overview"
category: "Scrum"
tags:
  - "Scrum"
  - "Vietnamese"
description: "This post is a vietnamese post which gives an overview of scrum - management framework. It'll show you a general knowledge about scrum such as: What is scrum? what's it uses for? and how can we use it?"

socialImage: "/media/scrum-overview/scrum.png"
---

## Table of contents

1. [Scrum là gì](#scrum-là-gì)
2. [Scrum Roles - Vai trò trong Scrum](#scrum-roles---vai-trò-trong-scrum)
3. [Scrum Meetings - Những cuộc họp Scrum](#scrum-meetings---những-cuộc-họp-scrum)
4. [Scrum Artifacts - Những tạo tác trong Scrum ](#scrum-artifacts---những-tạo-tác-trong-scrum)
5. [Multiple teams - Nhiều nhóm phát triển](#multiple-teams---nhiều-nhóm-phát-triển)
6. [References](#references)

## Lời nói đầu

Bài đăng này được viết với mục đích lưu trữ kiến thức cá nhân và kinh nghiệm của mình sau 1 năm làm việc trong môi trường Agile. Trước đây mình có đọc và cũng biết nhiều về Scrum nhưng thực sự có những môi trường cố áp dụng Scrum (thậm chí là những cty mình từng làm) nhưng thực chất không phải là Scrum.

Và điều hiển nhiên là học Scrum thôi là chưa đủ, vì ở nhiều môi trường và hoàn cảnh khách nhau, Scrum được tổ chức và áp dụng khác nhau. Do đó, theo ý kiến cá nhân của mình, Q&A lúc nào cũng là phần cần thiết và quan trọng nhất trong quá trình học Scrum vì nó có thể đưa ra những pain-point cụ thể và giải pháp cho chúng. 

Hiện tại mình được phép thử mình ở vị trí Scrum Master của công ty, hay có thể gọi mình là Scrum Master student ở thời điểm này vì role Scrum Master khá là power trong framework mà bản thân mình hiện tại k đủ authority (thẩm quyền) để làm việc đó. Do đó mình cũng xin chia sẽ kiến thức về Scrum ở blog cá nhân trong khi học tập và áp dụng để mọi nguời cùng tham khảo và góp ý.

## Scrum là gì 

Mình đã nghe khá nhiều về Scrum cũng như Agile, và vài năm trước đây khi chúng được nhắc đến bản thân mình luôn nghĩ đó là mô hình quản lý task bao gồm 4 giai đoạn: backlog, todo, doing, and done, mà không biết đó chỉ là một phần nhỏ trong framework. 

Không dừng lại ở đó, mọi người có thể biết về những tạo tác và những định nghĩa trong Scrum chẳng hạn như: __Sprint__, __Cross-functional__ (đa chức năng), hay __Self-organizarion__ (tự quản lý) nhưng đa phần sẽ không hiểu về ý nghĩa đằng sau của chúng hoặc vì sao phải có chúng. 

Vậy thực sự bản thân Scrum là gì?

### 1. Scrum là một management framework 

* Đây là một mô hình quản lý dành cho việc phát triển những incremental product hay còn gọi là những sản phẩm được phát triển qua từng giai đoạn. Những sản phẩm này luôn có sự thay đổi __thường xuyên__ về yêu cầu chức năng từ phía khách hàng và Scrum có những phương thức vận hành có thể đáp ứng cho việc thay đổi đó. Việc này khác hoàn toàn mô hình truyền thống _Waterfall_
* Scrum thường dùng 1 hay nhiều development team (nhóm phát triển) khác nhau tuỳ theo kích thước của công ty. Những nhóm này thường chỉ gồm 7 người ở mức lí tưởng. Việc áp dụng 1 hay nhiều team sẽ gặp hoàn toàn những vấn đề khác nhau. Mình sẽ đề cập và giải thích điều này trong 1 bài viết khác.
* Scrum đưa ra cấu trúc về: __roles__ (vai trò cá nhân trong team), __meetings__ (các buổi họp Scrum), __rules__ (quy tắc), và __artifacts__(một số tạo tác). Các development teams phải có trách nhiệm trong việc tạo dựng và điều chỉnh mọi quy trình của team theo sát framework này.
* Quan trọng hơn cả, Scrum sử dụng vòng lặp với thời gian cố định trong việc phát triển, và vòng lặp này được gọi là __Sprint__. Độ dài thời gian của một Sprint thường __không vượt quá 30 ngày__ và càng ngắn càng tốt. Đầu ra ở một Sprint là một sản phẩm dùng được (potential releasable product) và được test kỹ càng để có thể lấy feedback (phản hồi) từ users. Đó là lí do tại sao Sprint càng ngắn càng tốt. Với một Sprint ngắn chúng ta có thể nhận được feedback từ người dùng và điều chỉnh sản phẩm một cách sớm nhất. 

### 2. Scrum là giải pháp thay thế cho mô hình Waterfall

* Mô hình Waterfall truyền thống (Hình 1) là mô hình quy trình (process) đầu tiên được giới thiệu và sử dụng rộng rải bởi vì nó đơn giản và dể sử dụng. 
* Waterfall yêu cầu phải có __sự hiểu biết hoàn hảo__ về các yêu cầu của sản phẩm từ ngay ban đầu __vì sau khi hoàn thành một giai đoạn nào đó sẽ rất khó quay lại__ nếu có rủi ro, hoặc cần bổ sung những thứ mà bạn không nghĩ ra ở giai đoạn thiết kế hay phân tích. 
* Do vậy với mô hình này chúng ta buộc phải đảm bảo được độ lỗi tối thiểu khi thực hiện từng giai đoạn.

![fig1.png](/media/scrum-overview/fig1.png)

*Hình 1: Mô hình Waterfall.*

* Khác với Waterfall, thay vì phát triển toàn bộ sản phẩm, Scrum chia nhỏ sản phẩm ra nhiều phần (items) hay chức năng (features) và phát triển các phần và chức năng đó thông qua vòng lặp Sprint. 
* Mỗi Sprint sẽ bao gồm __toàn bộ các hoạt động phát triển__ (Hình 2). Điều này giúp cho sản phẩm thích ứng với điều kiện thực tế thông qua các phản hồi ở cuối mỗi Sprint.
* Lợi ích lớn nhất của Scrum là khi áp dụng mô hình này cho những công việc phức tạp liên quan đến việc sáng tạo hay hợp tác chẳng hạn như tạo ra một sản phẩm hoàn toàn mới.
* Scrum thường được kết hợp với việc phát triển phần mềm hướng đối tượng. 

![fig2.png](/media/scrum-overview/fig2.png)

*Hình 2: Các giai đoạn trong một vòng lặp (1 sprint) của Scrum .*

* Các bước trong vòng lặp được mô tả sơ bên dưới:
	* _Evaluation/Prioritization_ 
		* Ở giai đoạn này thường product owner sẽ đánh gía và sắp xếp độ ưu tiên cho từng phần hay chức năng của sản phầm.
		* Vì khả năng nghiệp vụ và hoàn cảnh có thể thay đổi vì vậy giai đoạn này được lặp ở mỗi Sprint để bám sát vào sự thay đổi thực tế. 
		* Những phần (item) quan trọng nên được hoàn thành trước hết , thậm chí khi nó không quá hoàn hảo
	* _Detailed Requirement_
		* Ở giai đoạn làm rõ yêu cầu, chúng ta thường đặt câu hỏi và làm rõ từng chi tiết gíup cho việc hoàn thành yêu cầu thuận lợi hơn. 
		* Ngoài ra việc đặt câu hỏi cũng giúp chúng ta nắm bắt được scope của yêu cầu đễ tránh viêc chưa đạt những gì cần làm hoặc làm vượt quá những gì cần làm.
		* Công việc chỉ được uỷ thác khi và chỉ khi mọi người có một cái nhìn rõ ràng về những gì phải làm.
	* _Design and Analysis_
		* Chi tiết kỹ thuật phải được làm rõ khi một item được yêu cầu thực hiện 
	* _Implementation/Developer testing_
		* Implementation chỉ có thể bắt đầu sau khi có kế hoạch phát triển rõ ràng cụ thể.
		* Kiểm thử (tests) và tái cấu trúc (refactoring) là phải có để sản phẩm tốt hơn
	* QA/Acceptance testing
		* Các item đã thực hiện phải được kiểm tra và đánh giá bởi các bên liên quan (Product owner hoặc các PM khác như sale, marketing)

### 3. Scrum có một số điều cần chú ý như sau (Manifesto)

* Individuals and interaction over processes and tools
	* Các thành viên trong nhóm nên tương tác trực tiếp
	* Điều này rất quan trọng trong việc cập nhật luồng làm việc dễ dàng giữa các thành viên với nhau
* Working software over comprehensive documentation
	* Code cần phải hoạt động, được test và được refactored
	* Những điều đề ra trong document trước khi thực hiện nên được giữ ở mức tối thiểu có thể.
* PMs collaboration over contract negotiation
	* PMs cần phải là 1 phần của vòng lặp để giữ cho quy trình được linh hoạt và nhanh chóng.
	* Đôi khi ý tưởng ban đầu không hoạt động nên cần phải suy nghĩ lại.
* Responding to change over following a plan
	* Business priortities có thể thay đổi theo thời gian điều này dẫn đến sản phẩm cũng phải thay đổi để thích nghi.
	* Một số hạn chế khác chẳng hạn như hạn chế về thời gian phát triển cũng sẽ gây ảnh hưởng


## Scrum Roles - Vai trò trong Scrum

Trong Scrum chúng ta có 3 vai trò chính: Product Owner, Development team , và Scrum Master

### 1. Product Owner

* Product owner là:
	* Chủ kinh doanh sản phẩm (entrepreneur)
	* Người lãnh đạo 
	* Người quyết định cuối cùng của các câu hỏi yêu cầu (requirement questions)
* Product owner có trách nhiệm:
	* Xem xét quyền lợi của các bên liên quan (stackholder)
	* Tối ưu hoá "return on investment" (ROI) của sự đầu tư công sức vào việc phát triển.
	* Tầm nhìn của sản phầm (product vision)
* Product owner có quyền:
	* Cài và và điều chỉnh độ ưu tiên của Product backlog
		* Điều chỉnh những yêu cầu sản phẩm
		* Điều chỉnh kế hoạch phát triển như release plans
		* Việc điều chỉnh sẽ dựa trên:
			* Tình hình phát triển của những sprint gần nhất
			* Tình hình doanh nghiệp cũng như thị trường
	* Chấp nhận hoặc từ chối sự tăng trưởng sản phẩm (product increment) - có thể hiểu nôm na nó là kết quả của sprint.
	* Quyết định khi nào chuyển giao sản phẩm
* Lưu ý: Dù có 1 hay nhiều team thì chỉ nên có duy nhất 1 product owner. Người này là người có đủ quyền đưa ra những quyết định có ảnh hưởng đến doanh nghiệp. (Mình sẽ giải thích kĩ hơn ở bài viết khác)

### 2. Scrum Master

* Scrum master là:
	* Người có quyền quản lý Scrum nhưng không có quyền quản lý người khác 
		* Ví dụ: SM có thể đề nghị thêm cuộc họp để việc phát triển tốt hơn hay đề xuất qui trình để hoàn thành task dễ hơn NHƯNG không có quyền chỉ định người nào làm task nào 
	* Nên là người không có quyền lực ảnh hưởng trực tiếp đến các thành viên khác để tránh "invisible gun effect" 
		* "invisible gun effect" xảy ra khi bạn là sếp của mọi người nên khi bạn đưa ra ý kiến mọi người sẽ có tâm lí chịu chấp nhận với ý kiến đó dù muốn hay không. Ở đây chúng ta cần sự đóng góp từ các thành viên khác để team làm việc tốt hơn chứ không cần sự áp đặt.
* Scrum master chịu trách nhiệm:
	* Làm cho Scrum được hiểu và áp dụng cặn kẽ
	* Tạo môi trường thuận lợi cho team có thể self-organization
	* Bảo vệ team khỏi sự can thiệp bên ngoài để sprint có thể hoàn thành tốt nhất
		* Đôi khi bạn có những yêu cầu bất ngờ từ PO hay team khác. SM lúc phải cân nhắc tiến trình của sprint (chậm hay nhanh) để quyết định có chấp nhận yêu cầu hay không. SM phải chắc team không bị gánh nặng và làm sprint fail trong trường hợp này
	* Đề xuất cải thiện việc thực hiện kĩ thuật (engineering practices) chẳng hạn đề xuất qui trình hoàn thành một task như thế nào hiệu quả và đảm bảo chất lượng.
	* Xem xét và giải quyết trở ngại mà nhóm gặp phải

### 3. Development team 

* Một team tốt nhất nên chỉ có 6 ± 3 thành viên
* Có sự hợp tác mạnh mẽ giữa các thành viên trong team và giữa team với các team khác.
* Tự tổ chức (Self-organizing):
	* Team chịu trách nhiệm quyết định làm thế nào để phân công nhiệm vụ giữa thành viên để hoàn thành tất cả ở cuối mỗi sprint
* Tự quản (Self-managing)
	* Team chịu trách nhiệm về các quyết định cần có
* Đa chức năng (Cross-functional)
	* Trong một nhóm không yêu cầu 1 thành viên phải biết tất cả mọi mặt (vd front end, back end, test, v..v) nhưng tất cả các thành viên phải đáp ứng được tất cả mọi mặt. 
	* Vì vậy mỗi thành viên cần phải biết nhiều mặt để tạo sự linh động trong team (vd anh A chuyên làm front end nghỉ bệnh, and B có thể thay thế anh A nhận task đấy mặc dù anh B thường làm Test)
* Thảo luận về những gì sẽ hoàn thành trong sprint cùng với PO tại Sprint planning meeting ở mỗi đấu sprint
* Có quyền tự chủ lên kế hoạch làm sao để đạt được kết quả tốt mỗi sprint 

## Scrum Meetings - Những cuộc họp Scrum

## Scrum Artifacts - Những tạo tác trong Scrum 

## Multiple teams - Nhiều nhóm phát triển

## References

