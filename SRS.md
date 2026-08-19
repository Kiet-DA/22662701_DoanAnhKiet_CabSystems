Bước 1:Business Context
1. Doanh nghiệp hiện tại
Công ty ABC là doanh nghiệp cung cấp dịch vụ đặt xe trực tuyến. Hiện khách hàng có thể yêu cầu xe thông qua tổng đài hoặc một ứng dụng đơn giản. 
2. Hiện trạng hoạt động
Hệ thống hiện tại có một số hạn chế chính:
Việc phân công tài xế chủ yếu được thực hiện thủ công. 
Khách hàng khó theo dõi trạng thái chuyến đi. 
Thông tin thanh toán chưa được quản lý tập trung. 
Bộ phận vận hành gặp khó khăn khi muốn mở rộng hệ thống. 
3. Nhu cầu thay đổi của doanh nghiệp
Ban lãnh đạo muốn chuyển từ hệ thống hiện tại sang một nền tảng CAB mới, có khả năng:
Phục vụ số lượng lớn khách hàng và tài xế. 
Hỗ trợ toàn bộ quy trình đặt xe. 
Cho phép doanh nghiệp phát triển thêm các tính năng trong tương lai. 
4. Bối cảnh vận hành của hệ thống mới
Hệ thống mới được kỳ vọng hỗ trợ ba nhóm người dùng chính:
Khách hàng 
Tài xế 
Nhân viên vận hành 
Nền tảng cần hỗ trợ xuyên suốt quy trình:
Tạo yêu cầu đặt xe → Tìm và phân công tài xế → Thực hiện chuyến → Tính cước → Thanh toán → Thông báo → Đánh giá sau chuyến. 
5. Bối cảnh mở rộng trong tương lai
Doanh nghiệp không chỉ muốn giải quyết vấn đề hiện tại mà còn muốn nền tảng có khả năng thay đổi và mở rộng, chẳng hạn:
Bổ sung loại dịch vụ mới. 
Thêm phương thức thanh toán. 
Thêm nhà cung cấp thông báo. 
Thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng.
Bước 2: Stakeholder
Stakeholder chính
Stakeholder	Vai trò trong dự án	Mối quan tâm / nhu cầu
Ban giám đốc / Ban lãnh đạo ABC	Định hướng và quyết định	Muốn hệ thống phục vụ quy mô lớn, có khả năng mở rộng và có báo cáo về hoạt động, doanh thu, hiệu quả tài xế
Khách hàng	Người sử dụng dịch vụ	Đăng ký, đặt xe, theo dõi chuyến, thanh toán, xem lịch sử và đánh giá tài xế
Tài xế	Người cung cấp dịch vụ vận chuyển	Quản lý hồ sơ/phương tiện, nhận và xử lý chuyến, cập nhật trạng thái, cung cấp vị trí
Nhân viên vận hành	Người trực tiếp vận hành hệ thống	Quản lý khách hàng, tài xế, phương tiện, chuyến đi; giám sát và xử lý sự cố
Nhà cung cấp thanh toán bên ngoài	Hệ thống/đối tác tích hợp	Xử lý thanh toán điện tử và trả kết quả giao dịch
Nhà cung cấp dịch vụ thông báo	Hệ thống/đối tác tích hợp	Gửi thông báo đến khách hàng và tài xế
Bước 3: Business goal
ID	Business Goal	Ý nghĩa đối với doanh nghiệp
BG01	Tự động hóa việc tìm và phân công tài xế	Giảm phụ thuộc vào phân công thủ công, nâng cao hiệu quả vận hành
BG02	Nâng cao trải nghiệm khách hàng	Cho khách hàng theo dõi quá trình đặt xe, tài xế, ETA, trạng thái chuyến, thanh toán và đánh giá
BG03	Tập trung hóa quản lý vận hành	Giúp nhân viên quản lý khách hàng, tài xế, phương tiện, chuyến đi và giao dịch trên một hệ thống
BG04	Nâng cao khả năng kiểm soát hoạt động kinh doanh	Cung cấp dữ liệu về số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế
BG05	Đảm bảo hệ thống có khả năng mở rộng	Có thể phục vụ số lượng lớn khách hàng/tài xế và mở rộng các thành phần khi tải tăng
BG06	Đảm bảo hoạt động ổn định và hạn chế ảnh hưởng của lỗi	Lỗi ở thanh toán hoặc thông báo không làm toàn bộ hệ thống đặt xe ngừng hoạt động
BG07	Tạo nền tảng linh hoạt cho phát triển dài hạn	Có thể bổ sung dịch vụ, phương thức thanh toán, nhà cung cấp thông báo và thay đổi thành phần kỹ thuật mà không phải xây dựng lại toàn bộ hệ thống
Bước 4: Scope
Project Scope
In Scope
A. Quản lý tài khoản và thông tin người dùng
Hệ thống hỗ trợ:
Khách hàng đăng ký, đăng nhập và cập nhật thông tin cá nhân. 
Tài xế đăng ký hoặc được nhân viên vận hành tạo tài khoản. 
Tài xế cập nhật hồ sơ và thông tin phương tiện. 
Xác thực người dùng trước khi sử dụng chức năng yêu cầu tài khoản. 

