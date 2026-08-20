Bước 1 Đọc và phân tích yêu cầu sơ khởi của khách hàng sơ khởi của giai đoạn 1 (ngữ cảnh của nghiệp vu, vấn đề của nghiệp vụ là gì)
1. Ngữ cảnh nghiệp vụ
Công ty ABC cung cấp dịch vụ đặt xe trực tuyến.
Hiện khách hàng đặt xe qua tổng đài hoặc ứng dụng đơn giản.
Có 3 nhóm người dùng chính: khách hàng, tài xế, nhân viên vận hành.
Doanh nghiệp muốn xây dựng CAB System mới để tự động hóa và quản lý toàn bộ quy trình đặt xe.
2. Vấn đề nghiệp vụ hiện tại
Phân công tài xế còn thủ công → chậm và khó mở rộng.
Khách hàng khó theo dõi trạng thái chuyến.
Thông tin thanh toán chưa được quản lý tập trung.
Nhân viên vận hành khó quản lý và xử lý sự cố.
Hệ thống hiện tại khó mở rộng khi số lượng khách hàng/tài xế tăng.
Thông báo và các chức năng chưa đủ linh hoạt để mở rộng.
3. Nhu cầu của khách hàng
Tự động tìm và phân công tài xế.
Cho phép khách hàng đặt xe và theo dõi chuyến.
Hỗ trợ tính cước, thanh toán, thông báo và đánh giá.
Hỗ trợ nhân viên quản lý khách hàng, tài xế, chuyến đi, giao dịch.
Có báo cáo cho ban lãnh đạo.
Hệ thống ổn định, bảo mật và dễ mở rộng.
4. Vấn đề cần làm rõ
Cách tính cước.
Tiêu chí ưu tiên tài xế.
Thời gian tài xế phản hồi.
Chính sách hủy chuyến.
Xử lý mất kết nối.
Thời gian lưu trữ dữ liệu.
Bước 2
2.1 Lập bảng 2 cột  cot 1(Stakeholder), cột thứ 2 vai trò  
| **Stakeholder**                    | **Vai trò**                                                                           |
| ---------------------------------- | -----------------------------------------------------------------------------------   |
| - Ban giám đốc Công ty ABC         | - Đưa ra mục tiêu, yêu cầu kinh doanh và theo dõi hiệu quả hoạt động của hệ thống.    |
| - Khách hàng                       | - Đặt xe, theo dõi chuyến đi, thanh toán, xem lịch sử và đánh giá tài xế.             |
| - Tài xế                           | - Nhận/từ chối chuyến, thực hiện chuyến, cập nhật trạng thái và vị trí.               |
| - Nhân viên vận hành               | - Quản lý khách hàng, tài xế, phương tiện, chuyến đi; theo dõi và hỗ trợ xử lý sự cố. |
| - Nhà cung cấp thanh toán          | - Xử lý các giao dịch thanh toán điện tử cho hệ thống.                                |
| - Nhà cung cấp dịch vụ thông báo   | - Cung cấp dịch vụ gửi thông báo đến khách hàng và tài xế.                            |
2.2 Lập vẽ ma trận Stakeholder matrix  tầm ảnh hưởng vai trò của Stakeholder trong hệ thống
https://github.com/user-attachments/assets/13dfa22f-78e1-47a3-b97b-1142e2765d0f
quadrantChart
    title Ma trận Stakeholder: Tầm ảnh hưởng và mức độ quan tâm
    x-axis Mức độ quan tâm thấp --> Mức độ quan tâm cao
    y-axis Tầm ảnh hưởng thấp --> Tầm ảnh hưởng cao
    quadrant-1 Quản lý chặt chẽ
    quadrant-2 Duy trì hài lòng
    quadrant-3 Theo dõi
    quadrant-4 Giữ liên lạc

    Ban giám đốc Công ty ABC: [0.72, 0.95]
    Khách hàng: [0.90, 0.55]
    Tài xế: [0.85, 0.48]
    Nhân viên vận hành: [0.88, 0.78]
    Nhà cung cấp thanh toán: [0.42, 0.68]
    Nhà cung cấp dịch vụ thông báo: [0.35, 0.52]
Bước 3 Mục đích của nhiệm vụ (Business Goal)
- **BG01**: Tự động hóa quy trình đặt xe và tìm kiếm, phân công tài xế để giảm thời gian xử lý và nâng cao hiệu quả vận hành.
- **BG02**: Cung cấp cho khách hàng trải nghiệm đặt xe, theo dõi chuyến đi, thanh toán và đánh giá tài xế một cách thuận tiện, minh bạch và nhanh chóng.
- **BG03**: Hỗ trợ tài xế nhận chuyến, cập nhật trạng thái và vị trí, đồng thời nâng cao độ tin cậy trong quá trình thực hiện chuyến đi.
- **BG04**: Giúp nhân viên vận hành quản lý khách hàng, tài xế, phương tiện, chuyến đi và xử lý sự cố kịp thời trên hệ thống.
- **BG05**: Tích hợp thanh toán điện tử và dịch vụ thông báo để đảm bảo giao dịch an toàn, minh bạch và thông tin được truyền đến đúng đối tượng nhanh chóng.
- **BG06**: Cung cấp báo cáo, thống kê và số liệu theo thời gian cho Ban giám đốc để theo dõi hiệu quả hoạt động doanh nghiệp.
- **BG07**: Xây dựng hệ thống ổn định, bảo mật, dễ mở rộng và phù hợp với tăng trưởng số lượng khách hàng, tài xế và phương tiện trong tương lai.
Mục tiêu tổng thể của nhiệm vụ là xây dựng CAB System để tự động hóa toàn bộ quy trình đặt xe, nâng cao chất lượng dịch vụ, tăng hiệu quả quản lý và đáp ứng nhu cầu phát triển dài hạn của Công ty ABC.
4. XÁC ĐỊNH PHẠM VI YÊU CẦU (SCOPE)
4.1. Phạm vi hệ thống (In Scope)
CAB System tập trung hỗ trợ toàn bộ quy trình đặt xe từ khi khách hàng tạo yêu cầu đến khi chuyến đi hoàn thành, thanh toán và đánh giá.
Các module chính của hệ thống:
Mã	Module	Nội dung chính
SC01	Quản lý tài khoản	Đăng ký, đăng nhập, cập nhật thông tin cá nhân
SC02	Quản lý khách hàng	Quản lý thông tin khách hàng và lịch sử chuyến
SC03	Quản lý tài xế	Quản lý hồ sơ và trạng thái hoạt động của tài xế
SC04	Quản lý phương tiện	Quản lý thông tin và loại xe
SC05	Đặt xe	Nhập điểm đón, điểm đến và lựa chọn loại xe
SC06	Tìm tài xế	Tìm tài xế phù hợp dựa trên vị trí và trạng thái
SC07	Phân công tài xế	Gửi yêu cầu, tài xế nhận/từ chối và tìm tài xế khác
SC08	Quản lý chuyến đi	Theo dõi và cập nhật trạng thái chuyến
SC09	Tính cước	Xác định số tiền khách hàng phải trả
SC10	Thanh toán	Hỗ trợ thanh toán tiền mặt và thanh toán điện tử
SC11	Thông báo	Gửi thông báo về đặt xe, chuyến đi và thanh toán
SC12	Đánh giá	Khách hàng đánh giá tài xế sau chuyến
SC13	Quản lý vận hành	Theo dõi khách hàng, tài xế, phương tiện và chuyến đi
SC14	Báo cáo	Thống kê số chuyến, doanh thu, tỷ lệ hoàn thành và hủy
SC15	Phân quyền & Audit Log	Kiểm soát quyền truy cập và lưu vết thao tác quan trọng
4.2. MVP – Chức năng bắt buộc phải thực hiện
Do thời gian xây dựng và triển khai sản phẩm là 7 tuần, phiên bản MVP tập trung vào các chức năng cốt lõi của quy trình đặt xe.
Mã	Module MVP	Chức năng chính	Mức độ ưu tiên
MVP01	Tài khoản	Đăng ký, đăng nhập	Cao
MVP02	Khách hàng	Quản lý thông tin khách hàng	Cao
MVP03	Tài xế	Quản lý hồ sơ và trạng thái sẵn sàng	Cao
MVP04	Phương tiện	Quản lý thông tin xe và loại xe	Cao
MVP05	Đặt xe	Nhập điểm đón, điểm đến, chọn loại xe	Cao
MVP06	Tìm tài xế	Tìm tài xế phù hợp và gần khách hàng	Cao
MVP07	Phân công tài xế	Nhận/từ chối chuyến và tìm tài xế tiếp theo	Cao
MVP08	Quản lý chuyến	Cập nhật trạng thái chuyến	Cao
MVP09	Tính cước	Xác định số tiền phải trả	Cao
MVP10	Thanh toán	Thanh toán tiền mặt và điện tử cơ bản	Cao
MVP11	Thông báo	Thông báo các trạng thái quan trọng	Trung bình
MVP12	Đánh giá	Đánh giá tài xế sau khi hoàn thành chuyến	Trung bình
MVP13	Vận hành	Nhân viên theo dõi và hỗ trợ chuyến	Cao
MVP14	Phân quyền	Phân quyền cơ bản cho người dùng	Cao
Quy trình MVP cốt lõi
Khách hàng đăng nhập
        ↓
