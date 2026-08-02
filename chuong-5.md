**CHƯƠNG 5: QUẢN LÝ TRUYỀN THÔNG VÀ RỦI RO DỰ ÁN**

Quản lý truyền thông và quản lý rủi ro là hai nhóm công việc xuyên suốt vòng đời dự án xây dựng website thương mại điện tử HOALYLY.vn. Trên nền tảng các bên liên quan và ma trận RACI tại Chương 2, WBS cùng lịch trình tại Chương 3, ngân sách và nguồn lực tại Chương 4, chương này cụ thể hóa kênh trao đổi thông tin, mẫu báo cáo vận hành, đồng thời xây dựng danh mục rủi ro, đánh giá định tính và phương án ứng phó phù hợp với quy mô hộ kinh doanh nhỏ và mô hình Agile/Scrum đã lựa chọn.

**5.1. Quản lý truyền thông**

Quản lý truyền thông nhằm bảo đảm đúng thông tin đến đúng người, đúng thời điểm và bằng phương thức phù hợp. Theo phân công tại mục 2.4 và kế hoạch nguồn lực mục 4.2, đội dự án gồm Quản lý dự án (PM/Scrum Master), hai lập trình viên, UI/UX Designer, Tester/QA và Chủ cửa hàng HOALYLY với vai trò Product Owner. Việc thiết lập kế hoạch truyền thông rõ ràng giúp giảm lệch pha giữa yêu cầu nghiệp vụ và giải pháp kỹ thuật, đồng thời hỗ trợ kiểm soát tiến độ, chi phí và chất lượng theo từng Sprint.

**5.1.1. Các bên liên quan và nhu cầu thông tin**

Các bên liên quan chính đã được liệt kê tại mục 2.2, gồm: Chủ cửa hàng (Sponsor/Product Owner), Quản lý dự án, Đội phát triển, Nhân viên cửa hàng (người dùng Admin), Khách hàng cuối và Nhà cung cấp hosting/domain. Nhu cầu thông tin của từng bên khác nhau về nội dung, mức độ chi tiết và tần suất. Bảng kế hoạch truyền thông dưới đây tổng hợp các luồng thông tin vận hành trong dự án.

| Bên liên quan | Nhu cầu thông tin chính | Người cung cấp | Tần suất | Phương thức | Mục đích |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Chủ cửa hàng (PO/Sponsor) | Tiến độ Sprint, ngân sách đã sử dụng, rủi ro nổi bật, sản phẩm demo cần nghiệm thu | PM | Hàng tuần và cuối mỗi Sprint | Google Meet, Email, Zalo | Phê duyệt, ưu tiên backlog, quyết định thay đổi |
| Quản lý dự án (PM) | Trạng thái công việc, rào cản kỹ thuật, kết quả kiểm thử, chi phí phát sinh | Dev, Tester, Designer | Hàng ngày (họp standup ngắn) và hàng tuần | Zalo nhóm, Trello, Google Meet | Điều phối nguồn lực, cập nhật kế hoạch |
| Đội phát triển (Dev, Designer) | Yêu cầu đã ưu tiên, phản hồi UAT, tiêu chuẩn coding/.NET, lịch review | PO, PM, Tester | Theo Sprint và khi có thay đổi | Trello, GitHub, Google Meet | Thực hiện đúng phạm vi và chất lượng |
| Tester/QA | Phiên bản build cần kiểm thử, tiêu chí chấp nhận, danh sách lỗi đã sửa | Dev, PM | Theo chu kỳ kiểm thử trong Sprint | Trello, GitHub Issues, Email | Lập test case, xác nhận kết quả |
| Nhân viên cửa hàng | Cách dùng Admin (sản phẩm, đơn hàng, tồn kho), lịch đào tạo | PM, Dev | Giai đoạn bàn giao và hỗ trợ sau triển khai | Google Meet, tài liệu hướng dẫn | Vận hành hệ thống sau triển khai chính thức |
| Nhà cung cấp hosting/domain | Yêu cầu môi trường (Windows Hosting, SQL Server), sự cố hạ tầng | PM, Dev | Khi đăng ký/triển khai hoặc khi sự cố | Email, cổng hỗ trợ nhà cung cấp | Bảo đảm website online ổn định |
| Khách hàng cuối | Thông báo đơn hàng, trạng thái giao hàng (qua hệ thống) | Hệ thống website | Theo từng giao dịch | Email hệ thống (theo luồng đặt hàng đã thiết kế tại Chương 3) | Xác nhận đơn và theo dõi giao nhận |