B. Đặt xe
Hệ thống hỗ trợ khách hàng:
Nhập điểm đón. 
Nhập điểm đến. 
Chọn loại xe. 
Gửi yêu cầu đặt xe. 
Theo dõi trạng thái của yêu cầu. 

C. Tìm và phân công tài xế
Đây là một phần cốt lõi của scope.
Hệ thống phải:
Tìm tài xế phù hợp. 
Xem xét vị trí. 
Xem trạng thái sẵn sàng. 
Áp dụng các tiêu chí vận hành. 
Ưu tiên tài xế phù hợp và gần khách hàng. 
Xử lý trường hợp tài xế từ chối. 
Xử lý trường hợp tài xế không phản hồi. 
Tự động tiếp tục tìm tài xế khác. 
Thông báo cho khách hàng khi không tìm được tài xế. 

D. Quản lý và theo dõi chuyến đi
Hệ thống hỗ trợ:
Tài xế nhận/chấp nhận/từ chối chuyến. 
Tài xế cập nhật trạng thái chuyến. 
Theo dõi trạng thái tài xế. 
Lưu thông tin vị trí tài xế. 
Hỗ trợ xác định ETA. 
Khách hàng theo dõi chuyến đi. 

E. Tính cước và thanh toán
Hệ thống phải hỗ trợ:
Xác định số tiền khách hàng phải trả. 
Tính cước sau khi chuyến hoàn thành. 
Thanh toán bằng tiền mặt. 
Thanh toán điện tử. 
Tích hợp nhà cung cấp thanh toán bên ngoài. 
Thông báo khi thanh toán điện tử thất bại. 
Cho phép xử lý lại theo chính sách doanh nghiệp. 
Thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán không được lưu trực tiếp trong CAB. 

F. Notification
Hệ thống hỗ trợ thông báo cho:
Khách hàng
Booking được tiếp nhận. 
Có tài xế nhận chuyến. 
Tài xế đến điểm đón. 
Chuyến hoàn thành. 
Kết quả thanh toán. 
Tài xế
Có chuyến mới. 
Có thay đổi liên quan đến chuyến. 
Ngoài ra, hệ thống phải có khả năng mở rộng thêm các kênh thông báo trong tương lai. 

G. Lịch sử và đánh giá
Khách hàng có thể:
Xem lịch sử chuyến đi. 
Xem số tiền phải trả. 
Đánh giá tài xế sau khi chuyến hoàn thành. 

