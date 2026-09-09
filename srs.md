# BƯỚC 1. ĐỌC VÀ PHÂN TÍCH YÊU CẦU SƠ KHỞI CỦA KHÁCH HÀNG

## 1.1. Ngữ cảnh nghiệp vụ

Công ty ABC là doanh nghiệp cung cấp dịch vụ đặt xe trực tuyến. Hiện tại, khách hàng có thể liên hệ tổng đài hoặc sử dụng một ứng dụng đơn giản để yêu cầu xe. Tuy nhiên, hệ thống hiện tại còn hạn chế ở việc phân công tài xế chủ yếu thực hiện thủ công, khách hàng khó theo dõi trạng thái chuyến đi, thông tin thanh toán chưa được quản lý tập trung và bộ phận vận hành gặp khó khăn khi muốn mở rộng hệ thống.

Ban lãnh đạo mong muốn xây dựng một nền tảng CAB mới có khả năng phục vụ số lượng lớn khách hàng và tài xế, đồng thời có thể phát triển thêm các tính năng trong tương lai.

## 1.2. Vấn đề nghiệp vụ hiện tại

- Phân công tài xế chủ yếu thực hiện thủ công.
- Khách hàng khó theo dõi trạng thái chuyến đi.
- Thông tin thanh toán chưa được quản lý tập trung.
- Bộ phận vận hành gặp khó khăn khi mở rộng hệ thống.
- Khi tài xế không phản hồi hoặc từ chối, hệ thống cần có cơ chế tiếp tục tìm tài xế khác.
- Doanh nghiệp cần có dữ liệu để theo dõi hoạt động và báo cáo.

## 1.3. Nhu cầu chính của khách hàng

- Tự động tìm và phân công tài xế.
- Cho phép khách hàng đặt xe và theo dõi chuyến đi.
- Hỗ trợ tính cước và thanh toán.
- Hỗ trợ thông báo.
- Cho phép khách hàng đánh giá tài xế.
- Hỗ trợ nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến đi.
- Cung cấp báo cáo hoạt động.
- Đảm bảo hệ thống ổn định, bảo mật và có khả năng mở rộng.

## 1.4. Các vấn đề chưa được chốt

- Cách tính cước.
- Tiêu chí ưu tiên tài xế.
- Thời gian tài xế phải phản hồi.
- Chính sách hủy chuyến.
- Cách xử lý khi mất kết nối mạng.
- Thời gian lưu trữ dữ liệu.


---

# BƯỚC 2. XÁC ĐỊNH STAKEHOLDER

## 2.1. Stakeholder và vai trò

| Stakeholder | Vai trò |
|---|---|
| Ban giám đốc Công ty ABC | Đưa ra định hướng, kỳ vọng của doanh nghiệp và theo dõi báo cáo về hoạt động kinh doanh. |
| Khách hàng | Đăng ký tài khoản, đăng nhập, cập nhật thông tin, đặt xe, theo dõi chuyến đi, xem lịch sử, xem số tiền phải trả và đánh giá tài xế. |
| Tài xế | Quản lý hồ sơ và phương tiện, cập nhật trạng thái hoạt động, nhận/từ chối chuyến, cập nhật trạng thái và vị trí trong quá trình thực hiện chuyến. |
| Nhân viên vận hành | Quản lý khách hàng, tài xế, phương tiện và chuyến đi; theo dõi chuyến đang diễn ra; kiểm tra trạng thái tài xế; xử lý chuyến bị lỗi và tra cứu giao dịch. |
| Nhà cung cấp thanh toán bên ngoài | Cung cấp dịch vụ xử lý thanh toán điện tử cho hệ thống. |

## 2.2. Stakeholder Matrix

| Stakeholder | Mức độ quan tâm | Tầm ảnh hưởng | Chiến lược |
|---|---|---|---|
| Ban giám đốc | Cao | Cao | Quản lý chặt chẽ |
| Nhân viên vận hành | Cao | Cao | Quản lý chặt chẽ |
| Khách hàng | Cao | Trung bình | Giữ liên lạc |
| Tài xế | Cao | Trung bình | Giữ liên lạc |
| Nhà cung cấp thanh toán | Trung bình | Cao đối với thanh toán | Duy trì hài lòng |


---

# BƯỚC 3. BUSINESS GOAL