*Bảng 5.1: Kế hoạch truyền thông dự án HOALYLY.vn*

Kế hoạch trên bám sát ma trận RACI tại mục 2.2: Chủ shop là Accountable đối với nghiệm thu, đào tạo người dùng và phê duyệt các hạng mục then chốt; PM là Responsible trong điều phối, báo cáo tiến độ và tổ chức họp; Đội phát triển là Responsible trong lập trình, thiết kế và tham gia kiểm thử. Các cuộc họp hàng tuần giữa nhóm phát triển và Chủ cửa hàng (đã nêu tại mục 2.3 khi lựa chọn Agile/Scrum) được duy trì như kênh chính để phát hiện sớm lệch yêu cầu.

**5.1.2. Công cụ truyền thông**

Dự án sử dụng bộ công cụ gọn, chi phí thấp, phù hợp nhóm nhỏ và môi trường làm việc phân tán. Các công cụ dưới đây trùng với danh mục đề xuất trong đề cương chương và phù hợp khoản chi công cụ phát triển đã dự toán tại mục 4.1.1 (Visual Studio Community, Figma, Git):

| Công cụ | Vai trò trong dự án | Nội dung chính trao đổi |
| :---- | :---- | :---- |
| Email | Trao đổi chính thức, lưu vết phê duyệt | Báo cáo tuần, đề xuất chi phí trên 1.000.000 VND (theo quy trình phê duyệt tại mục 4.1.3), biên bản nghiệm thu, liên hệ nhà cung cấp hosting/domain |
| Zalo | Trao đổi nhanh nội bộ và với Chủ shop | Nhắc việc hằng ngày, thông báo rào cản khẩn, chia sẻ link họp và cập nhật ngắn về tiến độ |
| Google Meet | Họp trực tuyến | Họp standup ngắn, Sprint Review/Demo, Sprint Retrospective, họp xử lý rủi ro hoặc thay đổi phạm vi |
| Trello | Quản lý backlog và theo dõi công việc | Product Backlog, Sprint Backlog, cột trạng thái (To Do / Doing / Done), gắn người phụ trách theo bảng phân công nhân sự mục 2.4 |
| GitHub | Quản lý mã nguồn và phối hợp kỹ thuật | Repository ASP.NET MVC, Pull Request, code review, Issues theo dõi lỗi; hỗ trợ quy trình merge vào nhánh develop sau khi khắc phục vấn đề mức Cao (theo biên bản đánh giá chất lượng mã nguồn tại phần quản lý chất lượng) |

*Bảng 5.2: Công cụ truyền thông và phối hợp*

Nguyên tắc sử dụng: thông tin quyết định và phê duyệt phải có bản ghi trên Email hoặc biên bản họp; trao đổi kỹ thuật và trạng thái công việc ưu tiên Trello/GitHub; Zalo chỉ dùng cho thông tin ngắn, không thay thế tài liệu chính thức. Cách phân tầng này giúp giảm nhiễu thông tin nhưng vẫn giữ tốc độ phản hồi cần thiết với mô hình Agile.

**5.1.3. Báo cáo và biên bản**

Hai nhóm tài liệu vận hành chính là báo cáo tiến độ tuần và biên bản họp. Chúng phục vụ giám sát theo nhóm tiến trình Giám sát và kiểm soát (Monitoring & Controlling) của PMBOK đã nêu tại Chương 1, đồng thời cung cấp dữ liệu đầu vào cho kiểm soát chi phí (so sánh thực tế với kế hoạch cuối mỗi tuần tại mục 4.1.3) và cập nhật rủi ro.

**a) Báo cáo tiến độ tuần**

PM tổng hợp và gửi Chủ cửa hàng cùng nhóm vào cuối mỗi tuần làm việc. Nội dung tối thiểu gồm:

1. Tiến độ so với kế hoạch Sprint/WBS: các gói công việc hoàn thành, đang thực hiện, chậm so với ước lượng.
2. Kết quả kiểm thử trong tuần (số lỗi mở/đóng, mức độ nghiêm trọng) nếu có hoạt động QA.
3. Chi phí phát sinh trong tuần và tỷ lệ tiêu thụ ngân sách so với tổng dự toán 33.990.000 VND tại mục 4.1.1 (vẫn nằm trong trần ngân sách không vượt quá 50.000.000 VND theo Project Charter).
4. Rủi ro mới phát sinh hoặc rủi ro hiện hữu thay đổi mức độ.
5. Kế hoạch tuần tiếp theo và các quyết định cần Chủ shop phê duyệt (thay đổi yêu cầu, chi phí vượt ngưỡng).

Mẫu khung báo cáo tuần:

| Mục | Nội dung điền |
| :---- | :---- |
| Tuần báo cáo / Sprint | Ví dụ: Tuần 5 / Sprint 2 (theo lịch Sprint tại mục 2.4) |
| Công việc hoàn thành | Liệt kê theo mã WBS hoặc thẻ Trello |
| Công việc chậm / rào cản | Mô tả nguyên nhân và người xử lý |
| Ngân sách tuần | Chi thực tế / kế hoạch; mức chênh lệch (%) theo bảng 4.4 |
| Rủi ro cần lưu ý | Mã rủi ro, mức độ, hành động |
| Đề xuất / quyết định chờ duyệt | Nội dung ngắn gọn gửi Chủ shop |

*Bảng 5.3: Khung báo cáo tiến độ tuần*

**b) Biên bản họp**

Các cuộc họp có quyết định (Sprint Planning, Sprint Review, họp thay đổi phạm vi, họp xử lý rủi ro mức Cao) đều lập biên bản. Biên bản ghi: thời gian, thành phần tham dự, nội dung thảo luận, quyết định, hành động tiếp theo, người phụ trách và hạn hoàn thành. Biên bản được lưu trên Email nhóm và đính kèm liên kết Trello/GitHub liên quan. Đối với UAT và nghiệm thu, biên bản nghiệm thu (sản phẩm bàn giao của gói WBS 6.4) là căn cứ bàn giao chính thức.

Việc duy trì báo cáo tuần và biên bản họp tạo vòng phản hồi khép kín: thông tin từ thực thi được chuyển thành quyết định của PO/Sponsor, rồi cập nhật lại backlog và kế hoạch nguồn lực, giảm nguy cơ mở rộng phạm vi không kiểm soát (scope creep) đã được cảnh báo khi xác định phạm vi tại Chương 3.

**5.2. Quản lý rủi ro**

Quản lý rủi ro trong dự án HOALYLY.vn được gắn với gói công việc WBS 1.2 (Quản lý rủi ro) và hoạt động giám sát liên tục tại WBS 1.3. Mục tiêu là nhận diện sớm các yếu tố có thể làm trễ tiến độ cam kết 4 tháng (16 tuần, hạn hoàn thành 30/11/2026 theo mục 2.1), vượt trần ngân sách 50.000.000 VND hoặc vượt xa dự toán 33.990.000 VND, suy giảm chất lượng (tốc độ tải, bảo mật, tương thích) hoặc ảnh hưởng vận hành cửa hàng sau triển khai.

**5.2.1. Xác định rủi ro**

Danh mục rủi ro được xây dựng từ các ràng buộc và giả định tại Project Charter (mục 2.1), đặc thù ngành hoa tươi (vòng đời ngắn, cao điểm lễ), phạm vi loại trừ (không phát triển ứng dụng di động, không tích hợp thanh toán thẻ quốc tế), lựa chọn công nghệ .NET/SQL Server, cũng như các điểm đã ghi nhận trong kiểm thử và review mã nguồn (validation form, tối ưu truy vấn, xử lý exception còn thiếu ở một số API).

