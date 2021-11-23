# OOP-2021
Môn học Lập trình hướng đối tượng với Java



Thành viên trong nhóm:
+ Bùi Minh Sơn 20021427
+ Nông Ngọc Sơn 20021430
+ Nguyễn Đức Dũng 20020181

Repo đã tìm được và phân tích: https://github.com/OmarElgabry/DesignPatterns/tree/master/src?fbclid=IwAR3zcvkF1NME6gIojqlXHsJEQnlaZ-fpN46HoGKMaSQouK-o_uOHSZNU6eU


Điểm giống nhau:

Có kết cấu tương tự với mẫu chuẩn.

Hệ thống làm việc độc lập với cách sản phẩm của nó được tạo ra, cấu tạo và đại diện.

Mỗi lớp chỉ chịu trách nhiệm về 1 một việc.

Khi chỉnh sửa thêm bớt thành phần thì không cần thay đổi code hiện tại.

Code sạch sẽ

Điểm khác nhau:

Không nhiều do là 1 mẫu thiết kế tương tự mẫu thiết kế chuẩn.

•	Singleton:
o	Đảm bảo 1 class chỉ có 1 instance và cung cấp 1 điểm truy xuất toàn cục đến nó.
 vd: https://github.com/OmarElgabry/DesignPatterns/tree/master/src/singleton
 
•	Abstract Factory:
o	Cung cấp một interface cho việc tạo lập các đối tượng (có liên hệ với nhau) mà không cần qui định lớp khi hay xác định lớp cụ thể (concrete) tạo mỗi đối tượng.
vd: 

•	Factory Method:
o	Định nghĩa Interface để sinh ra đối tượng nhưng để cho lớp con quyết định lớp nào được dùng để sinh ra đối tượng Factory method cho phép một lớp chuyển quá trình khởi tạo đối tượng cho lớp con.
vd: https://github.com/OmarElgabry/DesignPatterns/tree/master/src/factory

•	Builder:
o	Tách rời việc xây dựng (construction) một đối tượng phức tạp khỏi biểu diễn của nó sao cho cùng một tiến trình xây dựng có thể tạo được các biểu diễn khác nhau.
vd: 

•	Prototype:
o	Qui định loại của các đối tượng cần tạo bằng cách dùng một đối tượng mẫu, tạo mới nhờ vào sao chép đối tượng mẫu này.
vd: 

•	Adapter:
o	Do vấn đề tương thích, thay đổi interface của một lớp thành một interface khác phù hợp với yêu cầu người sử dụng lớp.
vd: 
•	Bridge:
o	Tách rời ngữ nghĩa của một vấn đề khỏi việc cài đặt, mục đích để cả hai bộ phận (ngữ nghĩa và cài đặt) có thể thay đổi độc lập nhau.
vd: https://github.com/OmarElgabry/DesignPatterns/tree/master/src/bridge
•	Composite:
o	Tổ chức các đối tượng theo cấu trúc phân cấp dạng cây. Tất cả các đối tượng trong cấu trúc được thao tác theo một cách thuần nhất như nhau.
Tạo quan hệ thứ bậc bao gộp giữa các đối tượng. Client có thể xem đối tượng bao gộp và bị bao gộp như nhau -> khả năng tổng quát hoá trong code của client -> dễ phát triển, nâng cấp, bảo trì.
vd: https://github.com/OmarElgabry/DesignPatterns/tree/master/src/composite

•	Decorator:
o	Gán thêm trách nhiệm cho đối tượng (mở rộng chức năng) vào lúc chạy (dynamically).

•	Facade:

o	Cung cấp một interface thuần nhất cho một tập hợp các interface trong một “hệ thống con” (subsystem). Nó định nghĩa 1 interface cao hơn các interface có sẵn để làm cho hệ thống con dễ sử dụng hơn.

•	Flyweight:

o	Sử dụng việc chia sẻ để thao tác hiệu quả trên một số lượng lớn đối tượng “cở nhỏ” (chẳng hạn paragraph, dòng, cột, ký tự…).

•	Proxy:

o	Cung cấp đối tượng đại diện cho một đối tượng khác để hỗ trợ hoặc kiểm soát quá trình truy xuất đối tượng đó. Đối tượng thay thế gọi là proxy.

•	Chain of Responsibility: 

o	Khắc phục việc ghép cặp giữa bộ gởi và bộ nhận thông điệp. Các đối tượng nhận thông điệp được kết nối thành một chuỗi và thông điệp được chuyển dọc theo chuỗi nầy đến khi gặp được đối tượng xử lý nó. Tránh việc gắn kết cứng giữa phần tử gởi request với phần tử nhận và xử lý request bằng cách cho phép hơn 1 đối tượng có có cơ hội xử lý request. Liên kết các đối tượng nhận request thành 1 dây chuyền rồi gửi request xuyên qua từng đối tượng xử lý đến khi gặp đối tượng xử lý cụ thể.

•	Command: 

o	Mỗi yêu cầu (thực hiện một thao tác nào đó) được bao bọc thành một đối tượng. Các yêu cầu sẽ được lưu trữ và gởi đi như các đối tượng.Đóng gói request vào trong một Object, nhờ đó có thể nthông số hoá chương trình nhận request và thực hiện các thao tác trên request: sắp xếp, log, undo…

•	Interpreter: 

o	Hỗ trợ việc định nghĩa biểu diễn văn phạm và bộ thông dịch cho một ngôn ngữ.

•	Iterator: 

o	Truy xuất các phần tử của đối tượng dạng tập hợp tuần tự (list, array, …) mà không phụ thuộc vào biểu diễn bên trong của các phần tử.

•	Mediator: 

o	Định nghĩa một đối tượng để bao bọc việc giao tiếp giữa một số đối tượng với nhau.