| Mã | Business Goal |
|---|---|
| BG01 | Tự động hóa quy trình đặt xe và tìm, phân công tài xế. |
| BG02 | Nâng cao khả năng theo dõi và trải nghiệm của khách hàng trong quá trình sử dụng dịch vụ. |
| BG03 | Hỗ trợ tài xế nhận chuyến, cập nhật trạng thái và vị trí trong quá trình thực hiện chuyến. |
| BG04 | Nâng cao hiệu quả quản lý và vận hành dịch vụ đặt xe. |
| BG05 | Quản lý tập trung việc tính cước và thanh toán. |
| BG06 | Cung cấp báo cáo phục vụ theo dõi hoạt động kinh doanh và vận hành. |
| BG07 | Xây dựng nền tảng ổn định, bảo mật, có khả năng mở rộng và phát triển trong tương lai. |

---

# BƯỚC 4. XÁC ĐỊNH PHẠM VI YÊU CẦU (SCOPE)

## 4.1. In Scope

### Quản lý tài khoản

- Đăng ký tài khoản.
- Đăng nhập.
- Cập nhật thông tin cá nhân.

### Quản lý khách hàng

- Quản lý thông tin khách hàng.
- Xem lịch sử chuyến đi.

### Quản lý tài xế

- Đăng ký hoặc được nhân viên vận hành tạo tài khoản.
- Quản lý hồ sơ tài xế.
- Cập nhật trạng thái hoạt động.
- Cập nhật thông tin phương tiện.

### Đặt và thực hiện chuyến

- Nhập điểm đón.
- Nhập điểm đến.
- Lựa chọn loại xe.
- Gửi yêu cầu đặt xe.
- Tìm tài xế phù hợp.
- Phân công tài xế.
- Theo dõi chuyến đi.
- Cập nhật trạng thái chuyến.
- Cập nhật vị trí tài xế.

### Tính cước và thanh toán

- Xác định số tiền phải trả.
- Thanh toán tiền mặt.
- Thanh toán điện tử.
- Tích hợp nhà cung cấp thanh toán bên ngoài.
- Xử lý lại khi thanh toán điện tử thất bại theo chính sách doanh nghiệp.

### Thông báo

- Thông báo tiếp nhận yêu cầu đặt xe.
- Thông báo tài xế nhận chuyến.
- Thông báo tài xế đến điểm đón.
- Thông báo hoàn thành chuyến.
- Thông báo kết quả thanh toán.
- Thông báo cho tài xế về chuyến mới hoặc thay đổi liên quan đến chuyến.

### Đánh giá

- Khách hàng đánh giá tài xế sau khi hoàn thành chuyến.

### Vận hành và báo cáo

- Quản lý khách hàng.
- Quản lý tài xế.
- Quản lý phương tiện.
- Quản lý chuyến đi.
- Theo dõi chuyến đang diễn ra.
- Kiểm tra trạng thái tài xế.
- Xử lý chuyến bị lỗi.
- Tra cứu lịch sử giao dịch.
- Báo cáo số lượng chuyến.
- Báo cáo doanh thu.
- Báo cáo tỷ lệ hoàn thành.
- Báo cáo tỷ lệ hủy.
- Báo cáo hiệu quả hoạt động của tài xế.

## 4.2. Ràng buộc

- Không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán trong hệ thống CAB.
- Thanh toán điện tử được thực hiện thông qua nhà cung cấp thanh toán bên ngoài.

## 4.3. Phạm vi phát triển trong tương lai

- Bổ sung các loại dịch vụ mới.
- Bổ sung phương thức thanh toán mới.
- Bổ sung nhà cung cấp thông báo mới.
- Thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng.

## 4.4. Open Issues / TBD

- Cách tính cước.
- Tiêu chí ưu tiên tài xế.
- Thời gian phản hồi.
- Chính sách hủy.
- Xử lý mất kết nối.
- Thời gian lưu trữ dữ liệu.

---

# BƯỚC 5. BUSINESS REQUIREMENT (BR)