| Mã | Rủi ro | Mô tả gắn với bối cảnh dự án | Nguồn / giai đoạn dễ phát sinh |
| :---- | :---- | :---- | :---- |
| R01 | Trễ tiến độ | Công việc trên đường găng (Backend, Frontend, Kiểm thử) kéo dài vượt ước lượng ngày công trong WBS | Phân tích, thiết kế, phát triển, kiểm thử |
| R02 | Vượt ngân sách | Chi phí phát sinh ngoài dự toán 33.990.000 VND (nhân công, hosting, phát sinh tính năng), có nguy cơ tiến sát hoặc vượt trần 50.000.000 VND | Toàn dự án, đặc biệt khi phạm vi thay đổi |
| R03 | Lỗi kỹ thuật / tích hợp | Lỗi tích hợp thanh toán VNPAY/QR, Entity Framework/SQL Server, hoặc lỗi module giỏ hàng, đơn hàng, tồn kho | Sprint 2-3 (lõi và nâng cao) và giai đoạn kiểm thử |
| R04 | Thay đổi yêu cầu (scope creep) | Chủ shop bổ sung tính năng ngoài phạm vi đã chốt (ví dụ yêu cầu gần với ứng dụng di động hoặc cổng thanh toán thẻ quốc tế đã loại trừ) | Phân tích yêu cầu và các Sprint Review |
| R05 | Mất dữ liệu | Mất hoặc hỏng dữ liệu sản phẩm, đơn hàng, khách hàng trên SQL Server (môi trường phát triển, staging hoặc production) | Phát triển, triển khai, vận hành sau bàn giao |
| R06 | Nhân sự nghỉ / giảm sẵn sàng | Thành viên đội (Dev, Designer, Tester) hoặc PO không dành đủ thời gian theo kế hoạch huy động mục 4.2.2 | Toàn dự án |
| R07 | Rủi ro bảo mật | Lỗ hổng XSS/SQL Injection/CSRF, lộ thông tin khách hàng hoặc sự cố tài khoản Admin | Phát triển xác thực/phân quyền; trước triển khai chính thức |
| R08 | Sự cố hạ tầng hosting/domain | Nhà cung cấp gián đoạn dịch vụ, cấu hình Windows Hosting/SQL Server không đúng cam kết (liên quan giả định ổn định hạ tầng tại mục 2.1) | Triển khai và vận hành |
| R09 | Chất lượng UX/hiệu năng không đạt | Tốc độ tải vượt quá ngưỡng 3 giây hoặc trải nghiệm đặt hàng kém trên mobile, ảnh hưởng khả năng xử lý đơn và chuyển đổi | Kiểm thử hệ thống, tối ưu trước bàn giao |

*Bảng 5.4: Danh mục rủi ro dự án HOALYLY.vn*

**5.2.2. Phân tích định tính rủi ro**

Phân tích định tính dùng ma trận Xác suất - Tác động với thang điểm 1 đến 5. Mức rủi ro = Xác suất x Tác động. Quy ước mức độ: Thấp (1-6), Trung bình (7-12), Cao (13-25).

Thang đánh giá:

| Điểm | Xác suất | Tác động đến mục tiêu (tiến độ / chi phí / chất lượng) |
| :---- | :---- | :---- |
| 1 | Rất thấp | Ảnh hưởng nhỏ, xử lý trong nội bộ Sprint |
| 2 | Thấp | Chậm vài ngày hoặc chi phí nhỏ trong quỹ dự phòng |
| 3 | Trung bình | Ảnh hưởng một mốc (milestone) hoặc module quan trọng |
| 4 | Cao | Nguy cơ lỡ hạn bàn giao hoặc vượt ngưỡng chi phí cần Chủ shop duyệt |
| 5 | Rất cao | Đe dọa thất bại mục tiêu SMART hoặc ngưng vận hành website |

*Bảng 5.5: Thang điểm xác suất và tác động*

Kết quả đánh giá rủi ro:

| Mã | Xác suất | Tác động | Điểm | Mức độ | Ưu tiên giám sát |
| :---- | :---- | :---- | :---- | :---- | :---- |
| R01 | 4 | 4 | 16 | Cao | Có |
| R02 | 3 | 4 | 12 | Trung bình | Có |
| R03 | 4 | 4 | 16 | Cao | Có |
| R04 | 4 | 3 | 12 | Trung bình | Có |
| R05 | 2 | 5 | 10 | Trung bình | Có |
| R06 | 3 | 4 | 12 | Trung bình | Có |
| R07 | 3 | 5 | 15 | Cao | Có |
| R08 | 2 | 4 | 8 | Trung bình | Theo sự kiện |
| R09 | 3 | 3 | 9 | Trung bình | Có |

*Bảng 5.6: Đánh giá định tính rủi ro*

Nhóm rủi ro Cao cần ưu tiên điều hành trong họp tuần gồm R01 (tiến độ), R03 (lỗi kỹ thuật/tích hợp) và R07 (bảo mật). Các rủi ro Trung bình được theo dõi kèm chỉ số chi phí (bảng 4.4) và phản hồi Sprint Review.