H. Operation / Admin Portal
Hệ thống cung cấp giao diện quản trị để nhân viên vận hành:
Quản lý khách hàng. 
Quản lý tài xế. 
Quản lý phương tiện. 
Quản lý chuyến đi. 
Xem các chuyến đang diễn ra. 
Kiểm tra trạng thái tài xế. 
Hỗ trợ xử lý chuyến bị lỗi. 
Tra cứu lịch sử giao dịch. 
Thực hiện các thao tác theo phân quyền. 

I. Reporting
Hệ thống hỗ trợ báo cáo về:
Số lượng chuyến. 
Doanh thu. 
Tỷ lệ chuyến hoàn thành. 
Tỷ lệ hủy. 
Hiệu quả hoạt động của tài xế. 

J. Security, Audit và khả năng mở rộng
Trong scope còn có các yêu cầu nền tảng:
Kiểm soát xác thực. 
Phân quyền thao tác quản trị. 
Bảo vệ dữ liệu cá nhân. 
Bảo vệ dữ liệu phương tiện. 
Bảo vệ dữ liệu vị trí. 
Bảo vệ dữ liệu giao dịch. 
Lưu vết các thao tác quan trọng. 
Có khả năng scale các thành phần độc lập. 
Một lỗi ở payment/notification không làm toàn bộ hệ thống đặt xe dừng hoạt động. 
Có khả năng triển khai chức năng mới từng phần. 

2. Out of Scope / Chưa thuộc phạm vi đã xác định
Ở đây cần rất cẩn thận: file không đưa ra danh sách Out of Scope chính thức. Vì vậy không nên tự kết luận một chức năng là “không làm”.
Thay vào đó, những nội dung sau nên được đánh dấu là:
“Chưa xác định / cần xác nhận”
Chi tiết công thức tính cước. 
Tiêu chí chính xác để ưu tiên tài xế. 
Thời gian tài xế phải phản hồi. 
Chính sách hủy chuyến. 
Cách xử lý cụ thể khi mất kết nối mạng. 
Thời gian lưu trữ dữ liệu. 
Đây là open scope / scope clarification, chưa phải Out of Scope.
Bước 5: Business requirements
Business Requirements của dự án
ID	Business Requirement	Nội dung
BR01	Xây dựng nền tảng đặt xe tập trung	ABC cần một nền tảng CAB mới để hỗ trợ xuyên suốt quy trình từ khi khách hàng tạo yêu cầu đặt xe đến khi chuyến hoàn thành, thanh toán và đánh giá.
BR02	Tự động hóa việc tìm và phân công tài xế	Hệ thống phải giảm sự phụ thuộc vào việc phân công thủ công bằng cách tự động xác định và đề xuất tài xế phù hợp.
BR03	Nâng cao trải nghiệm khách hàng	Hệ thống phải giúp khách hàng dễ dàng đặt xe, theo dõi tài xế, trạng thái chuyến, chi phí và kết quả thanh toán.
BR04	Hỗ trợ tài xế thực hiện dịch vụ trên nền tảng	Hệ thống phải hỗ trợ tài xế quản lý hồ sơ/phương tiện, nhận chuyến, thực hiện chuyến và cập nhật trạng thái.
BR05	Tập trung hóa hoạt động vận hành	ABC cần một giao diện quản trị để nhân viên vận hành quản lý khách hàng, tài xế, phương tiện, chuyến đi và giao dịch.
BR06	Quản lý và hỗ trợ thanh toán	Hệ thống phải hỗ trợ tính cước, thanh toán tiền mặt/điện tử và tích hợp với nhà cung cấp thanh toán bên ngoài.
BR07	Cung cấp cơ chế thông báo xuyên suốt quy trình	Hệ thống phải thông báo cho khách hàng và tài xế tại các sự kiện quan trọng của chuyến đi và thanh toán.
BR08	Cung cấp dữ liệu phục vụ quản trị kinh doanh	Hệ thống phải cung cấp thông tin và báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả tài xế.
BR09	Đảm bảo hệ thống có khả năng mở rộng	Hệ thống phải có khả năng phục vụ số lượng lớn khách hàng/tài xế và cho phép các thành phần mở rộng độc lập khi tải tăng.
BR10	Đảm bảo tính ổn định và khả năng chịu lỗi	Lỗi ở một thành phần như thanh toán hoặc thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động.
BR11	Đảm bảo an toàn và kiểm soát dữ liệu	Hệ thống phải xác thực người dùng, kiểm soát quyền truy cập và bảo vệ dữ liệu cá nhân, phương tiện, vị trí và giao dịch.
BR12	Tạo nền tảng cho mở rộng trong tương lai	Hệ thống phải cho phép bổ sung loại dịch vụ, phương thức thanh toán, nhà cung cấp thông báo và thay đổi thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng.