| Mã | Tên | Diễn giải |
|---|---|---|
| BR01 | Đặt xe | Hệ thống hỗ trợ khách hàng tạo yêu cầu đặt xe. |
| BR02 | Tìm và phân công tài xế | Hệ thống hỗ trợ tìm và lựa chọn tài xế phù hợp cho chuyến xe. |
| BR03 | Quản lý chuyến đi | Hệ thống hỗ trợ quản lý và theo dõi quá trình của chuyến xe. |
| BR04 | Quản lý khách hàng | Hệ thống hỗ trợ quản lý thông tin khách hàng và lịch sử chuyến đi. |
| BR05 | Quản lý tài xế | Hệ thống hỗ trợ quản lý hồ sơ và trạng thái hoạt động của tài xế. |
| BR06 | Quản lý phương tiện | Hệ thống hỗ trợ quản lý thông tin phương tiện. |
| BR07 | Tính cước | Hệ thống xác định số tiền khách hàng phải trả sau khi chuyến hoàn thành. |
| BR08 | Thanh toán | Hệ thống hỗ trợ thanh toán bằng tiền mặt hoặc phương thức điện tử. |
| BR09 | Thông báo | Hệ thống hỗ trợ gửi thông báo về các sự kiện liên quan đến chuyến đi và thanh toán. |
| BR10 | Đánh giá | Hệ thống hỗ trợ khách hàng đánh giá tài xế sau khi chuyến hoàn thành. |
| BR11 | Quản lý vận hành | Hệ thống hỗ trợ nhân viên vận hành quản lý và xử lý hoạt động đặt xe. |
| BR12 | Báo cáo | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| BR13 | Bảo mật và phân quyền | Hệ thống bảo vệ dữ liệu và kiểm soát quyền truy cập đối với các chức năng quản trị. |
| BR14 | Khả năng mở rộng | Hệ thống có khả năng mở rộng để bổ sung dịch vụ, phương thức thanh toán và kênh thông báo trong tương lai. |

---

# BƯỚC 6. XÂY DỰNG BUSINESS PROCESS

## 6.1. Quy trình nghiệp vụ đặt xe

1. Khách hàng đăng ký hoặc đăng nhập.
2. Khách hàng nhập điểm đón.
3. Khách hàng nhập điểm đến.
4. Khách hàng lựa chọn loại xe.
5. Khách hàng gửi yêu cầu đặt xe.
6. Hệ thống tiếp nhận yêu cầu.
7. Hệ thống xác định các tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành.
8. Hệ thống gửi yêu cầu đến tài xế phù hợp.
9. Tài xế chấp nhận hoặc từ chối chuyến.
10. Nếu tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác.
11. Nếu không tìm được tài xế, hệ thống thông báo cho khách hàng.
12. Tài xế thực hiện chuyến và cập nhật trạng thái.
13. Khi chuyến hoàn thành, hệ thống xác định số tiền khách hàng phải trả.
14. Khách hàng thanh toán bằng tiền mặt hoặc phương thức điện tử.
15. Hệ thống ghi nhận và thông báo kết quả thanh toán.
16. Khách hàng đánh giá tài xế sau chuyến.

## 6.2. Quy trình quản lý vận hành

1. Nhân viên vận hành đăng nhập.
2. Nhân viên xem các chuyến đang diễn ra.
3. Nhân viên kiểm tra trạng thái tài xế.
4. Nhân viên theo dõi và xử lý các trường hợp chuyến bị lỗi.
5. Nhân viên tra cứu lịch sử giao dịch.
6. Hệ thống cung cấp dữ liệu báo cáo phục vụ quản lý.

---

# BƯỚC 7. PHÂN RÃ YÊU CẦU NGHIỆP VỤ (FRD)