Tạo yêu cầu đặt xe
        ↓
Hệ thống tìm tài xế
        ↓
Tài xế nhận chuyến
        ↓
Tài xế thực hiện chuyến
        ↓
Hoàn thành chuyến
        ↓
Tính cước
        ↓
Thanh toán
        ↓
Khách hàng đánh giá
4.3. Phạm vi mở rộng (Future Scope)
Các chức năng sau có thể được phát triển trong các phiên bản tiếp theo:
Thuật toán phân công tài xế nâng cao.
Dự đoán nhu cầu đặt xe.
Giá cước linh hoạt theo thời điểm.
Chương trình khuyến mãi.
Hệ thống tích điểm và khách hàng thân thiết.
Ví điện tử riêng của CAB.
Tích hợp nhiều nhà cung cấp thanh toán.
Tích hợp nhiều nhà cung cấp thông báo.
Báo cáo và phân tích dữ liệu nâng cao.
Thêm các loại dịch vụ CAB mới.
Các chức năng quản lý và phân tích nâng cao cho doanh nghiệp.
4.4. Ngoài phạm vi (Out of Scope)
Các nội dung sau không thuộc phạm vi triển khai của phiên bản hiện tại:
Tự xây dựng hệ thống thanh toán ngân hàng.
Lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.
Tự xây dựng hệ thống bản đồ/GPS.
Tự xây dựng hạ tầng SMS, Email hoặc Push Notification.
Hệ thống AI dự đoán nhu cầu.
Hệ thống khuyến mãi và Loyalty nâng cao.
Ví điện tử riêng của CAB.
Các dịch vụ vận tải khác chưa được khách hàng xác nhận.
Các chức năng chưa có yêu cầu hoặc chưa được khách hàng thống nhất.

Bước 5: Xác định Business Requirement (BR)
| **Mã**   | **Tên**                 | **Diễn giải**                                                                                                                                        |
| -------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **BR01** | Đặt chuyến              | Hệ thống hỗ trợ khách hàng tạo yêu cầu đặt xe để sử dụng dịch vụ CAB.                                                                                |
| **BR02** | Tìm và phân công tài xế | Hệ thống hỗ trợ doanh nghiệp tự động tìm và phân công tài xế phù hợp cho chuyến xe.                                                                  |
| **BR03** | Quản lý chuyến đi       | Hệ thống hỗ trợ quản lý và theo dõi toàn bộ quá trình của một chuyến xe.                                                                             |
| **BR04** | Quản lý khách hàng      | Hệ thống hỗ trợ quản lý thông tin và lịch sử sử dụng dịch vụ của khách hàng.                                                                         |
| **BR05** | Quản lý tài xế          | Hệ thống hỗ trợ quản lý thông tin, trạng thái hoạt động và quá trình thực hiện chuyến của tài xế.                                                    |
| **BR06** | Quản lý phương tiện     | Hệ thống hỗ trợ quản lý thông tin phương tiện phục vụ hoạt động đặt xe.                                                                              |
| **BR07** | Tính cước               | Hệ thống hỗ trợ xác định số tiền khách hàng cần thanh toán cho chuyến xe.                                                                            |
| **BR08** | Thanh toán              | Hệ thống hỗ trợ khách hàng thanh toán chi phí chuyến đi bằng tiền mặt hoặc phương thức điện tử.                                                      |
| **BR09** | Thông báo               | Hệ thống hỗ trợ thông báo kịp thời các thông tin quan trọng liên quan đến chuyến xe cho khách hàng và tài xế.                                        |
| **BR10** | Đánh giá chuyến đi      | Hệ thống hỗ trợ khách hàng đánh giá chất lượng dịch vụ và tài xế sau khi hoàn thành chuyến.                                                          |
| **BR11** | Quản lý vận hành        | Hệ thống hỗ trợ nhân viên vận hành giám sát, quản lý và xử lý các vấn đề liên quan đến hoạt động đặt xe.                                             |
| **BR12** | Báo cáo hoạt động       | Hệ thống cung cấp thông tin và báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động.                             |
| **BR13** | Bảo mật và phân quyền   | Hệ thống đảm bảo người dùng chỉ được truy cập và thực hiện các chức năng phù hợp với quyền hạn.                                                      |
| **BR14** | Khả năng mở rộng        | Hệ thống có khả năng mở rộng để đáp ứng số lượng người dùng tăng và bổ sung các dịch vụ, phương thức thanh toán hoặc kênh thông báo trong tương lai. |
# 6. XÂY DỰNG BUSINESS PROCESS
## 6.1. Quy trình nghiệp vụ đặt xe
Quy trình nghiệp vụ chính của hệ thống được xây dựng theo chuỗi sau:
1. **Khách hàng đăng nhập vào hệ thống**
   - Khách hàng đăng nhập hoặc đăng ký tài khoản.
   - Hệ thống xác thực thông tin người dùng.
2. **Khách hàng đặt chuyến**
   - Khách hàng nhập điểm đón, điểm đến, thời gian, loại xe và yêu cầu đặc biệt.
   - Hệ thống lưu thông tin yêu cầu chuyến và tạo một đơn đặt xe mới.
3. **Hệ thống tìm tài xế phù hợp**
   - Hệ thống kiểm tra danh sách tài xế đang sẵn sàng.
   - Dựa trên vị trí, loại xe, thời gian và mức độ ưu tiên, hệ thống đề xuất hoặc tự động phân công tài xế phù hợp.
4. **Tài xế nhận chuyến**
   - Tài xế nhận hoặc từ chối chuyến.
   - Nếu nhận chuyến, hệ thống cập nhật trạng thái chuyến sang "Đã chấp nhận".
5. **Tài xế di chuyển đến điểm đón**
   - Tài xế cập nhật vị trí thực tế.
   - Khách hàng nhận được thông tin tài xế đang đến.
6. **Thực hiện chuyến đi**
   - Khi bắt đầu chuyến, tài xế cập nhật trạng thái "Đang đi".
   - Hệ thống ghi nhận thời gian bắt đầu, điểm đón, điểm đến và trạng thái chuyến đi.
7. **Kết thúc chuyến đi**
   - Tài xế cập nhật trạng thái "Hoàn thành".
   - Hệ thống tính cước theo quy tắc định giá đã được thiết lập.
8. **Thanh toán và đánh giá**
   - Khách hàng thanh toán trực tuyến hoặc thanh toán theo phương thức đã chọn.
   - Khách hàng có thể đánh giá tài xế và phản hồi dịch vụ.