Bước 6: Business process

1. Business Process tổng thể
Quy trình nghiệp vụ cốt lõi của CAB có thể mô tả:
Khách hàng
    │
    ▼
Tạo yêu cầu đặt xe
    │
    ▼
Hệ thống tiếp nhận booking
    │
    ▼
Tìm tài xế phù hợp
    │
    ├── Không tìm được ──► Thông báo khách hàng
    │
    ▼
Gửi yêu cầu cho tài xế
    │
    ├── Từ chối / Không phản hồi
    │          │
    │          ▼
    │     Tìm tài xế khác
    │
    ▼
Tài xế nhận chuyến
    │
    ▼
Tài xế đến điểm đón
    │
    ▼
Đón khách
    │
    ▼
Thực hiện chuyến
    │
    ▼
Hoàn thành chuyến
    │
    ▼
Tính cước
    │
    ▼
Thanh toán
    │
    ├── Thất bại ──► Thông báo + xử lý lại
    │
    ▼
Thông báo kết quả
    │
    ▼
Khách hàng đánh giá tài xế
Các nhánh tìm tài xế và thanh toán thất bại được nêu trực tiếp trong tài liệu. 

2. Các Business Process chính
BP01 — Quản lý tài khoản
Mục đích
Cho phép người dùng có tài khoản truy cập và sử dụng các chức năng yêu cầu xác thực.
Luồng
Đăng ký/được tạo tài khoản → Đăng nhập → Xác thực → Cập nhật thông tin cá nhân
Khách hàng có thể tự đăng ký và cập nhật thông tin; tài xế có thể đăng ký hoặc được nhân viên vận hành tạo tài khoản. 

3. BP02 — Đặt xe
Actor
Customer
Luồng chính
Đăng nhập
   ↓
Nhập điểm đón
   ↓
Nhập điểm đến
   ↓
Chọn loại xe
   ↓
Gửi yêu cầu đặt xe
   ↓
Hệ thống tiếp nhận
Khách hàng cần được thông báo khi yêu cầu đặt xe được tiếp nhận. 

4. BP03 — Tìm và phân công tài xế
Đây là core business process của CAB.
Luồng chính
Booking mới
    ↓
Xác định tài xế phù hợp
    ↓
Kiểm tra:
- Vị trí
- Trạng thái sẵn sàng
- Tiêu chí vận hành
    ↓
Ưu tiên tài xế phù hợp/gần khách
    ↓
Gửi đề xuất chuyến
Nhánh ngoại lệ
Driver nhận
   ↓
Assign Driver
hoặc:
Driver từ chối
      ↓
Tìm Driver tiếp theo
hoặc:
Driver không phản hồi
      ↓
Tìm Driver tiếp theo
Nếu không còn tài xế phù hợp:
Không tìm được tài xế
        ↓
Thông báo khách hàng
Toàn bộ logic này được mô tả trong file. 

5. BP04 — Thực hiện chuyến
Actor
Driver
Sau khi nhận chuyến, tài xế thực hiện các bước:
Nhận chuyến
   ↓
Đến điểm đón
   ↓
Đã đón khách
   ↓
Đang di chuyển
   ↓
Hoàn thành chuyến
Trong quá trình này, hệ thống lưu thông tin vị trí tài xế để hỗ trợ tìm tài xế gần khách hàng và cải thiện ETA. 