| Mã | Tên yêu cầu | Diễn giải |
|---|---|---|
| FRD01 | Tạo yêu cầu đặt xe | Khách hàng nhập điểm đón, điểm đến và lựa chọn loại xe để gửi yêu cầu. |
| FRD02 | Tìm tài xế | Hệ thống tìm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| FRD03 | Phân công tài xế | Hệ thống gửi yêu cầu đến tài xế phù hợp và ghi nhận tài xế nhận chuyến. |
| FRD04 | Xử lý từ chối/không phản hồi | Hệ thống tiếp tục tìm tài xế khác khi tài xế từ chối hoặc không phản hồi. |
| FRD05 | Thông báo không tìm được tài xế | Hệ thống thông báo rõ ràng cho khách hàng khi không tìm được tài xế. |
| FRD06 | Theo dõi chuyến đi | Khách hàng theo dõi trạng thái chuyến và thông tin tài xế. |
| FRD07 | Cập nhật trạng thái chuyến | Tài xế cập nhật trạng thái trong quá trình thực hiện chuyến. |
| FRD08 | Cập nhật vị trí tài xế | Hệ thống ghi nhận vị trí tài xế để hỗ trợ tìm tài xế gần khách hàng và dự kiến thời gian đến. |
| FRD09 | Tính cước | Hệ thống xác định số tiền khách hàng phải trả sau khi chuyến hoàn thành. |
| FRD10 | Thanh toán | Hệ thống hỗ trợ thanh toán bằng tiền mặt hoặc phương thức điện tử. |
| FRD11 | Xử lý thanh toán điện tử | Hệ thống tích hợp với nhà cung cấp thanh toán bên ngoài và ghi nhận kết quả giao dịch. |
| FRD12 | Thông báo | Hệ thống gửi thông báo đến khách hàng và tài xế về các sự kiện liên quan. |
| FRD13 | Quản lý khách hàng | Nhân viên vận hành quản lý thông tin khách hàng. |
| FRD14 | Quản lý tài xế | Nhân viên vận hành quản lý thông tin tài xế. |
| FRD15 | Quản lý phương tiện | Nhân viên vận hành quản lý thông tin phương tiện. |
| FRD16 | Quản lý chuyến đi | Nhân viên vận hành quản lý và theo dõi chuyến đi. |
| FRD17 | Xử lý chuyến bị lỗi | Nhân viên vận hành hỗ trợ xử lý các trường hợp chuyến bị lỗi. |
| FRD18 | Tra cứu giao dịch | Nhân viên vận hành tra cứu lịch sử giao dịch. |
| FRD19 | Phân quyền | Hệ thống kiểm soát quyền truy cập đối với các chức năng quản trị. |
| FRD20 | Báo cáo | Hệ thống cung cấp báo cáo về hoạt động đặt xe và vận hành. |

---

# BƯỚC 8. BUSINESS RULE VÀ EXCEPTION HANDLING

## 8.1. Business Rules

| Mã | Quy tắc nghiệp vụ |
|---|---|
| BRL01 | Chỉ tài xế đang ở trạng thái sẵn sàng mới được xem xét để nhận chuyến. |
| BRL02 | Việc tìm tài xế dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| BRL03 | Hệ thống ưu tiên tài xế phù hợp và gần khách hàng. |
| BRL04 | Nếu tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác. |
| BRL05 | Nếu không tìm được tài xế, hệ thống phải thông báo cho khách hàng. |
| BRL06 | Sau khi chuyến hoàn thành, hệ thống xác định số tiền khách hàng phải trả. |
| BRL07 | Hệ thống không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán. |
| BRL08 | Khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| BRL09 | Các thao tác quản trị phải được kiểm soát quyền truy cập. |
| BRL10 | Các thao tác quan trọng phải được lưu vết. |

## 8.2. Exception Handling

| Mã | Ngoại lệ | Xử lý |
|---|---|---|
| EX01 | Tài xế từ chối chuyến | Hệ thống tiếp tục tìm tài xế khác. |
| EX02 | Tài xế không phản hồi | Hệ thống tiếp tục tìm tài xế khác theo thời gian phản hồi được doanh nghiệp xác định. |
| EX03 | Không tìm được tài xế | Hệ thống thông báo rõ ràng cho khách hàng. |
| EX04 | Thanh toán điện tử thất bại | Hệ thống thông báo cho khách hàng và cho phép xử lý lại theo chính sách doanh nghiệp. |
| EX05 | Lỗi thanh toán | Lỗi thanh toán không được làm toàn bộ hệ thống đặt xe ngừng hoạt động. |
| EX06 | Lỗi thông báo | Lỗi thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động. |
| EX07 | Mất kết nối mạng | Cách xử lý cụ thể cần được xác nhận với khách hàng. |

---

# BƯỚC 9. DATA MODELING VÀ XÁC ĐỊNH THỰC THỂ ERD

## 9.1. Các thực thể chính

- KHÁCH_HÀNG
- TÀI_XẾ
- PHƯƠNG_TIỆN
- LOẠI_XE
- CHUYẾN_ĐI
- THANH_TOÁN
- THÔNG_BÁO
- ĐÁNH_GIÁ

## 9.2. Quan hệ đề xuất

```text
KHÁCH_HÀNG 1 ----- N CHUYẾN_ĐI
TÀI_XẾ     1 ----- N CHUYẾN_ĐI
TÀI_XẾ     1 ----- N PHƯƠNG_TIỆN
LOẠI_XE    1 ----- N PHƯƠNG_TIỆN
CHUYẾN_ĐI  1 ----- N THANH_TOÁN
CHUYẾN_ĐI  1 ----- 0..1 ĐÁNH_GIÁ
KHÁCH_HÀNG 1 ----- N THÔNG_BÁO
TÀI_XẾ     1 ----- N THÔNG_BÁO
```