9. **Nhân viên vận hành theo dõi và xử lý sự cố**
   - Nhân viên vận hành xem tình trạng các chuyến đi đang diễn ra.
   - Hệ thống hỗ trợ xử lý các sự cố như hủy chuyến, chậm trễ, thanh toán lỗi hoặc tài xế không phản hồi.
10. **Báo cáo, thống kê và quản trị**
    - Ban giám đốc và nhân viên vận hành xem báo cáo doanh thu, số lượng chuyến, hiệu suất tài xế và tỷ lệ hoàn thành.
Bước 7: Thiết kế phân rã yêu cầu nghiệp vụ (FRD)
## 7.1 Phân rã yêu cầu nghiệp vụ cho chức năng đặt xe
| **Mã** | **Tên yêu cầu** | **Diễn giải** |
| ------ | --------------- | ------------ |
| **FRD01** | Tìm tài xế | Hệ thống phải tìm danh sách tài xế đang sẵn sàng trong khu vực của điểm đón để phục vụ yêu cầu đặt xe. |
| **FRD02** | Chọn tài xế online | Khách hàng có thể chọn tài xế đang online hoặc hệ thống tự động chọn tài xế phù hợp nhất trong danh sách khớp điều kiện. |
| **FRD03** | Chọn loại xe | Khách hàng cần lựa chọn loại xe phù hợp như xe 4 chỗ, 7 chỗ, xe VIP hoặc xe tải theo nhu cầu chuyến đi. |
| **FRD04** | Ưu tiên tài xế có đánh giá cao | Khi có nhiều tài xế phù hợp, hệ thống ưu tiên tài xế có đánh giá cao, phản hồi nhanh và khoảng cách gần hơn. |
| **FRD05** | Xác nhận chuyến đi | Sau khi tài xế nhận chuyến, hệ thống phải gửi xác nhận cho khách hàng và cập nhật trạng thái chuyến thành "Đã xác nhận". |
| **FRD06** | Cập nhật vị trí tài xế | Hệ thống phải hiển thị vị trí hiện tại của tài xế để khách hàng theo dõi thời gian đến điểm đón. |
| **FRD07** | Tính cước chuyến đi | Hệ thống phải tính cước theo khoảng cách, thời gian, loại xe và các phụ phí nếu có. |
| **FRD08** | Thanh toán sau chuyến | Sau khi hoàn thành chuyến, hệ thống phải cho phép thanh toán và lưu giao dịch thanh toán vào lịch sử. |
| **FRD09** | Hủy hoặc đổi chuyến | Khách hàng hoặc tài xế có thể hủy/đổi chuyến trong các điều kiện hợp lệ và hệ thống phải cập nhật trạng thái phù hợp. |
| **FRD10** | Theo dõi và xử lý sự cố | Hệ thống phải hỗ trợ nhân viên vận hành theo dõi sự cố và thực hiện xử lý khi tài xế không phản hồi, chậm trễ hoặc thanh toán lỗi. |
## 7.2 Mô tả phân rã yêu cầu nghiệp vụ
- **FRD01 – Tìm tài xế**: Là chức năng nền tảng của hệ thống, nhằm rà soát các tài xế đang ở trạng thái sẵn sàng và nằm trong phạm vi địa lý của khách hàng.
- **FRD02 – Chọn tài xế online**: Cho phép khách hàng hoặc hệ thống chọn tài xế đang online và có thể nhận chuyến ngay lập tức.
- **FRD03 – Chọn loại xe**: Người dùng lựa chọn loại xe phù hợp với số lượng hành khách và mức độ phục vụ mong muốn.
- **FRD04 – Ưu tiên tài xế có đánh giá cao**: Hệ thống áp dụng tiêu chí ưu tiên như mức đánh giá, khoảng cách, thời gian phản hồi và hiệu suất để lựa chọn tài xế tốt nhất.
Như vậy, phân rã yêu cầu nghiệp vụ ở bước này tập trung vào các chức năng quan trọng trong quá trình đặt xe và lựa chọn tài xế, vì đây là phần lõi của hệ thống CAB System.
Bước 8: Business Rule và Exception Handling
## 8.1 Business Rules (Quy tắc nghiệp vụ)
| **Mã** | **Tên quy tắc** | **Luật nghiệp vụ** |
| ------ | --------------- | ----------------- |
| **BRL01** | Tài xế chỉ nhận chuyến khi sẵn sàng | Chỉ những tài xế có trạng thái "Sẵn sàng" mới được phép nhận hoặc chấp nhận chuyến. |
| **BRL02** | Khách hàng phải nhập thông tin bắt buộc | Khi đặt chuyến, khách hàng bắt buộc phải nhập điểm đón, điểm đến, thời gian đặt xe và loại xe. |
| **BRL03** | Chuyến không hợp lệ nếu chưa có tài xế | Nếu hệ thống không tìm được tài xế phù hợp trong thời gian quy định, chuyến được đánh dấu là "Chưa có tài xế" và đưa về trạng thái chờ hoặc hủy. |
| **BRL04** | Tài xế chỉ được phép nhận 1 chuyến cùng lúc | Một tài xế chỉ được nhận một chuyến tại một thời điểm, không được đồng thời nhận nhiều yêu cầu. |
| **BRL05** | Tài xế có thể từ chối chuyến | Nếu tài xế từ chối chuyến, hệ thống tự động tìm tài xế khác phù hợp với cùng tiêu chí. |
| **BRL06** | Chuyến bị hủy nếu quá thời hạn xác nhận | Nếu tài xế không phản hồi trong thời gian quy định, hệ thống sẽ huỷ lời mời và chuyển sang tài xế khác. |
| **BRL07** | Tính cước sau khi chuyến kết thúc | Cước được tính dựa trên quãng đường, thời gian, loại xe và phụ phí áp dụng. |
| **BRL08** | Thanh toán bắt buộc trước khi hoàn tất | Khách hàng cần hoàn tất thanh toán theo phương thức đã chọn trước khi tài xế được xác nhận hoàn tất chuyến. |
| **BRL09** | Khách hàng có quyền hủy đúng quy định | Khách hàng có thể hủy chuyến trong thời gian hợp lệ; nếu quá thời hạn, có thể áp dụng phí hủy. |
| **BRL10** | Nhân viên vận hành can thiệp khi có sự cố | Khi xảy ra lỗi như tài xế mất kết nối, khách hàng không xác nhận hoặc sai thông tin, nhân viên vận hành có quyền xử lý thủ công. |

## 8.2 Exception Handling (Xử lý ngoại lệ)