6. BP05 — Theo dõi chuyến
Đây là process có sự tham gia của Customer + Driver + Operation.
Customer
Theo dõi:
Đang tìm tài xế. 
Tài xế nào nhận chuyến. 
Thời gian dự kiến tài xế đến. 
Trạng thái chuyến. 
Driver
Cập nhật:
Đã đến điểm đón. 
Đã đón khách. 
Đang di chuyển. 
Hoàn thành. 
Operation
Theo dõi các chuyến đang diễn ra và trạng thái tài xế. 

7. BP06 — Tính cước và thanh toán
Luồng nghiệp vụ
Chuyến hoàn thành
      ↓
Xác định số tiền phải trả
      ↓
┌───────────────────────┐
│ Phương thức thanh toán│
└───────────┬───────────┘
            │
      ┌─────┴─────┐
      ↓           ↓
   Tiền mặt    Điện tử
                  ↓
          Payment Provider
                  ↓
          ┌───────┴───────┐
          ↓               ↓
       Thành công       Thất bại
          ↓               ↓
   Hoàn tất thanh toán   Thông báo
                          ↓
                       Xử lý lại
Tài liệu yêu cầu hỗ trợ tiền mặt và thanh toán điện tử, tích hợp nhà cung cấp bên ngoài, đồng thời xử lý trường hợp giao dịch điện tử thất bại. 

8. BP07 — Notification
Notification không phải một process độc lập hoàn toàn mà là supporting process xuyên suốt vòng đời booking/trip.
Customer nhận thông báo khi:
Booking được tiếp nhận. 
Driver nhận chuyến. 
Driver đến điểm đón. 
Chuyến hoàn thành. 
Thanh toán có kết quả. 
Driver nhận thông báo khi:
Có chuyến mới. 
Có thay đổi liên quan đến chuyến. 

9. BP08 — Đánh giá sau chuyến
Actor
Customer
Trip Completed
      ↓
Xem thông tin chuyến
      ↓
Đánh giá Driver
Khách hàng được yêu cầu có khả năng đánh giá tài xế sau khi hoàn thành chuyến. 

10. BP09 — Vận hành và xử lý sự cố
Actor
Operation Staff
Nhân viên vận hành thực hiện:
Theo dõi hoạt động
      ↓
Phát hiện chuyến/vấn đề bất thường
      ↓
Kiểm tra trạng thái
      ↓
Hỗ trợ xử lý
      ↓
Tra cứu giao dịch / lịch sử
Đồng thời quản lý:
Customer. 
Driver. 
Vehicle. 
Trip. 
và sử dụng chức năng theo phân quyền. 

11. BP10 — Báo cáo quản trị
Actor
Ban lãnh đạo / Operation
Quy trình:
Dữ liệu hoạt động
       ↓
Tổng hợp
       ↓
Phân tích
       ↓
Báo cáo
       ↓
Theo dõi KPI
Các chỉ số được tài liệu nêu gồm:
Số lượng chuyến. 
Doanh thu. 
Tỷ lệ hoàn thành. 
Tỷ lệ hủy. 
Hiệu quả tài xế. 

12. Tổng hợp Business Process Map
ID	Business Process	Actor chính
BP01	Quản lý tài khoản	Customer / Driver / Operation
BP02	Đặt xe	Customer
BP03	Tìm & phân công tài xế	CAB System / Driver
BP04	Thực hiện chuyến	Driver
BP05	Theo dõi chuyến	Customer / Driver / Operation
BP06	Tính cước & thanh toán	Customer / CAB / Payment Provider
BP07	Thông báo	CAB / Notification Provider
BP08	Đánh giá sau chuyến	Customer
BP09	Vận hành & xử lý sự cố	Operation
BP10	Báo cáo quản trị	Operation / Management

Bước 7: Functional requirement