---

# BƯỚC 10. NON-FUNCTIONAL REQUIREMENTS

| Mã | Yêu cầu phi chức năng |
|---|---|
| NFR01 | Hệ thống phải hoạt động ổn định khi nhu cầu tăng cao. |
| NFR02 | Các thành phần của hệ thống phải có khả năng mở rộng độc lập khi tải tăng. |
| NFR03 | Lỗi tại chức năng thanh toán hoặc thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động. |
| NFR04 | Khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| NFR05 | Các thao tác quản trị phải được kiểm soát quyền truy cập. |
| NFR06 | Thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch phải được bảo vệ. |
| NFR07 | Các thao tác quan trọng phải được lưu vết để phục vụ kiểm tra khi có sự cố. |
| NFR08 | Các chức năng mới có thể được triển khai từng phần và hạn chế ảnh hưởng đến các chức năng đang hoạt động. |
| NFR09 | Hệ thống có khả năng bổ sung các loại dịch vụ, phương thức thanh toán và nhà cung cấp thông báo mới. |
| NFR10 | Hệ thống có kiến trúc đủ linh hoạt để thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng. |

---

# BƯỚC 11. XÁC ĐỊNH VÀ VẼ USE CASE

## 11.1. Actor

- Khách hàng
- Tài xế
- Nhân viên vận hành
- Ban giám đốc
- Nhà cung cấp thanh toán bên ngoài

## 11.2. Use Case của Khách hàng

- Đăng ký tài khoản
- Đăng nhập
- Cập nhật thông tin cá nhân
- Đặt xe
- Theo dõi chuyến đi
- Xem lịch sử chuyến đi
- Xem số tiền phải trả
- Thanh toán
- Đánh giá tài xế

## 11.3. Use Case của Tài xế

- Đăng ký tài khoản
- Cập nhật hồ sơ
- Cập nhật thông tin phương tiện
- Cập nhật trạng thái hoạt động
- Nhận thông báo chuyến
- Chấp nhận chuyến
- Từ chối chuyến
- Cập nhật trạng thái chuyến
- Cập nhật vị trí

## 11.4. Use Case của Nhân viên vận hành

- Quản lý khách hàng
- Quản lý tài xế
- Quản lý phương tiện
- Quản lý chuyến đi
- Theo dõi chuyến đang diễn ra
- Kiểm tra trạng thái tài xế
- Xử lý chuyến bị lỗi
- Tra cứu lịch sử giao dịch
- Quản lý quyền truy cập theo phạm vi được cấp

## 11.5. Use Case của Ban giám đốc

- Xem báo cáo hoạt động

## 11.6. Use Case của Nhà cung cấp thanh toán

- Xử lý thanh toán điện tử

## 11.7. Quan hệ Include đề xuất

- **Đặt xe** `<<include>>` **Tìm tài xế**.
- **Thanh toán** `<<include>>` **Xử lý thanh toán điện tử** khi khách hàng chọn phương thức điện tử.
- Các Use Case cần thông báo có thể `<<include>>` **Gửi thông báo**.

---

# BƯỚC 12. ĐẶC TẢ USE CASE

## UC01 – Đăng ký tài khoản

**Actor:** Khách hàng, Tài xế

**Mục tiêu:** Cho phép khách hàng hoặc tài xế tạo tài khoản.

**Tiền điều kiện:** Người dùng chưa có tài khoản.

**Hậu điều kiện:** Tài khoản được tạo thành công.

### Luồng chính

1. Người dùng chọn Đăng ký.
2. Hệ thống hiển thị biểu mẫu.
3. Người dùng nhập thông tin.
4. Người dùng xác nhận đăng ký.
5. Hệ thống kiểm tra thông tin.
6. Hệ thống tạo tài khoản.
7. Hệ thống thông báo đăng ký thành công.

### Luồng ngoại lệ

- Thông tin không hợp lệ → yêu cầu nhập lại.
- Tài khoản đã tồn tại → thông báo và yêu cầu sử dụng thông tin khác.
- Lỗi hệ thống → thông báo đăng ký thất bại.

## UC02 – Đăng nhập