| **Mã** | **Tên ngoại lệ** | **Mô tả** | **Xử lý** |
| ------ | --------------- | -------- | -------- |
| **EX01** | Khách hàng chờ tìm tài xế quá lâu | Hệ thống không tìm được tài xế phù hợp trong thời gian tiêu chuẩn. | Hệ thống thông báo cho khách hàng rằng chưa tìm được tài xế, yêu cầu thử lại hoặc tự động tìm tài xế khác; nếu vẫn không có, chuyến bị hủy hoặc chuyển sang trạng thái chờ. |
| **EX02** | Tài xế không phản hồi | Tài xế không chấp nhận hoặc không trả lời yêu cầu trong thời gian quy định. | Hệ thống tự động chuyển cho tài xế khác trong danh sách phù hợp. |
| **EX03** | Tài xế từ chối chuyến | Tài xế bấm từ chối sau khi nhận được lời mời. | Hệ thống gọi lại quy trình tìm tài xế mới và gửi yêu cầu đến tài xế kế tiếp. |
| **EX04** | Tài xế mất kết nối | Tài xế mất tín hiệu hoặc không cập nhật vị trí trong quá trình thực hiện. | Hệ thống gửi cảnh báo cho nhân viên vận hành; nếu không khôi phục trong thời gian quy định, chuyến có thể chuyển sang tình huống khẩn cấp và điều phối lại. |
| **EX05** | Khách hàng hủy chuyến | Khách hàng hủy chuyến sau khi tài xế đã nhận. | Nếu trong thời gian cho phép, hệ thống cập nhật trạng thái hủy; nếu quá thời hạn, áp dụng phí hủy theo quy định. |
| **EX06** | Thanh toán thất bại | Khách hàng thanh toán không thành công hoặc thẻ bị từ chối. | Hệ thống giữ trạng thái "Chờ thanh toán", thông báo lỗi và yêu cầu thanh toán lại; nếu không thanh toán trong thời gian quy định, đơn đặt xe bị hủy. |
| **EX07** | Lỗi thông tin địa điểm | Khách hàng nhập điểm đón hoặc điểm đến không hợp lệ hoặc trùng nhau. | Hệ thống cảnh báo và yêu cầu nhập lại thông tin chính xác. |
| **EX08** | Tài xế không đủ điều kiện | Tài xế đang offline, không đúng loại xe hoặc không nhận chuyến theo vùng phục vụ. | Hệ thống loại bỏ tài xế khỏi danh sách đề xuất và tìm tài xế khác. |