Dựa **chỉ trên nội dung file**, dưới đây là bảng Functional Requirements được chuẩn hóa theo dạng **ID – Module – Actor – Functional Requirement – Priority – Ghi chú**. Các yêu cầu chưa được file chốt chi tiết được đánh dấu **TBC (To Be Confirmed)** thay vì tự bổ sung. 

### Bảng Functional Requirements

| ID       | Module              | Actor                | Functional Requirement                                                                         | Priority | Ghi chú                 |
| -------- | ------------------- | -------------------- | ---------------------------------------------------------------------------------------------- | -------- | ----------------------- |
| **FR01** | Account             | Customer             | Hệ thống cho phép khách hàng đăng ký tài khoản                                                 | Must     |                         |
| **FR02** | Account             | Customer             | Hệ thống cho phép khách hàng đăng nhập                                                         | Must     |                         |
| **FR03** | Account             | Customer             | Hệ thống cho phép khách hàng cập nhật thông tin cá nhân                                        | Must     |                         |
| **FR04** | Driver Management   | Driver               | Hệ thống cho phép tài xế đăng ký tài khoản                                                     | Must     |                         |
| **FR05** | Driver Management   | Operation            | Hệ thống cho phép nhân viên vận hành tạo tài khoản cho tài xế                                  | Must     |                         |
| **FR06** | Driver Management   | Driver               | Hệ thống cho phép tài xế cập nhật hồ sơ                                                        | Must     |                         |
| **FR07** | Vehicle Management  | Driver               | Hệ thống cho phép tài xế cập nhật thông tin phương tiện                                        | Must     |                         |
| **FR08** | Driver Availability | Driver               | Hệ thống cho phép tài xế chuyển sang trạng thái sẵn sàng nhận chuyến                           | Must     |                         |
| **FR09** | Booking             | Customer             | Hệ thống cho phép khách hàng nhập điểm đón                                                     | Must     |                         |
| **FR10** | Booking             | Customer             | Hệ thống cho phép khách hàng nhập điểm đến                                                     | Must     |                         |
| **FR11** | Booking             | Customer             | Hệ thống cho phép khách hàng lựa chọn loại xe                                                  | Must     |                         |
| **FR12** | Booking             | Customer             | Hệ thống cho phép khách hàng gửi yêu cầu đặt xe                                                | Must     |                         |
| **FR13** | Driver Matching     | System               | Hệ thống xác định các tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành | Must     |                         |
| **FR14** | Driver Matching     | System               | Hệ thống ưu tiên tài xế phù hợp và gần khách hàng                                              | Must     | Tiêu chí cụ thể TBC     |
| **FR15** | Driver Matching     | Driver               | Hệ thống gửi thông báo chuyến phù hợp cho tài xế                                               | Must     |                         |
| **FR16** | Driver Matching     | Driver               | Hệ thống cho phép tài xế chấp nhận chuyến                                                      | Must     |                         |
| **FR17** | Driver Matching     | Driver               | Hệ thống cho phép tài xế từ chối chuyến                                                        | Must     |                         |
| **FR18** | Driver Matching     | System               | Khi tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác                      | Must     | Timeout TBC             |
| **FR19** | Driver Matching     | Customer             | Hệ thống thông báo cho khách hàng khi không tìm được tài xế                                    | Must     |                         |
| **FR20** | Trip Tracking       | Customer             | Hệ thống hiển thị trạng thái đang tìm tài xế                                                   | Must     |                         |
| **FR21** | Trip Tracking       | Customer             | Hệ thống hiển thị tài xế đã nhận chuyến                                                        | Must     |                         |
| **FR22** | Trip Tracking       | Customer             | Hệ thống cung cấp thời gian dự kiến tài xế đến                                                 | Must     |                         |
| **FR23** | Trip Management     | Driver               | Hệ thống cho phép tài xế cập nhật trạng thái “đã đến điểm đón”                                 | Must     |                         |
| **FR24** | Trip Management     | Driver               | Hệ thống cho phép tài xế cập nhật trạng thái “đã đón khách”                                    | Must     |                         |
| **FR25** | Trip Management     | Driver               | Hệ thống cho phép tài xế cập nhật trạng thái “đang di chuyển”                                  | Must     |                         |
| **FR26** | Trip Management     | Driver               | Hệ thống cho phép tài xế cập nhật trạng thái “hoàn thành chuyến”                               | Must     |                         |
| **FR27** | Location            | Driver/System        | Hệ thống lưu thông tin vị trí của tài xế                                                       | Must     |                         |
| **FR28** | Location            | System               | Hệ thống sử dụng thông tin vị trí để hỗ trợ tìm tài xế gần khách hàng và cải thiện ETA         | Must     |                         |
| **FR29** | Trip History        | Customer             | Hệ thống cho phép khách hàng xem lịch sử chuyến đi                                             | Should   |                         |
| **FR30** | Fare                | Customer             | Hệ thống hiển thị số tiền khách hàng phải trả                                                  | Must     |                         |
| **FR31** | Rating              | Customer             | Hệ thống cho phép khách hàng đánh giá tài xế sau chuyến                                        | Should   |                         |
| **FR32** | Fare                | System               | Hệ thống xác định số tiền phải trả dựa trên loại dịch vụ và thông tin chuyến đi                | Must     | Công thức tính cước TBC |
| **FR33** | Payment             | Customer             | Hệ thống hỗ trợ thanh toán bằng tiền mặt                                                       | Must     |                         |
| **FR34** | Payment             | Customer             | Hệ thống hỗ trợ thanh toán điện tử                                                             | Must     |                         |
| **FR35** | Payment             | System               | Hệ thống tích hợp với nhà cung cấp thanh toán bên ngoài                                        | Must     |                         |
| **FR36** | Payment             | System               | Hệ thống không lưu trực tiếp thông tin nhạy cảm của thẻ/tài khoản thanh toán                   | Must     |                         |
| **FR37** | Payment             | System               | Hệ thống thông báo cho khách hàng khi thanh toán điện tử thất bại                              | Must     |                         |
| **FR38** | Payment             | Customer/System      | Hệ thống cho phép xử lý lại thanh toán theo chính sách doanh nghiệp                            | Must     | Chính sách retry TBC    |
| **FR39** | Notification        | Customer             | Hệ thống thông báo khi yêu cầu đặt xe được tiếp nhận                                           | Must     |                         |
| **FR40** | Notification        | Customer             | Hệ thống thông báo khi tài xế nhận chuyến                                                      | Must     |                         |
| **FR41** | Notification        | Customer             | Hệ thống thông báo khi tài xế đến điểm đón                                                     | Must     |                         |
| **FR42** | Notification        | Customer             | Hệ thống thông báo khi chuyến hoàn thành                                                       | Must     |                         |
| **FR43** | Notification        | Customer             | Hệ thống thông báo kết quả thanh toán                                                          | Must     |                         |
| **FR44** | Notification        | Driver               | Hệ thống thông báo cho tài xế về chuyến mới                                                    | Must     |                         |
| **FR45** | Notification        | Driver               | Hệ thống thông báo cho tài xế về thay đổi liên quan đến chuyến đang thực hiện                  | Must     |                         |
| **FR46** | Notification        | System               | Hệ thống hỗ trợ mở rộng thêm các kênh thông báo trong tương lai                                | Should   |                         |
| **FR47** | Operation           | Operation            | Hệ thống cho phép nhân viên vận hành quản lý khách hàng                                        | Must     |                         |
| **FR48** | Operation           | Operation            | Hệ thống cho phép nhân viên vận hành quản lý tài xế                                            | Must     |                         |
| **FR49** | Operation           | Operation            | Hệ thống cho phép nhân viên vận hành quản lý phương tiện                                       | Must     |                         |
| **FR50** | Operation           | Operation            | Hệ thống cho phép nhân viên vận hành quản lý chuyến đi                                         | Must     |                         |
| **FR51** | Monitoring          | Operation            | Hệ thống cho phép nhân viên vận hành xem các chuyến đang diễn ra                               | Must     |                         |
| **FR52** | Monitoring          | Operation            | Hệ thống cho phép nhân viên vận hành kiểm tra trạng thái tài xế                                | Must     |                         |
| **FR53** | Operation Support   | Operation            | Hệ thống hỗ trợ nhân viên xử lý các trường hợp chuyến bị lỗi                                   | Must     |                         |
| **FR54** | Transaction         | Operation            | Hệ thống cho phép tra cứu lịch sử giao dịch                                                    | Must     |                         |
| **FR55** | Authorization       | Operation            | Hệ thống phân quyền để nhân viên thông thường không thực hiện được thao tác nhạy cảm           | Must     |                         |
| **FR56** | Reporting           | Management/Operation | Hệ thống cung cấp báo cáo số lượng chuyến                                                      | Should   |                         |
| **FR57** | Reporting           | Management/Operation | Hệ thống cung cấp báo cáo doanh thu                                                            | Must     |                         |
| **FR58** | Reporting           | Management/Operation | Hệ thống cung cấp tỷ lệ chuyến hoàn thành                                                      | Should   |                         |
| **FR59** | Reporting           | Management/Operation | Hệ thống cung cấp tỷ lệ hủy                                                                    | Should   |                         |
| **FR60** | Reporting           | Management/Operation | Hệ thống cung cấp hiệu quả hoạt động của tài xế                                                | Should   |                         |
| **FR61** | Authentication      | Customer/Driver      | Hệ thống xác thực khách hàng và tài xế trước khi sử dụng chức năng yêu cầu tài khoản           | Must     |                         |
| **FR62** | Security            | System               | Hệ thống kiểm soát quyền truy cập đối với các thao tác quản trị                                | Must     |                         |
| **FR63** | Security            | System               | Hệ thống bảo vệ thông tin cá nhân                                                              | Must     |                         |
| **FR64** | Security            | System               | Hệ thống bảo vệ thông tin phương tiện                                                          | Must     |                         |
| **FR65** | Security            | System               | Hệ thống bảo vệ dữ liệu vị trí                                                                 | Must     |                         |
| **FR66** | Security            | System               | Hệ thống bảo vệ dữ liệu giao dịch                                                              | Must     |                         |
| **FR67** | Audit               | System               | Hệ thống lưu vết các thao tác quan trọng để phục vụ kiểm tra khi có sự cố                      | Must     |                         |