**Actor:** Khách hàng, Tài xế, Nhân viên vận hành

**Mục tiêu:** Cho phép người dùng truy cập hệ thống theo quyền được cấp.

**Tiền điều kiện:** Người dùng đã có tài khoản.

**Hậu điều kiện:** Người dùng đăng nhập thành công.

### Luồng chính

1. Người dùng chọn Đăng nhập.
2. Hệ thống hiển thị màn hình đăng nhập.
3. Người dùng nhập thông tin.
4. Người dùng xác nhận.
5. Hệ thống kiểm tra thông tin.
6. Hệ thống xác thực tài khoản.
7. Hệ thống xác định quyền truy cập.
8. Hệ thống cho phép truy cập chức năng tương ứng.

### Luồng ngoại lệ

- Sai thông tin đăng nhập → thông báo lỗi.
- Tài khoản không hợp lệ hoặc không được phép truy cập → thông báo.
- Lỗi hệ thống → thông báo lỗi.

## UC03 – Đặt xe

**Actor:** Khách hàng

**Mục tiêu:** Cho phép khách hàng tạo yêu cầu đặt xe.

**Tiền điều kiện:** Khách hàng đã đăng nhập.

**Hậu điều kiện:** Yêu cầu đặt xe được tạo thành công và hệ thống bắt đầu tìm tài xế.

### Luồng chính

1. Khách hàng chọn Đặt xe.
2. Hệ thống hiển thị màn hình đặt xe.
3. Khách hàng nhập điểm đón.
4. Khách hàng nhập điểm đến.
5. Khách hàng chọn loại xe.
6. Khách hàng gửi yêu cầu.
7. Hệ thống kiểm tra thông tin.
8. Hệ thống tạo yêu cầu đặt xe.
9. Hệ thống bắt đầu tìm tài xế.

### Luồng ngoại lệ

- Thiếu điểm đón → yêu cầu nhập lại.
- Thiếu điểm đến → yêu cầu nhập lại.
- Chưa chọn loại xe → yêu cầu lựa chọn.
- Không tìm được tài xế → thông báo cho khách hàng.

## UC04 – Tìm tài xế

**Actor:** Hệ thống

**Mục tiêu:** Tìm tài xế phù hợp cho yêu cầu đặt xe.

**Tiền điều kiện:** Yêu cầu đặt xe đã được tạo.

**Hậu điều kiện:** Có tài xế nhận chuyến hoặc khách hàng được thông báo không tìm được tài xế.

### Luồng chính

1. Hệ thống nhận yêu cầu tìm tài xế.
2. Hệ thống xác định điểm đón và loại xe.
3. Hệ thống tìm tài xế đang sẵn sàng.
4. Hệ thống xác định tài xế phù hợp.
5. Hệ thống gửi yêu cầu đến tài xế.
6. Tài xế chấp nhận chuyến.
7. Hệ thống ghi nhận tài xế cho chuyến.
8. Hệ thống thông báo thông tin tài xế cho khách hàng.

### Luồng ngoại lệ

**E1. Tài xế từ chối**

1. Tài xế từ chối.
2. Hệ thống ghi nhận việc từ chối.
3. Hệ thống tiếp tục tìm tài xế khác.

**E2. Tài xế không phản hồi**

1. Hệ thống xác định tài xế không phản hồi theo thời gian được doanh nghiệp quy định.
2. Hệ thống tiếp tục tìm tài xế khác.

**E3. Không tìm được tài xế**

1. Hệ thống không tìm được tài xế phù hợp.
2. Hệ thống thông báo rõ ràng cho khách hàng.

## UC05 – Nhận chuyến

**Actor:** Tài xế

**Mục tiêu:** Cho phép tài xế nhận yêu cầu chuyến.

**Tiền điều kiện:** Tài xế đang ở trạng thái sẵn sàng và nhận được yêu cầu chuyến.

### Luồng chính

1. Tài xế nhận thông báo yêu cầu chuyến.
2. Hệ thống hiển thị thông tin chuyến.
3. Tài xế xem thông tin chuyến.
4. Tài xế chấp nhận chuyến.
5. Hệ thống ghi nhận việc chấp nhận.
6. Hệ thống thông báo cho khách hàng.

### Luồng ngoại lệ

- Tài xế không còn sẵn sàng → hệ thống không ghi nhận việc nhận chuyến.
- Chuyến đã được tài xế khác nhận → hệ thống thông báo chuyến không còn khả dụng.
- Hết thời gian phản hồi → xử lý theo thời gian được doanh nghiệp xác định.