## 8.3 Quy trình xử lý ngoại lệ cơ bản
1. Hệ thống phát hiện tình huống ngoại lệ.
2. Xác định nguyên nhân và mức độ ảnh hưởng.
3. Nếu có thể xử lý tự động, hệ thống thực hiện lại quy trình tìm tài xế hoặc thông báo lại cho người dùng.
4. Nếu không xử lý được tự động, nhân viên vận hành can thiệp thủ công.
5. Hệ thống ghi nhận lịch sử xử lý sự cố và cập nhật trạng thái chuyến phù hợp.
## 8.4 Ví dụ xử lý ngoại lệ điển hình
- **Ví dụ 1**: Chỉ những tài xế ở trạng thái "Sẵn sàng" mới nhận chuyến. Nếu một tài xế đang "Bận", "Ngoại tuyến" hoặc "Không nhận chuyến", hệ thống không đưa vào danh sách tìm tài xế.
- **Ví dụ 2**: Khách hàng tạo chuyến nhưng chờ tìm tài xế quá lâu. Nếu sau 60 giây hệ thống vẫn không tìm được tài xế phù hợp, hệ thống sẽ gửi thông báo "Chưa có tài xế phù hợp" và cho khách hàng chọn thử lại hoặc hủy chuyến.
- **Ví dụ 3**: Tài xế nhận được lời mời nhưng không bấm chấp nhận trong thời gian quy định. Hệ thống tự động hủy lời mời, chuyển sang tài xế khác, và gửi thông báo cập nhật cho khách hàng.
- **Ví dụ 4**: Tài xế từ chối chuyến sau khi chấp nhận. Hệ thống lập tức tìm tài xế khác thay thế và không để chuyến bị treo.
Bước 9: Xây dựng Data Modeling và xác định thực thể ERD##
 erDiagram
    KHACH_HANG ||--o{ CHUYEN_DI : dat
    TAI_XE ||--o{ CHUYEN_DI : thuc_hien
    TAI_XE ||--|| PHUONG_TIEN : su_dung
    LOAI_XE ||--o{ PHUONG_TIEN : thuoc
    CHUYEN_DI ||--|| THANH_TOAN : co
    CHUYEN_DI ||--o| DANH_GIA : duoc_danh_gia
    KHACH_HANG ||--o{ THONG_BAO : nhan
    TAI_XE ||--o{ THONG_BAO : nhan

    KHACH_HANG {
        int MaKH PK
        string HoTen
        string SoDienThoai
        string Email
        string MatKhau
        string DiaChi
    }

    TAI_XE {
        int MaTX PK
        string HoTen
        string SoDienThoai
        string MatKhau
        string TrangThai
        string ViTriHienTai
    }

    PHUONG_TIEN {
        int MaPT PK
        string BienSo
        string MauXe
        int MaTX FK
        int MaLoaiXe FK
    }

    LOAI_XE {
        int MaLoaiXe PK
        string TenLoaiXe
        string MoTa
    }

    CHUYEN_DI {
        int MaChuyen PK
        int MaKH FK
        int MaTX FK
        string DiemDon
        string DiemDen
        datetime ThoiGianDat
        datetime ThoiGianDon
        string TrangThai
        decimal SoTien
    }

    THANH_TOAN {
        int MaTT PK
        int MaChuyen FK
        string PhuongThuc
        decimal SoTien
        string TrangThai
        datetime ThoiGianThanhToan
    }

    DANH_GIA {
        int MaDG PK
        int MaChuyen FK
        int MaKH FK
        int MaTX FK
        int SoSao
        string NoiDung
    }

    THONG_BAO {
        int MaTB PK
        string NoiDung
        datetime ThoiGian
        string TrangThai
        int MaKH FK
        int MaTX FK
    }

## Bước 10. Non-Functional Requirements
Non-Functional Requirements (NFR) là các yêu cầu quy định về chất lượng, hiệu năng, bảo mật, khả năng sử dụng và độ tin cậy của hệ thống.
### NFR01 – Hiệu năng
Hệ thống phải phản hồi các thao tác thông thường của người dùng trong thời gian tối đa 3 giây trong điều kiện hệ thống hoạt động bình thường.
### NFR02 – Thời gian tìm tài xế
Hệ thống phải thực hiện quá trình tìm kiếm và đề xuất tài xế trong thời gian hợp lý, đồng thời phải có cơ chế giới hạn thời gian tìm kiếm.
### NFR03 – Khả năng chịu tải
Hệ thống phải có khả năng phục vụ nhiều khách hàng và tài xế sử dụng đồng thời mà không làm ảnh hưởng nghiêm trọng đến hiệu năng.
### NFR04 – Tính sẵn sàng
Hệ thống phải hoạt động ổn định và có khả năng phục vụ người dùng liên tục, đặc biệt trong thời gian cao điểm.
### NFR05 – Độ tin cậy
Hệ thống phải đảm bảo dữ liệu chuyến xe, thông tin khách hàng và thông tin tài xế được lưu trữ chính xác, hạn chế mất mát hoặc sai lệch dữ liệu.
### NFR06 – Bảo mật
Hệ thống phải bảo vệ thông tin tài khoản, thông tin cá nhân và thông tin liên quan đến chuyến xe của người dùng.
### NFR07 – Xác thực người dùng
Hệ thống phải yêu cầu người dùng đăng nhập và xác thực trước khi sử dụng các chức năng yêu cầu quyền truy cập.
### NFR08 – Phân quyền
Hệ thống phải phân biệt quyền truy cập giữa các vai trò như:
- Khách hàng
- Tài xế
- Quản trị viên
Mỗi vai trò chỉ được phép sử dụng các chức năng phù hợp với quyền của mình.
### NFR09 – Khả năng sử dụng
Giao diện hệ thống phải đơn giản, dễ hiểu và dễ sử dụng đối với khách hàng, tài xế và quản trị viên.
### NFR10 – Khả năng tương thích
Hệ thống phải có khả năng hoạt động trên các trình duyệt web phổ biến và các thiết bị được hệ thống hỗ trợ.
### NFR11 – Khả năng mở rộng
Hệ thống phải được thiết kế để có thể mở rộng thêm số lượng người dùng, tài xế, loại xe và các chức năng mới trong tương lai.
### NFR12 – Khả năng bảo trì
Hệ thống phải được thiết kế theo cấu trúc rõ ràng, dễ kiểm tra, sửa lỗi và nâng cấp.
### NFR13 – Tính nhất quán dữ liệu
Hệ thống phải đảm bảo trạng thái của chuyến xe và trạng thái tài xế được cập nhật nhất quán.
Ví dụ: khi tài xế đã nhận chuyến, hệ thống phải cập nhật trạng thái tài xế thành "Đang nhận chuyến" và không cho phép tài xế đó nhận thêm chuyến khác.
### NFR14 – Khôi phục lỗi
Khi xảy ra lỗi hệ thống hoặc mất kết nối tạm thời, hệ thống phải có khả năng xử lý và khôi phục trạng thái dữ liệu hợp lệ, hạn chế ảnh hưởng đến chuyến xe đang thực hiện.
### NFR15 – Ghi nhận nhật ký
Hệ thống phải ghi nhận các thao tác quan trọng như đăng nhập, tạo chuyến, nhận chuyến, từ chối chuyến, hủy chuyến và hoàn thành chuyến để phục vụ việc kiểm tra và quản lý.
Bước 11 xác định và vẽ usecase 
flowchart LR
    KH["Khách hàng"]
    TX["Tài xế"]
    QTV["Quản trị viên"]

    subgraph HT["Hệ thống đặt xe"]
        UC1(["Đăng ký tài khoản"])
        UC2(["Đăng nhập"])
        UC3(["Đặt chuyến đi"])
        UC4(["Theo dõi chuyến đi"])
        UC5(["Hủy chuyến đi"])
        UC6(["Thanh toán chuyến đi"])
        UC7(["Đánh giá chuyến đi"])

        UC8(["Đăng nhập"])
        UC9(["Nhận chuyến đi"])
        UC10(["Thực hiện chuyến đi"])
        UC11(["Cập nhật trạng thái chuyến đi"])
        UC12(["Cập nhật vị trí hiện tại"])

        UC13(["Quản lý khách hàng"])
        UC14(["Quản lý tài xế"])
        UC15(["Quản lý phương tiện"])
        UC16(["Quản lý loại xe"])
        UC17(["Quản lý chuyến đi"])
        UC18(["Quản lý thanh toán"])
        UC19(["Quản lý đánh giá"])
        UC20(["Gửi thông báo"])
    end

    KH --- UC1
    KH --- UC2
    KH --- UC3
    KH --- UC4
    KH --- UC5
    KH --- UC6
    KH --- UC7

    TX --- UC8
    TX --- UC9
    TX --- UC10
    TX --- UC11
    TX --- UC12

    QTV --- UC13
    QTV --- UC14
    QTV --- UC15
    QTV --- UC16
    QTV --- UC17
    QTV --- UC18
    QTV --- UC19
    QTV --- UC20

    UC3 -.->|include| UC20
    UC6 -.->|include| UC18
    UC7 -.->|include| UC19
    UC9 -.->|include| UC20
    UC10 -.->|include| UC11

    classDef actor fill:#fefce8,stroke:#facc15,stroke-width:2px,color:#713f12;
    classDef customer fill:#eef2ff,stroke:#818cf8,stroke-width:2px,color:#312e81;
    classDef driver fill:#f0fdfa,stroke:#2dd4bf,stroke-width:2px,color:#134e4a;
    classDef admin fill:#fff7ed,stroke:#fb923c,stroke-width:2px,color:#7c2d12;
    classDef notification fill:#fdf4ff,stroke:#e879f9,stroke-width:2px,color:#701a75;

    class KH actor;
    class TX actor;
    class QTV actor;
    class UC1,UC2,UC3,UC4,UC5,UC6,UC7 customer;
    class UC8,UC9,UC10,UC11,UC12 driver;
    class UC13,UC14,UC15,UC16,UC17,UC18,UC19 admin;
    class UC20 notification;
Bước 12 Đặt Tả Usecase
12. ĐẶC TẢ USE CASE
12.1. Quy ước đặc tả

Mỗi Use Case được đặc tả theo các nội dung:

Mã Use Case
Tên Use Case
Actor
Mục tiêu
Điều kiện trước
Điều kiện sau
Luồng chính
Luồng ngoại lệ
Business Rules liên quan
12.2. UC01 – Đăng ký tài khoản
Thành phần	Nội dung
Mã Use Case	UC01
Tên Use Case	Đăng ký tài khoản
Actor	Khách hàng, Tài xế
Mục tiêu	Cho phép người dùng tạo tài khoản để sử dụng hệ thống.
Điều kiện trước	Người dùng chưa có tài khoản.
Điều kiện sau	Tài khoản được tạo thành công.
Luồng chính
Người dùng chọn chức năng Đăng ký.
Hệ thống hiển thị biểu mẫu đăng ký.
Người dùng nhập thông tin đăng ký.
Người dùng xác nhận đăng ký.
Hệ thống kiểm tra tính hợp lệ của thông tin.
Hệ thống kiểm tra tài khoản đã tồn tại hay chưa.
Hệ thống tạo tài khoản.
Hệ thống thông báo đăng ký thành công.
Luồng ngoại lệ
E1: Thông tin không hợp lệ → hệ thống yêu cầu người dùng nhập lại.
E2: Tài khoản đã tồn tại → hệ thống thông báo và yêu cầu sử dụng thông tin khác.
E3: Xảy ra lỗi hệ thống → hệ thống thông báo đăng ký thất bại.
12.3. UC02 – Đăng nhập
Thành phần	Nội dung
Mã Use Case	UC02
Tên Use Case	Đăng nhập
Actor	Khách hàng, Tài xế, Quản trị viên
Mục tiêu	Cho phép người dùng truy cập hệ thống theo quyền được cấp.
Điều kiện trước	Người dùng đã có tài khoản.
Điều kiện sau	Người dùng đăng nhập thành công.
Luồng chính
Người dùng chọn Đăng nhập.
Hệ thống hiển thị màn hình đăng nhập.
Người dùng nhập thông tin tài khoản.
Người dùng xác nhận đăng nhập.
Hệ thống kiểm tra thông tin.
Hệ thống xác thực tài khoản.
Hệ thống xác định vai trò người dùng.
Hệ thống cho phép truy cập các chức năng tương ứng.
Luồng ngoại lệ
E1: Sai thông tin đăng nhập → hệ thống thông báo đăng nhập thất bại.
E2: Tài khoản bị khóa → hệ thống thông báo tài khoản không thể đăng nhập.
E3: Tài khoản không tồn tại → hệ thống yêu cầu kiểm tra lại thông tin.
12.4. UC03 – Đặt xe
Thành phần	Nội dung
Mã Use Case	UC03
Tên Use Case	Đặt xe
Actor	Khách hàng
Mục tiêu	Cho phép khách hàng tạo yêu cầu đặt xe.
Điều kiện trước	Khách hàng đã đăng nhập.
Điều kiện sau	Chuyến xe được tạo và chuyển sang trạng thái Đang tìm tài xế.
Luồng chính
Khách hàng chọn chức năng Đặt xe.
Hệ thống hiển thị màn hình đặt xe.
Khách hàng nhập điểm đón.
Khách hàng nhập điểm đến.
Khách hàng chọn loại xe.
Hệ thống hiển thị thông tin chuyến dự kiến.
Khách hàng xác nhận đặt xe.
Hệ thống kiểm tra thông tin chuyến.
Hệ thống tạo chuyến.
Hệ thống chuyển trạng thái chuyến thành Đang tìm tài xế.
Hệ thống thực hiện Use Case UC04 – Tìm tài xế.
Luồng ngoại lệ
E1: Thiếu điểm đón → hệ thống yêu cầu nhập điểm đón.
E2: Thiếu điểm đến → hệ thống yêu cầu nhập điểm đến.
E3: Chưa chọn loại xe → hệ thống yêu cầu chọn loại xe.
E4: Khách hàng hủy thao tác → hệ thống không tạo chuyến.
Business Rules
BR01: Chuyến phải có đầy đủ điểm đón, điểm đến và loại xe.
BR02: Chuyến mới được chuyển sang tìm tài xế sau khi tạo thành công.
12.5. UC04 – Tìm tài xế
Thành phần	Nội dung
Mã Use Case	UC04
Tên Use Case	Tìm tài xế
Actor	Hệ thống
Mục tiêu	Tìm tài xế phù hợp để thực hiện chuyến xe.
Điều kiện trước	Chuyến đã được tạo thành công và ở trạng thái Đang tìm tài xế.
Điều kiện sau	Một tài xế chấp nhận chuyến hoặc hệ thống kết thúc quá trình tìm kiếm.
Luồng chính
Hệ thống nhận yêu cầu tìm tài xế.
Hệ thống lấy thông tin điểm đón và loại xe của chuyến.
Hệ thống tìm các tài xế đang ở trạng thái Sẵn sàng.
Hệ thống loại bỏ các tài xế không phù hợp với loại xe.
Hệ thống ưu tiên tài xế phù hợp với vị trí điểm đón.
Hệ thống gửi yêu cầu nhận chuyến cho tài xế phù hợp.
Hệ thống chờ phản hồi của tài xế.
Tài xế chấp nhận chuyến.
Hệ thống gán tài xế cho chuyến.
Hệ thống chuyển trạng thái tài xế thành Đang nhận chuyến.
Hệ thống chuyển chuyến thành Đã tìm thấy tài xế.
Hệ thống thông báo thông tin tài xế cho khách hàng.
Luồng ngoại lệ
E1 – Tài xế từ chối
Tài xế chọn Từ chối.
Hệ thống ghi nhận yêu cầu bị từ chối.
Hệ thống tiếp tục tìm tài xế khác.
E2 – Tài xế không phản hồi
Hệ thống gửi yêu cầu cho tài xế.
Tài xế không phản hồi trong thời gian quy định.
Hệ thống tự động hết hạn yêu cầu.
Hệ thống Reject yêu cầu.
Hệ thống tiếp tục tìm tài xế khác.
E3 – Tài xế không còn trạng thái Sẵn sàng
Hệ thống chọn tài xế.
Trước khi tài xế phản hồi, trạng thái tài xế thay đổi thành Bận/Offline.
Hệ thống hủy yêu cầu đối với tài xế đó.
Hệ thống tìm tài xế khác.
E4 – Tài xế đã nhận chuyến khác
Hệ thống gửi yêu cầu đến tài xế.
Tài xế nhận một chuyến khác trước khi chấp nhận chuyến hiện tại.
Hệ thống phát hiện tài xế không còn khả dụng.
Hệ thống loại tài xế đó.
Hệ thống tìm tài xế khác.
E5 – Không tìm được tài xế
Hệ thống không tìm được tài xế phù hợp.
Hệ thống tiếp tục tìm trong thời gian quy định.
Hết thời gian tìm kiếm.
Hệ thống thông báo Không tìm thấy tài xế phù hợp.
Khách hàng chọn Thử lại hoặc Hủy chuyến.
Business Rules
BR03: Chỉ tài xế có trạng thái Sẵn sàng mới được lựa chọn.
BR04: Tài xế phải có loại xe phù hợp với yêu cầu của khách hàng.
BR05: Tài xế chỉ được nhận một chuyến đang hoạt động.
BR06: Tài xế phải phản hồi trong thời gian quy định.
BR07: Hệ thống ưu tiên tài xế phù hợp với vị trí điểm đón.
12.6. UC05 – Chấp nhận chuyến
Thành phần	Nội dung
Mã Use Case	UC05
Tên Use Case	Chấp nhận chuyến
Actor	Tài xế
Mục tiêu	Cho phép tài xế chấp nhận yêu cầu chuyến.
Điều kiện trước	Tài xế đang ở trạng thái Sẵn sàng và nhận được yêu cầu chuyến.
Điều kiện sau	Chuyến được gán cho tài xế và tài xế chuyển sang trạng thái Đang nhận chuyến.
Luồng chính
Tài xế nhận thông báo yêu cầu chuyến.
Hệ thống hiển thị thông tin chuyến.
Tài xế xem thông tin chuyến.
Tài xế chọn Chấp nhận.
Hệ thống kiểm tra tài xế còn ở trạng thái Sẵn sàng.
Hệ thống kiểm tra chuyến chưa được tài xế khác nhận.
Hệ thống gán chuyến cho tài xế.
Hệ thống cập nhật trạng thái tài xế thành Đang nhận chuyến.
Hệ thống thông báo cho khách hàng.
Luồng ngoại lệ
E1: Tài xế không còn Sẵn sàng → hệ thống không cho phép nhận chuyến và tiếp tục tìm tài xế khác.
E2: Chuyến đã được tài xế khác nhận → hệ thống thông báo chuyến không còn khả dụng.
E3: Hết thời gian phản hồi → yêu cầu hết hạn và hệ thống tiếp tục tìm tài xế khác.
12.7. UC06 – Từ chối chuyến
Thành phần	Nội dung
Mã Use Case	UC06
Tên Use Case	Từ chối chuyến
Actor	Tài xế
Mục tiêu	Cho phép tài xế từ chối yêu cầu chuyến.
Điều kiện trước	Tài xế đang nhận yêu cầu chuyến.
Điều kiện sau	Yêu cầu bị từ chối và hệ thống tiếp tục tìm tài xế khác.
Luồng chính
Tài xế nhận yêu cầu chuyến.
Tài xế xem thông tin chuyến.
Tài xế chọn Từ chối.
Hệ thống ghi nhận yêu cầu bị từ chối.
Hệ thống tiếp tục tìm tài xế khác.
Hệ thống thông báo trạng thái tìm tài xế cho khách hàng.
Luồng ngoại lệ
E1: Chuyến đã được tài xế khác nhận → hệ thống kết thúc yêu cầu.
E2: Xảy ra lỗi hệ thống → hệ thống thông báo lỗi và ghi nhận trạng thái phù hợp.
12.8. UC07 – Theo dõi chuyến xe
Thành phần	Nội dung
Mã Use Case	UC07
Tên Use Case	Theo dõi chuyến xe
Actor	Khách hàng
Mục tiêu	Cho phép khách hàng theo dõi trạng thái chuyến và thông tin tài xế.
Điều kiện trước	Khách hàng đã có chuyến xe.
Điều kiện sau	Khách hàng xem được trạng thái hiện tại của chuyến.
Luồng chính
Khách hàng mở chuyến đang thực hiện.
Hệ thống hiển thị thông tin tài xế.
Hệ thống hiển thị trạng thái chuyến.
Hệ thống cập nhật trạng thái chuyến theo quá trình thực hiện.
Khách hàng theo dõi chuyến.
Khi chuyến hoàn thành, hệ thống hiển thị trạng thái Hoàn thành.
Luồng ngoại lệ
E1: Không thể cập nhật vị trí → hệ thống thông báo thông tin vị trí tạm thời không khả dụng.
E2: Chuyến bị hủy → hệ thống thông báo chuyến đã bị hủy.
12.9. UC08 – Hủy chuyến
Thành phần	Nội dung
Mã Use Case	UC08
Tên Use Case	Hủy chuyến
Actor	Khách hàng, Tài xế
Mục tiêu	Cho phép hủy chuyến theo điều kiện của hệ thống.
Điều kiện trước	Chuyến đang ở trạng thái có thể hủy.
Điều kiện sau	Chuyến chuyển sang trạng thái Đã hủy.
Luồng chính
Người dùng chọn Hủy chuyến.
Hệ thống kiểm tra trạng thái chuyến.
Hệ thống hiển thị yêu cầu xác nhận.
Người dùng xác nhận hủy.
Hệ thống cập nhật chuyến thành Đã hủy.
Hệ thống thông báo kết quả.
Luồng ngoại lệ
E1: Chuyến không còn được phép hủy → hệ thống thông báo không thể hủy chuyến.
E2: Khách hàng hủy trong lúc tìm tài xế → hệ thống dừng quá trình tìm tài xế.
E3: Tài xế hủy sau khi đã nhận chuyến → hệ thống chuyển chuyến về Đang tìm tài xế và tiếp tục tìm tài xế khác.
12.10. UC09 – Thanh toán
Thành phần	Nội dung
Mã Use Case	UC09
Tên Use Case	Thanh toán
Actor	Khách hàng
Mục tiêu	Cho phép khách hàng thanh toán chi phí chuyến xe.
Điều kiện trước	Chuyến đã hoàn thành và hệ thống đã xác định số tiền cần thanh toán.
Điều kiện sau	Thanh toán được ghi nhận thành công hoặc thất bại.
Luồng chính
Chuyến xe hoàn thành.
Hệ thống tính số tiền cần thanh toán.
Hệ thống hiển thị số tiền.
Khách hàng chọn phương thức thanh toán.
Khách hàng xác nhận thanh toán.
Hệ thống xử lý thanh toán.
Hệ thống ghi nhận thanh toán thành công.
Hệ thống cập nhật trạng thái thanh toán.
Luồng ngoại lệ
E1: Thanh toán thất bại → hệ thống thông báo và cho phép thực hiện lại.
E2: Phương thức thanh toán không hợp lệ → yêu cầu chọn phương thức khác.
E3: Mất kết nối trong quá trình thanh toán → hệ thống kiểm tra lại trạng thái giao dịch trước khi cho phép thanh toán lại.
12.11. UC10 – Đánh giá tài xế
Thành phần	Nội dung
Mã Use Case	UC10
Tên Use Case	Đánh giá tài xế
Actor	Khách hàng
Mục tiêu	Cho phép khách hàng đánh giá tài xế sau chuyến xe.
Điều kiện trước	Chuyến đã hoàn thành.
Điều kiện sau	Đánh giá được lưu vào hệ thống.
Luồng chính
Khách hàng mở chuyến đã hoàn thành.
Hệ thống hiển thị chức năng đánh giá.
Khách hàng chọn số sao và có thể nhập nhận xét.
Khách hàng gửi đánh giá.
Hệ thống kiểm tra dữ liệu.
Hệ thống lưu đánh giá.
Hệ thống thông báo đánh giá thành công.
Luồng ngoại lệ
E1: Đánh giá không hợp lệ → hệ thống yêu cầu nhập lại.
E2: Khách hàng đã đánh giá chuyến → hệ thống không cho phép đánh giá lần nữa.
12.12. UC11 – Cập nhật trạng thái tài xế
Thành phần	Nội dung
Mã Use Case	UC11
Tên Use Case	Cập nhật trạng thái tài xế
Actor	Tài xế
Mục tiêu	Cho phép tài xế cập nhật trạng thái hoạt động.
Điều kiện trước	Tài xế đã đăng nhập.
Điều kiện sau	Trạng thái tài xế được cập nhật.
Luồng chính
Tài xế mở chức năng trạng thái.
Tài xế chọn trạng thái Sẵn sàng hoặc Offline.
Hệ thống kiểm tra điều kiện cập nhật.
Hệ thống lưu trạng thái.
Hệ thống cập nhật trạng thái tài xế.
Luồng ngoại lệ
E1: Tài xế đang có chuyến → không cho phép chuyển sang trạng thái Offline.
E2: Tài xế đang thực hiện chuyến → trạng thái được duy trì là Đang nhận chuyến.
12.13. UC12 – Quản lý khách hàng
Thành phần	Nội dung
Mã Use Case	UC12
Tên Use Case	Quản lý khách hàng
Actor	Quản trị viên
Mục tiêu	Cho phép quản trị viên quản lý tài khoản khách hàng.
Điều kiện trước	Quản trị viên đã đăng nhập.
Điều kiện sau	Thông tin khách hàng được cập nhật theo thao tác của quản trị viên.
Luồng chính
Quản trị viên chọn Quản lý khách hàng.
Hệ thống hiển thị danh sách khách hàng.
Quản trị viên xem thông tin khách hàng.
Quản trị viên có thể thêm, sửa, khóa hoặc mở khóa tài khoản.
Hệ thống kiểm tra dữ liệu.
Hệ thống lưu thay đổi.
Bước 14 – Ma trận truy xuất nguồn gốc yêu cầu (RTM)
14.1. Quy ước mã
Ký hiệu	Ý nghĩa
BG	Business Goal – Mục tiêu nghiệp vụ
BR	Business Rule – Quy tắc nghiệp vụ
FR	Functional Requirement – Yêu cầu chức năng
UC	Use Case – Ca sử dụng
AC	Acceptance Criteria – Tiêu chí chấp nhận
TC	Test Case – Ca kiểm thử
14.2. Business Goal (BG)
Mã	Business Goal
BG01	Cho phép khách hàng đặt chuyến xe nhanh chóng và thuận tiện.
BG02	Tự động tìm và phân công tài xế phù hợp cho khách hàng.
BG03	Quản lý quá trình thực hiện chuyến xe từ lúc đặt xe đến khi hoàn thành.
BG04	Đảm bảo việc thanh toán và đánh giá sau chuyến xe.
BG05	Cho phép quản trị viên quản lý khách hàng, tài xế, loại xe và chuyến xe.
14.3. Business Rule (BR)
Mã	Business Rule
BR01	Chỉ tài xế có trạng thái Sẵn sàng mới được nhận chuyến.
BR02	Tài xế phải có loại xe phù hợp với loại xe khách hàng yêu cầu.
BR03	Một tài xế không được nhận đồng thời nhiều chuyến đang hoạt động.
BR04	Tài xế phải phản hồi yêu cầu chuyến trong thời gian quy định.
BR05	Nếu tài xế từ chối hoặc không phản hồi, hệ thống phải tìm tài xế khác.
BR06	Nếu không tìm được tài xế trong thời gian quy định, hệ thống phải thông báo cho khách hàng.
BR07	Khi tài xế hủy chuyến sau khi đã nhận, hệ thống phải xử lý theo quy định và có thể tìm tài xế thay thế.
BR08	Khách hàng chỉ được đánh giá sau khi chuyến đã hoàn thành.
BR09	Chuyến chỉ được thanh toán sau khi chuyến hoàn thành.
BR10	Người dùng chỉ được truy cập các chức năng phù hợp với vai trò của mình.
14.4. Functional Requirement (FR)
Mã	Functional Requirement
FR01	Hệ thống phải cho phép khách hàng đăng ký tài khoản.
FR02	Hệ thống phải cho phép người dùng đăng nhập.
FR03	Hệ thống phải cho phép khách hàng nhập điểm đón, điểm đến và loại xe để đặt chuyến.
FR04	Hệ thống phải tạo chuyến sau khi khách hàng xác nhận đặt xe.
FR05	Hệ thống phải tìm tài xế phù hợp với chuyến xe.
FR06	Hệ thống phải gửi yêu cầu nhận chuyến cho tài xế phù hợp.
FR07	Hệ thống phải cho phép tài xế chấp nhận hoặc từ chối chuyến.
FR08	Hệ thống phải tự động tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.
FR09	Hệ thống phải thông báo cho khách hàng khi không tìm được tài xế.
FR10	Hệ thống phải cho phép khách hàng theo dõi chuyến xe.
FR11	Hệ thống phải cho phép khách hàng hoặc tài xế hủy chuyến theo quy định.
FR12	Hệ thống phải cập nhật trạng thái chuyến trong quá trình thực hiện.
FR13	Hệ thống phải cho phép khách hàng thanh toán sau khi chuyến hoàn thành.
FR14	Hệ thống phải cho phép khách hàng đánh giá tài xế sau khi chuyến hoàn thành.
FR15	Hệ thống phải cho phép tài xế cập nhật trạng thái hoạt động.
FR16	Hệ thống phải cho phép quản trị viên quản lý khách hàng.
FR17	Hệ thống phải cho phép quản trị viên quản lý tài xế.
FR18	Hệ thống phải cho phép quản trị viên quản lý loại xe.
FR19	Hệ thống phải cho phép quản trị viên quản lý chuyến xe.
Hệ thống thông báo kết quả.
12.14. UC13 – Quản lý tài xế
Thành phần	Nội dung
Mã Use Case	UC13
Tên Use Case	Quản lý tài xế
Actor	Quản trị viên
Mục tiêu	Quản lý thông tin và trạng thái tài xế.
Điều kiện trước	Quản trị viên đã đăng nhập.
Điều kiện sau	Thông tin tài xế được cập nhật.
Luồng chính
Quản trị viên chọn Quản lý tài xế.
Hệ thống hiển thị danh sách tài xế.
Quản trị viên xem thông tin.
Quản trị viên thêm, sửa, khóa hoặc mở khóa tài xế.
Hệ thống kiểm tra dữ liệu.
Hệ thống lưu thay đổi.
Hệ thống thông báo kết quả.
12.15. UC14 – Quản lý loại xe
Thành phần	Nội dung
Mã Use Case	UC14
Tên Use Case	Quản lý loại xe
Actor	Quản trị viên
Mục tiêu	Cho phép quản trị viên quản lý các loại xe được cung cấp.
Điều kiện trước	Quản trị viên đã đăng nhập.
Điều kiện sau	Danh sách loại xe được cập nhật.
Luồng chính
Quản trị viên chọn Quản lý loại xe.
Hệ thống hiển thị danh sách loại xe.
Quản trị viên thêm, sửa hoặc xóa loại xe.
Hệ thống kiểm tra dữ liệu.
Hệ thống lưu thay đổi.
Hệ thống cập nhật danh sách loại xe.
Luồng ngoại lệ
E1: Loại xe đang được sử dụng cho chuyến → hệ thống không cho phép xóa.
E2: Thông tin loại xe không hợp lệ → hệ thống yêu cầu nhập lại.
12.16. UC15 – Quản lý chuyến xe
Thành phần	Nội dung
Mã Use Case	UC15
Tên Use Case	Quản lý chuyến xe
Actor	Quản trị viên
Mục tiêu	Cho phép quản trị viên theo dõi và quản lý các chuyến xe trên hệ thống.
Điều kiện trước	Quản trị viên đã đăng nhập.
Điều kiện sau	Thông tin chuyến xe được xem hoặc xử lý theo quyền quản trị.
Luồng chính
Quản trị viên chọn Quản lý chuyến xe.
Hệ thống hiển thị danh sách chuyến.
Quản trị viên tìm kiếm hoặc lọc chuyến.
Quản trị viên xem chi tiết chuyến.
Hệ thống hiển thị thông tin khách hàng, tài xế, trạng thái và thông tin chuyến.
Luồng ngoại lệ
E1: Không tìm thấy chuyến phù hợp → hệ thống thông báo không có dữ liệu.
E2: Dữ liệu chuyến không khả dụng → hệ thống thông báo lỗi.
13. Acceptance Criteria – Tiêu chí chấp nhận
| Mã   | Chức năng                 | Tiêu chí chấp nhận                                                                                                                         |
| ---- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| AC01 | Đăng ký                   | Khi người dùng nhập đầy đủ thông tin hợp lệ và chưa tồn tại tài khoản, hệ thống phải tạo tài khoản thành công.                             |
| AC02 | Đăng ký                   | Nếu thông tin đăng ký không hợp lệ hoặc tài khoản đã tồn tại, hệ thống phải thông báo lỗi và không tạo tài khoản.                          |
| AC03 | Đăng nhập                 | Khi nhập đúng tài khoản và mật khẩu, người dùng phải đăng nhập thành công và được chuyển đến giao diện tương ứng với vai trò.              |
| AC04 | Đăng nhập                 | Khi nhập sai tài khoản hoặc mật khẩu, hệ thống phải thông báo lỗi và không cho phép truy cập.                                              |
| AC05 | Đặt xe                    | Khi khách hàng nhập đầy đủ điểm đón, điểm đến và loại xe, hệ thống phải tạo chuyến thành công.                                             |
| AC06 | Đặt xe                    | Sau khi tạo chuyến, trạng thái chuyến phải chuyển thành **Đang tìm tài xế**.                                                               |
| AC07 | Tìm tài xế                | Hệ thống chỉ được gửi yêu cầu nhận chuyến cho tài xế có trạng thái **Sẵn sàng**.                                                           |
| AC08 | Tìm tài xế                | Hệ thống không được gửi yêu cầu cho tài xế đang bận, Offline hoặc đang thực hiện chuyến khác.                                              |
| AC09 | Tìm tài xế                | Tài xế được lựa chọn phải có loại xe phù hợp với loại xe khách hàng yêu cầu.                                                               |
| AC10 | Chấp nhận chuyến          | Khi tài xế đang Sẵn sàng và chấp nhận trong thời gian quy định, hệ thống phải gán chuyến cho tài xế đó.                                    |
| AC11 | Chấp nhận chuyến          | Sau khi tài xế nhận chuyến, trạng thái tài xế phải chuyển thành **Đang nhận chuyến**.                                                      |
| AC12 | Không phản hồi            | Nếu tài xế không phản hồi trong thời gian quy định, yêu cầu phải tự động hết hạn và hệ thống phải tìm tài xế khác.                         |
| AC13 | Từ chối chuyến            | Nếu tài xế từ chối, hệ thống phải ghi nhận việc từ chối và tiếp tục tìm tài xế khác.                                                       |
| AC14 | Tài xế không còn sẵn sàng | Nếu tài xế chuyển sang trạng thái không sẵn sàng trước khi nhận chuyến, hệ thống phải loại tài xế đó và tìm tài xế khác.                   |
| AC15 | Không tìm được tài xế     | Nếu hết thời gian tìm kiếm mà không có tài xế phù hợp, hệ thống phải thông báo cho khách hàng và cung cấp lựa chọn **Thử lại/Hủy chuyến**. |
| AC16 | Theo dõi chuyến           | Khách hàng phải xem được trạng thái hiện tại của chuyến và thông tin tài xế sau khi chuyến được xác nhận.                                  |
| AC17 | Hủy chuyến                | Khi khách hàng hủy chuyến trong thời gian được phép, hệ thống phải chuyển chuyến sang trạng thái **Đã hủy**.                               |
| AC18 | Tài xế hủy                | Nếu tài xế hủy chuyến sau khi đã nhận, hệ thống phải chuyển chuyến về trạng thái **Đang tìm tài xế** và tiếp tục tìm tài xế khác.          |
| AC19 | Hoàn thành chuyến         | Khi tài xế hoàn thành chuyến, hệ thống phải cập nhật trạng thái chuyến thành **Hoàn thành**.                                               |
| AC20 | Thanh toán                | Sau khi chuyến hoàn thành, hệ thống phải hiển thị đúng số tiền cần thanh toán và ghi nhận kết quả thanh toán.                              |
| AC21 | Đánh giá                  | Sau khi chuyến hoàn thành, khách hàng phải có thể đánh giá tài xế và hệ thống phải lưu đánh giá thành công.                                |
| AC22 | Trạng thái tài xế         | Khi tài xế chọn **Sẵn sàng**, hệ thống phải cập nhật trạng thái và cho phép tài xế được đưa vào quá trình tìm chuyến.                      |
| AC23 | Trạng thái tài xế         | Khi tài xế đang có chuyến, hệ thống không được cho phép tài xế nhận thêm chuyến khác.                                                      |
| AC24 | Phân quyền                | Khách hàng, tài xế và quản trị viên chỉ được truy cập các chức năng thuộc quyền của mình.                                                  |
| AC25 | Quản lý                   | Khi quản trị viên thêm, sửa, khóa hoặc cập nhật thông tin, hệ thống phải lưu thay đổi thành công và hiển thị dữ liệu mới.                  |