Ma trận Xác suất - Tác động (tóm tắt vị trí):

|  | Tác động 1 | Tác động 2 | Tác động 3 | Tác động 4 | Tác động 5 |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Xác suất 5 |  |  |  |  |  |
| Xác suất 4 |  |  | R04 | R01, R03 |  |
| Xác suất 3 |  |  | R09 | R02, R06 | R07 |
| Xác suất 2 |  |  |  | R08 | R05 |
| Xác suất 1 |  |  |  |  |  |

*Bảng 5.7: Ma trận xác suất - tác động*

**5.2.3. Kế hoạch ứng phó rủi ro**

Chiến lược ứng phó được chọn theo mức độ và khả năng kiểm soát của nhóm: Giảm thiểu (Mitigate) là ưu tiên với hầu hết rủi ro kỹ thuật và tiến độ; Chuyển giao (Transfer) áp dụng một phần với hạ tầng thuê ngoài; Chấp nhận (Accept) chỉ với phần dư còn lại sau khi đã có dự phòng 10% (3.090.000 VND) và kiểm soát chênh lệch chi phí theo bảng 4.4.

| Mã | Chiến lược | Hành động ứng phó cụ thể | Người chịu trách nhiệm | Dấu hiệu cảnh báo sớm |
| :---- | :---- | :---- | :---- | :---- |
| R01 | Giảm thiểu | Ưu tiên công việc trên đường găng; chia nhỏ sản phẩm bàn giao theo Sprint 1-5 tại mục 2.4; họp standup hàng ngày để gỡ rào cản; tái phân bổ Dev khi một nhánh Frontend/Backend chậm | PM, Dev | Số việc hoàn thành thấp hơn kế hoạch Sprint trong hai ngày liên tiếp |
| R02 | Giảm thiểu / Chấp nhận có kiểm soát | Bám dự toán và quỹ dự phòng 3.090.000 VND; phê duyệt chi theo ngưỡng 1.000.000 VND; nếu chênh lệch >10% thì thu hẹp phạm vi hoặc xin Chủ shop điều chỉnh ngân sách theo bảng 4.4 | PM, Chủ shop | Chi tiêu tuần vượt kế hoạch giai đoạn tương ứng tại mục 4.1.2 |
| R03 | Giảm thiểu | Tích hợp thanh toán và module lõi sớm (Sprint 2-3); unit/integration test; dùng Postman kiểm API; sửa lỗi mức Cao trước khi merge vào nhánh develop | Dev, Tester | Lỗi mở mức Cao chưa đóng cuối Sprint |
| R04 | Giảm thiểu | Chốt phạm vi bao gồm/không bao gồm tại Charter và WBS; mọi yêu cầu mới đưa vào Product Backlog để PO ưu tiên; đánh giá tác động tới lịch và chi phí trước khi nhận vào Sprint | PO, PM | Số yêu cầu mới ngoài backlog đã chốt tăng đột biến sau Sprint Review |
| R05 | Giảm thiểu | Sao lưu SQL Server định kỳ; kiểm tra phục hồi dữ liệu trước triển khai chính thức; hạn chế thao tác trực tiếp trên production; phân quyền Admin chặt | Dev, PM | Lỗi ghi/đọc dữ liệu hoặc thiếu bản sao lưu gần nhất |
| R06 | Giảm thiểu | Phân công rõ theo bảng nhân sự mục 2.4; tài liệu hóa thiết kế cơ sở dữ liệu và module quan trọng; review chéo để giảm phụ thuộc một người; PM điều chỉnh lịch huy động theo mục 4.2.2 | PM | Thành viên báo giảm thời gian tham gia hoặc vắng họp liên tiếp |
| R07 | Giảm thiểu | Áp dụng HTTPS/SSL; phòng chống XSS, CSRF và SQL Injection theo thực hành ASP.NET MVC và Entity Framework; review bảo mật trước triển khai; hoàn thiện xử lý exception và kiểm thử bảo mật cơ bản trước khi đưa lên môi trường thật | Dev, Tester | Phát hiện lỗ hổng trong review/test hoặc cấu hình SSL chưa hoàn tất |
| R08 | Chuyển giao / Giảm thiểu | Chọn nhà cung cấp Windows Hosting hỗ trợ ASP.NET MVC và SQL Server theo dự toán mục 4.1.1; giữ liên hệ hỗ trợ bằng Email; có checklist cấu hình môi trường (WBS 7.1) | PM, Dev | Website gián đoạn hoặc lỗi kết nối cơ sở dữ liệu sau khi triển khai |
| R09 | Giảm thiểu | Theo dõi PageSpeed/LCP (duy trì LCP trong ngưỡng an toàn; kết quả đo ở môi trường phát triển đã đạt 2.3 giây); tối ưu truy vấn danh sách sản phẩm; kiểm thử tương thích đa trình duyệt trước bàn giao | Dev, Tester, Designer | Hiệu năng giảm hoặc lỗi giao diện responsive trên mobile trong kiểm thử hồi quy |