## UC06 – Từ chối chuyến

**Actor:** Tài xế

**Tiền điều kiện:** Tài xế nhận được yêu cầu chuyến.

### Luồng chính

1. Tài xế xem yêu cầu.
2. Tài xế chọn Từ chối.
3. Hệ thống ghi nhận việc từ chối.
4. Hệ thống tiếp tục tìm tài xế khác.
5. Hệ thống cập nhật trạng thái cho khách hàng.

## UC07 – Theo dõi chuyến đi

**Actor:** Khách hàng

**Tiền điều kiện:** Khách hàng có chuyến xe.

### Luồng chính

1. Khách hàng mở thông tin chuyến.
2. Hệ thống hiển thị thông tin tài xế.
3. Hệ thống hiển thị trạng thái chuyến.
4. Hệ thống cập nhật trạng thái theo quá trình thực hiện.
5. Khách hàng theo dõi chuyến.
6. Khi chuyến hoàn thành, hệ thống hiển thị trạng thái hoàn thành.

### Luồng ngoại lệ

- Không cập nhật được vị trí → thông báo thông tin vị trí tạm thời không khả dụng.
- Chuyến bị lỗi hoặc thay đổi trạng thái → thông báo cho khách hàng.

## UC08 – Thanh toán

**Actor:** Khách hàng

**Tiền điều kiện:** Chuyến đã hoàn thành và số tiền phải trả đã được xác định.

### Luồng chính

1. Hệ thống hiển thị số tiền phải trả.
2. Khách hàng chọn phương thức thanh toán.
3. Nếu tiền mặt, hệ thống ghi nhận phương thức.
4. Nếu điện tử, hệ thống gửi yêu cầu đến nhà cung cấp thanh toán bên ngoài.
5. Hệ thống nhận kết quả.
6. Hệ thống ghi nhận kết quả thanh toán.
7. Hệ thống thông báo kết quả.

### Luồng ngoại lệ

**E1. Thanh toán điện tử thất bại**

1. Hệ thống nhận kết quả thất bại.
2. Hệ thống thông báo cho khách hàng.
3. Hệ thống cho phép xử lý lại theo chính sách doanh nghiệp.

## UC09 – Đánh giá tài xế

**Actor:** Khách hàng

**Tiền điều kiện:** Chuyến đã hoàn thành.

### Luồng chính

1. Khách hàng mở chuyến đã hoàn thành.
2. Hệ thống hiển thị chức năng đánh giá.
3. Khách hàng nhập đánh giá.
4. Khách hàng gửi đánh giá.
5. Hệ thống kiểm tra và lưu đánh giá.
6. Hệ thống thông báo kết quả.

## UC10 – Quản lý vận hành

**Actor:** Nhân viên vận hành

### Luồng chính

1. Nhân viên vận hành đăng nhập.
2. Nhân viên chọn chức năng quản lý.
3. Hệ thống hiển thị thông tin tương ứng.
4. Nhân viên xem, cập nhật hoặc xử lý theo quyền được cấp.
5. Hệ thống lưu thay đổi.
6. Hệ thống thông báo kết quả.

### Chức năng bao gồm

- Quản lý khách hàng.
- Quản lý tài xế.
- Quản lý phương tiện.
- Quản lý chuyến đi.
- Theo dõi chuyến đang diễn ra.
- Kiểm tra trạng thái tài xế.
- Xử lý chuyến bị lỗi.
- Tra cứu lịch sử giao dịch.

---

# BƯỚC 13. ACCEPTANCE CRITERIA