### Lưu ý về Priority

File **không quy định trực tiếp mức ưu tiên Must/Should**. Vì vậy cột Priority ở trên là **đề xuất phân loại phục vụ BA**, không phải priority đã được ABC xác nhận.

Đặc biệt, các requirement sau cần làm rõ trước khi đặc tả chi tiết:

| Requirement     | Nội dung cần xác nhận                    |
| --------------- | ---------------------------------------- |
| FR14            | Tiêu chí và thuật toán ưu tiên tài xế    |
| FR18            | Thời gian chờ phản hồi của tài xế        |
| FR32            | Công thức tính cước                      |
| FR38            | Chính sách retry khi thanh toán thất bại |
| Cancellation    | Quy tắc hủy chuyến                       |
| Network Failure | Cách xử lý khi mất kết nối               |
| Data Retention  | Thời gian lưu trữ dữ liệu                |

Các điểm này được tài liệu xác định rõ là **chưa chốt và cần BA làm rõ với các bên liên quan**. 

### Nhóm Functional Requirement theo module

Để dùng cho các bước tiếp theo, tôi khuyến nghị gom thành 10 module:

**Account & Authentication → Driver & Vehicle → Booking → Driver Matching → Trip & Location → Fare & Payment → Notification → Operation → Reporting → Security & Audit**

Cách phân nhóm này sẽ thuận tiện để chuyển tiếp sang **Use Case Diagram, Use Case Specification và Acceptance Criteria**.