*Bảng 5.8: Kế hoạch ứng phó rủi ro*

Các hành động trên tận dụng sẵn cơ chế đã có của dự án: mô hình Agile nhận thay đổi có kiểm soát, quỹ dự phòng 10%, giám sát đường găng, quy trình code review, kế hoạch kiểm thử (đơn vị, tích hợp, hệ thống, UAT) và tiêu chuẩn chất lượng về bảo mật, tốc độ tải, UX/UI.

**5.2.4. Giám sát rủi ro**

Giám sát rủi ro diễn ra liên tục trong nhóm tiến trình Giám sát và kiểm soát, không chỉ thực hiện một lần ở giai đoạn lập kế hoạch.

Cơ chế giám sát cụ thể:

1. Rà soát danh mục rủi ro trong họp tuần và cuối mỗi Sprint: cập nhật điểm xác suất/tác động, trạng thái (Mở / Đang xử lý / Đã đóng / Phát sinh mới).
2. Gắn rủi ro Cao (R01, R03, R07) vào báo cáo tiến độ tuần gửi Chủ shop.
3. Khi có sự kiện kích hoạt như chậm đường găng, lỗi tích hợp thanh toán, hoặc đề xuất thay đổi phạm vi lớn, PM triệu tập họp ngắn, ghi biên bản và cập nhật Trello/GitHub tương ứng.
4. Sau triển khai production, duy trì theo dõi R05, R07, R08 trong giai đoạn hỗ trợ 1-2 tuần (WBS 7.4), vì đây là lúc dữ liệu thật và giao dịch khách hàng bắt đầu phát sinh.
5. Mọi rủi ro đã đóng vẫn được lưu trong sổ đăng ký rủi ro để phục vụ bàn giao; các hướng mở rộng sau này (ứng dụng di động, thanh toán thẻ quốc tế) không đưa vào phạm vi hiện tại vì đã được loại trừ khi xác định phạm vi.

Mẫu theo dõi nhanh trong sổ đăng ký rủi ro:

| Mã | Mức hiện tại | Trạng thái | Hành động đang triển khai | Ngày rà soát gần nhất | Ghi chú |
| :---- | :---- | :---- | :---- | :---- | :---- |
| R01 | Cao | Đang xử lý | Ưu tiên các gói Backend trên đường găng; họp standup hàng ngày | Cuối tuần báo cáo | Theo dõi sát trước mốc M3 |
| R03 | Cao | Đang xử lý | Bổ sung test tích hợp thanh toán VNPAY/QR trong Sprint 3 | Cuối Sprint Review | Chỉ đóng khi hết lỗi mức Cao |
| R07 | Cao | Mở | Review bảo mật và hoàn tất SSL trước triển khai | Họp tuần | Gắn với checklist WBS 7.1 |

*Bảng 5.9: Mẫu cập nhật giám sát rủi ro*

**Kết luận chương 5**

Chương 5 đã thiết lập kế hoạch truyền thông gắn với các bên liên quan và ma trận RACI, xác định bộ công cụ Email, Zalo, Google Meet, Trello, GitHub cùng chế độ báo cáo tuần và biên bản họp. Đồng thời, chương đã xây dựng danh mục rủi ro phù hợp thực tiễn dự án HOALYLY.vn, đánh giá định tính bằng ma trận xác suất - tác động, đề xuất chiến lược ứng phó và cơ chế giám sát định kỳ. Các nội dung này bổ sung lớp kiểm soát cho phạm vi, tiến độ, chi phí và chất lượng đã trình bày ở các chương trước, giúp dự án duy trì sự thống nhất thông tin và chủ động trước biến động trong quá trình triển khai website trên nền tảng .NET.