| Mã | Chức năng | Tiêu chí chấp nhận |
|---|---|---|
| AC01 | Đăng ký | Người dùng có thể tạo tài khoản với thông tin hợp lệ. |
| AC02 | Đăng nhập | Người dùng có tài khoản hợp lệ có thể đăng nhập và truy cập chức năng theo quyền. |
| AC03 | Đặt xe | Khách hàng có thể nhập điểm đón, điểm đến, chọn loại xe và gửi yêu cầu. |
| AC04 | Tìm tài xế | Hệ thống tìm tài xế dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| AC05 | Phân công tài xế | Khi tài xế chấp nhận, hệ thống ghi nhận tài xế cho chuyến. |
| AC06 | Từ chối chuyến | Khi tài xế từ chối, hệ thống tiếp tục tìm tài xế khác. |
| AC07 | Không phản hồi | Khi tài xế không phản hồi trong thời gian được doanh nghiệp quy định, hệ thống tiếp tục tìm tài xế khác. |
| AC08 | Không tìm được tài xế | Hệ thống thông báo rõ ràng cho khách hàng. |
| AC09 | Theo dõi chuyến | Khách hàng xem được trạng thái chuyến và thông tin tài xế. |
| AC10 | Cập nhật chuyến | Tài xế có thể cập nhật trạng thái chuyến. |
| AC11 | Cập nhật vị trí | Hệ thống ghi nhận vị trí tài xế để hỗ trợ tìm tài xế gần khách hàng và dự kiến thời gian đến. |
| AC12 | Tính cước | Sau khi chuyến hoàn thành, hệ thống xác định số tiền khách hàng phải trả. |
| AC13 | Thanh toán | Hệ thống hỗ trợ tiền mặt và thanh toán điện tử. |
| AC14 | Thanh toán thất bại | Khách hàng được thông báo và có thể xử lý lại theo chính sách doanh nghiệp. |
| AC15 | Thông báo | Khách hàng và tài xế nhận được thông báo về các sự kiện liên quan. |
| AC16 | Đánh giá | Khách hàng có thể đánh giá tài xế sau khi chuyến hoàn thành. |
| AC17 | Quản lý vận hành | Nhân viên vận hành có thể thực hiện các chức năng quản lý theo quyền được cấp. |
| AC18 | Báo cáo | Ban giám đốc có thể xem báo cáo hoạt động được hệ thống cung cấp. |
| AC19 | Phân quyền | Các thao tác quản trị được kiểm soát theo quyền truy cập. |
| AC20 | Bảo mật | Dữ liệu cá nhân, phương tiện, vị trí và giao dịch được bảo vệ. |
| AC21 | Audit | Các thao tác quan trọng được lưu vết. |

---

# BƯỚC 14. MA TRẬN TRUY XUẤT NGUỒN GỐC YÊU CẦU (RTM)

## 14.1. Quy ước mã

| Ký hiệu | Ý nghĩa |
|---|---|
| BG | Business Goal – Mục tiêu nghiệp vụ |
| BR | Business Requirement – Yêu cầu nghiệp vụ |
| FRD | Functional Requirement Detail – Phân rã yêu cầu chức năng |
| UC | Use Case – Ca sử dụng |
| AC | Acceptance Criteria – Tiêu chí chấp nhận |
| TC | Test Case – Ca kiểm thử |

## 14.2. RTM

| BG | BR | FRD | UC | AC |
|---|---|---|---|---|
| BG01 | BR01 | FRD01 | UC03 – Đặt xe | AC03 |
| BG01 | BR02 | FRD02–FRD05 | UC04 – Tìm tài xế; UC05 – Nhận chuyến; UC06 – Từ chối chuyến | AC04–AC08 |
| BG02 | BR03 | FRD06–FRD08 | UC07 – Theo dõi chuyến đi | AC09–AC11 |
| BG03 | BR05 | FRD07–FRD08 | UC05 – Nhận chuyến; UC06 – Từ chối chuyến | AC05–AC07 |
| BG04 | BR04–BR06, BR11 | FRD13–FRD18 | UC10 – Quản lý vận hành | AC17 |
| BG05 | BR07–BR08 | FRD09–FRD11 | UC08 – Thanh toán | AC12–AC14 |
| BG05 | BR09 | FRD12 | Gửi thông báo | AC15 |
| BG02 | BR10 | — | UC09 – Đánh giá tài xế | AC16 |
| BG06 | BR12 | FRD20 | Xem báo cáo | AC18 |
| BG07 | BR13 | FRD19 | Phân quyền | AC19–AC20 |
| BG07 | BR14 | — | Khả năng mở rộng | — |

---

# OPEN ISSUES CẦN XÁC NHẬN TRƯỚC KHI PHÁT TRIỂN

| Mã | Nội dung cần xác nhận |
|---|---|
| OI01 | Cách tính cước cụ thể |
| OI02 | Tiêu chí ưu tiên tài xế |
| OI03 | Thời gian tài xế phải phản hồi |
| OI04 | Chính sách hủy chuyến |
| OI05 | Cách xử lý khi mất kết nối mạng |
| OI06 | Thời gian lưu trữ dữ liệu |

---


