**CHƯƠNG 2: LẬP KẾ HOẠCH THỰC HIỆN QUẢN LÝ DỰ ÁN**

**2.1. Đề cương dự án (Project Charter)**

Đề cương dự án là tài liệu quan trọng đầu tiên, đánh dấu sự khởi tạo chính thức của dự án. Nó cung cấp cái nhìn tổng quan về mục tiêu, phạm vi và các bên liên quan, là cơ sở để các thành viên trong nhóm và ban lãnh đạo cửa hàng HOALYLY có sự thống nhất ngay từ đầu.

Mục tiêu (SMART):

Dự án hướng đến mục tiêu xây dựng và triển khai thành công website thương mại điện tử HOALYLY.vn, đáp ứng các tiêu chí SMART:

\- Specific (Cụ thể): Xây dựng website bán hoa tươi trực tuyến với đầy đủ các chức năng: trưng bày sản phẩm, quản lý giỏ hàng, thanh toán, quản lý đơn hàng và kho, tích hợp chatbot tư vấn.

\- Measurable (Đo lường được):  
  \+ Hoàn thành và bàn giao website trong vòng 4 tháng (16 tuần) kể từ khi dự án khởi động.  
  \+ Tổng chi phí đầu tư (không bao gồm duy trì hàng tháng) không vượt quá 50.000.000 VND.  
  \+ Hệ thống có khả năng xử lý ổn định 100 đơn hàng/ngày trong giờ cao điểm.

\- Achievable (Khả thi): Với đội ngũ phát triển có kinh nghiệm và việc lựa chọn công nghệ phù hợp (.NET) cùng nguồn lực tài chính được duyệt, mục tiêu là hoàn toàn khả thi.

\- Relevant (Liên quan): Dự án giải quyết trực tiếp các bài toán cấp bách của cửa hàng HOALYLY như quản lý tồn kho thủ công, nhầm lẫn đơn hàng, giúp số hóa toàn diện hoạt động kinh doanh.

\- Time-bound (Ràng buộc thời gian): Thời gian hoàn thành dự án là ngày 30/11/2026.

Yêu cầu chức năng và phi chức năng:

\- Chức năng (Functional Requirements): Hệ thống phải đáp ứng 23 yêu cầu đã được khảo sát, bao gồm 18 yêu cầu chức năng cốt lõi (hiển thị sản phẩm, tìm kiếm, đặt hàng hẹn giờ, viết thiệp, quản lý giỏ hàng, thanh toán, quản lý đơn hàng, quản lý kho, chatbot...) và 5 yêu cầu phi chức năng.

\- Phi chức năng (Non-functional Requirements):  
  \+ Hiệu năng: Tốc độ tải trang trung bình dưới 3 giây. Hệ thống hỗ trợ đồng thời tối thiểu 500 người dùng truy cập.  
  \+ Bảo mật: Đảm bảo an toàn cho dữ liệu khách hàng và giao dịch thanh toán, sử dụng giao thức HTTPS và cơ chế xác thực an toàn.  
  \+ Khả dụng: Website hoạt động ổn định 99.9% thời gian.  
  \+ Khả năng mở rộng: Kiến trúc hệ thống cho phép dễ dàng nâng cấp, bổ sung tính năng trong tương lai.  
  \+ Trải nghiệm người dùng: Giao diện thân thiện, dễ sử dụng, tối ưu trên cả máy tính và thiết bị di động (Responsive).

Ràng buộc (Constraints):

\- Thời gian: Dự án phải được hoàn thành trong vòng 4 tháng để kịp ra mắt vào dịp cuối năm.  
\- Ngân sách: Tổng chi phí phát triển và triển khai ban đầu giới hạn ở mức 50 triệu VND, bao gồm chi phí thiết kế, lập trình, mua tên miền và hosting cho năm đầu tiên.  
\- Nhân lực: Đội ngũ phát triển lõi giới hạn từ 3-4 người (bao gồm 1 Project Manager, 1 Developer chính, 1 Developer phụ trợ và 1 Tester).  
\- Công nghệ: Bắt buộc sử dụng hệ sinh thái .NET (ASP.NET MVC, C\#, SQL Server) và tuân thủ các quy chuẩn về thiết kế UI/UX đã được duyệt.

Giả định (Assumptions):

\- Nguồn lực của cửa hàng HOALYLY (đặc biệt là chủ shop và nhân viên kho) sẵn sàng hợp tác, cung cấp đầy đủ thông tin và dành thời gian cho quá trình khảo sát, kiểm thử và đào tạo.  
\- Khách hàng mục tiêu của shop đã quen thuộc và sẵn sàng với việc mua sắm trực tuyến.  
\- Các nhà cung cấp dịch vụ hosting và tên miền cung cấp dịch vụ ổn định theo đúng cam kết.  
\- Không có thay đổi lớn về chính sách pháp lý ảnh hưởng đến hoạt động kinh doanh thương mại điện tử trong thời gian triển khai dự án.

**2.2. Xác định các bên liên quan (Stakeholders)**

Việc xác định rõ ràng các bên liên quan và vai trò của họ là yếu tố then chốt để đảm bảo dòng chảy thông tin và sự phối hợp nhịp nhàng trong suốt vòng đời dự án. Nhóm các bên liên quan chính của dự án HOALYLY.vn bao gồm:

1\. Chủ cửa hàng HOALYLY: Người đại diện, là nhà tài trợ (Sponsor) và là người quyết định cuối cùng (Accountable) cho dự án.  
2\. Quản lý dự án (Project Manager): Người chịu trách nhiệm điều phối, giám sát tiến độ và đảm bảo dự án hoàn thành đúng mục tiêu.  
3\. Đội ngũ phát triển (Development Team): Nhóm kỹ sư phần mềm chịu trách nhiệm hiện thực hóa các yêu cầu thành sản phẩm.  
4\. Khách hàng của shop: Người dùng cuối của sản phẩm, đối tượng chính mà website hướng tới phục vụ.  
5\. Nhân viên cửa hàng: Người sẽ sử dụng hệ thống quản trị (Admin) để vận hành shop hàng ngày.  
6\. Nhà cung cấp dịch vụ (Hosting, Domain): Đối tác cung cấp hạ tầng kỹ thuật để website hoạt động trên môi trường Internet.

Ma trận RACI (Responsible, Accountable, Consulted, Informed):

Ma trận RACI giúp phân định rõ trách nhiệm của từng bên trong các hoạt động chính của dự án, tránh tình trạng chồng chéo hoặc bỏ sót công việc.

Bảng ma trận RACI:

| Hoạt động | Chủ shop (Sponsor) | Quản lý dự án (PM) | Đội phát triển (Dev) | Khách hàng | Nhân viên shop |
| ----- | ----- | ----- | ----- | ----- | ----- |
| Phê duyệt Đề cương dự án | A | R | \- | \- | \- |
| Xác định yêu cầu chi tiết | C | A | R | C | C |
| Thiết kế kiến trúc và Giao diện | I | A | R | \- | C |
| Phát triển (Lập trình) | I | C | R | \- | \- |
| Kiểm thử và Đánh giá | A | R | R | C | C |
| Triển khai lên Hosting | I | R | R | \- | \- |
| Đào tạo người dùng | A | R | R | \- | C |
| Nghiệm thu và Bàn giao | A | R | R | \- | I |

Ghi chú:

* R (Responsible): Người trực tiếp thực hiện công việc.  
* A (Accountable): Người chịu trách nhiệm cuối cùng và phê duyệt kết quả.  
* C (Consulted): Người được tham vấn, đóng góp ý kiến.  
* I (Informed): Người được thông báo về tiến độ hoặc kết quả.

**2.3. Lựa chọn mô hình phát triển**

Dự án HOALYLY.vn, với đặc thù yêu cầu nghiệp vụ có thể thay đổi trong quá trình phát triển và mong muốn sớm có sản phẩm để thử nghiệm, sẽ áp dụng mô hình phát triển Agile (cụ thể là Scrum).

Lý do lựa chọn:

\- Linh hoạt: Cho phép tiếp nhận và điều chỉnh yêu cầu từ phía chủ shop một cách nhanh chóng mà không làm đổ vỡ toàn bộ kế hoạch, điều mà mô hình truyền thống khó đáp ứng.  
\- Tăng cường tương tác: Agile đề cao sự hợp tác thường xuyên giữa nhóm phát triển và khách hàng (chủ shop). Các cuộc họp hàng tuần giúp đảm bảo sản phẩm cuối cùng đúng với kỳ vọng.  
\- Giảm thiểu rủi ro: Việc phát hành sản phẩm theo từng giai đoạn nhỏ giúp sớm phát hiện ra các vấn đề về kỹ thuật hoặc nghiệp vụ để có hướng xử lý kịp thời.  
\- Phù hợp với quy mô: Với một dự án có đội ngũ nhỏ (dưới 10 người), Scrum là một lựa chọn tối ưu, dễ dàng áp dụng và quản lý.

Vai trò trong dự án theo Scrum:

\- Product Owner (PO): Chủ cửa hàng HOALYLY hoặc người đại diện, chịu trách nhiệm xác định và ưu tiên các chức năng của website (Product Backlog) để đảm bảo giá trị kinh doanh cao nhất.  
\- Scrum Master: Quản lý dự án, chịu trách nhiệm đảm bảo nhóm phát triển tuân thủ đúng quy trình Scrum, loại bỏ các rào cản và hỗ trợ nhóm tập trung vào công việc.  
\- Development Team: Bao gồm lập trình viên, chuyên viên kiểm thử, chịu trách nhiệm biến các yêu cầu ưu tiên thành sản phẩm hoàn chỉnh trong mỗi Sprint.

**2.4. Kế hoạch nhân sự và phân công**

Để đảm bảo tiến độ và chất lượng, dự án sẽ được phân công cho các thành viên cụ thể với các mảng công việc rõ ràng. Mức độ hoàn thành được đánh giá dựa trên kết quả của từng Sprint.

Bảng kế hoạch phân công nhân sự:

| Tên thành viên | Vai trò | Công việc đảm nhận | Kỹ năng/Yêu cầu |
| ----- | ----- | ----- | ----- |
| Nguyễn Văn A | Project Manager / Scrum Master | Lập kế hoạch tổng thể; quản lý tiến độ, rủi ro và ngân sách; điều phối nhóm; tổ chức các cuộc họp Scrum; báo cáo tiến độ cho chủ shop. | Có chứng chỉ PMP hoặc kinh nghiệm tương đương; thành thạo Agile/Scrum; kỹ năng quản lý dự án và giao tiếp tốt. |
| Trần Thị B | Senior .NET Developer | Phân tích và thiết kế kiến trúc hệ thống; xây dựng các module quan trọng (Thanh toán, Quản lý kho); thiết kế cơ sở dữ liệu; tích hợp API. | Thành thạo C\#, ASP.NET MVC, Entity Framework, SQL Server; có kinh nghiệm thiết kế API và tối ưu hệ thống. |
| Lê Văn C | Full-stack Developer | Phát triển giao diện Frontend (HTML, CSS, JavaScript, Bootstrap); xây dựng các chức năng như Giỏ hàng, Quản lý sản phẩm, Quản lý đơn hàng; hỗ trợ lập trình Backend. | Thành thạo HTML5, CSS3, JavaScript, Bootstrap; có kiến thức về C\#, ASP.NET MVC và SQL Server. |
| Phạm Thị D | Tester / QA | Lập kế hoạch kiểm thử; xây dựng test case; kiểm thử chức năng, hiệu năng và bảo mật; ghi nhận lỗi; theo dõi quá trình sửa lỗi và xác nhận kết quả. | Có kiến thức về kiểm thử phần mềm, viết test case; hiểu quy trình Agile; cẩn thận và có tư duy phân tích. |
| Chủ cửa hàng | Product Owner | Cung cấp yêu cầu nghiệp vụ; xác định mức độ ưu tiên của các tính năng; phản hồi kết quả sau mỗi Sprint; nghiệm thu và phê duyệt sản phẩm. | Hiểu rõ quy trình kinh doanh của cửa hàng hoa; có khả năng đưa ra quyết định về nghiệp vụ và định hướng phát triển sản phẩm. |

Tiến độ dự kiến:

\- Sprint 1 \- Nền tảng (Tuần 1-3): Xây dựng kiến trúc CSDL, thiết lập dự án, giao diện chính, quản lý sản phẩm/danh mục.  
\- Sprint 2 \- Lõi (Tuần 4-6): Xây dựng giỏ hàng, đặt hàng, thanh toán (mô phỏng), quản lý đơn hàng.  
\- Sprint 3 \- Nâng cao (Tuần 7-9): Tích hợp thanh toán thực tế (QR Code), chức năng hẹn giờ, thiệp, cảnh báo tồn kho.  
\- Sprint 4 \- Hoàn thiện (Tuần 10-12): Xây dựng chatbot, trang Admin Dashboard, tối ưu hiệu năng.  
\- Sprint 5 \- Kiểm thử và Sẵn sàng (Tuần 13-16): Kiểm thử tổng thể, sửa lỗi, triển khai lên hosting staging, đào tạo nhân viên, triển khai chính thức và bàn giao.

Kết luận:

Chương 2 đã trình bày chi tiết kế hoạch thực hiện quản lý dự án cho việc xây dựng website HOALYLY.vn. Các nội dung bao gồm đề cương dự án với mục tiêu SMART cụ thể, các ràng buộc và giả định quan trọng; việc xác định các bên liên quan thông qua ma trận RACI giúp làm rõ trách nhiệm của từng cá nhân/tổ chức; quyết định lựa chọn mô hình Agile/Scrum cho phép dự án thích ứng linh hoạt với thay đổi; và kế hoạch phân công nhân sự chi tiết cho từng vị trí. Với những chuẩn bị kỹ lưỡng này, dự án có nền tảng vững chắc để bước vào giai đoạn thực thi.

*Tài liệu tham khảo*

1\. SMART Criteria & Project Charter:  
    Open Library, "Project Management and Event Planning for Office Administrators". Available at: [https://openlibrary-repo.ecampusontario.ca/jspui/bitstream/123456789/2248/1/Project-Management-and-Event-Planning-for-Office-Administrators-1712935833.pdf\](https://openlibrary-repo.ecampusontario.ca/jspui/bitstream/123456789/2248/1/Project-Management-and-Event-Planning-for-Office-Administrators-1712935833.pdf](https://openlibrary-repo.ecampusontario.ca/jspui/bitstream/123456789/2248/1/Project-Management-and-Event-Planning-for-Office-Administrators-1712935833.pdf]\(https://openlibrary-repo.ecampusontario.ca/jspui/bitstream/123456789/2248/1/Project-Management-and-Event-Planning-for-Office-Administrators-1712935833.pdf)  
    Project Insight, "Charting the Right Course: Critical Information for Project Charters". Available at: [https://projectinsight.com/blogs/project-insight-news/charting-the-right-course-critical-information-for-project-charters\](https://projectinsight.com/blogs/project-insight-news/charting-the-right-course-critical-information-for-project-charters](https://projectinsight.com/blogs/project-insight-news/charting-the-right-course-critical-information-for-project-charters]\(https://projectinsight.com/blogs/project-insight-news/charting-the-right-course-critical-information-for-project-charters)

2\. PMBOK Guide (Project Management Body of Knowledge):  
    PMI Slovenija, "PMBOK guide". Available at: [https://www.pmi-slo.org/en/pmi-certifications/pmbok-guide/\](https://www.pmi-slo.org/en/pmi-certifications/pmbok-guide/](https://www.pmi-slo.org/en/pmi-certifications/pmbok-guide/]\(https://www.pmi-slo.org/en/pmi-certifications/pmbok-guide/)  
    PMI Norway Chapter, "Changes from PMBOK®6 to PMBOK®7". Available at: [https://pmi-no.org/calendar?eventId=13985\&month=8\&year=2022](https://pmi-no.org/calendar?eventId=13985&month=8&year=2022]\(https://pmi-no.org/calendar?eventId=13985&month=8&year=2022) 

3\. RACI Matrix (Stakeholder Responsibilities):  
    Flevy.com, "RACI Matrix Templates, Frameworks, & Toolkits". Available at: [https://flevy.com/topic/raci-matrix/question\](https://flevy.com/topic/raci-matrix/question](https://flevy.com/topic/raci-matrix/question]\(https://flevy.com/topic/raci-matrix/question)  
     Westlaw, "RACI Matrix | Practical Law". Available at: [https://content.next.westlaw.com/practical-law/document/Ieba4dbdfe7aa11ef8b11b9b0c07ab1f9/RACI-Matrix\](https://content.next.westlaw.com/practical-law/document/Ieba4dbdfe7aa11ef8b11b9b0c07ab1f9/RACI-Matrix](https://content.next.westlaw.com/practical-law/document/Ieba4dbdfe7aa11ef8b11b9b0c07ab1f9/RACI-Matrix]\(https://content.next.westlaw.com/practical-law/document/Ieba4dbdfe7aa11ef8b11b9b0c07ab1f9/RACI-Matrix)

4\. Agile/Scrum Development Methodology:  
    PMI (Project Management Institute), "Applying project methodology in agile development". Available at: [https://www.pmi.org/learning/library/applying-project-methodology-agile-development-6831\](https://www.pmi.org/learning/library/applying-project-methodology-agile-development-6831](https://www.pmi.org/learning/library/applying-project-methodology-agile-development-6831]\(https://www.pmi.org/learning/library/applying-project-methodology-agile-development-6831)  
    Wiley Online Library, "Project Management ToolBox, Second Edition \- Agile Project Execution". Available at: [https://onlinelibrary.wiley.com/doi/10.1002/9781119174820.ch11\](https://onlinelibrary.wiley.com/doi/10.1002/9781119174820.ch11](https://onlinelibrary.wiley.com/doi/10.1002/9781119174820.ch11]\(https://onlinelibrary.wiley.com/doi/10.1002/9781119174820.ch11)

5\. Project Planning:  
    Mosaic Projects, "Defining the Project Charter". Available at: [http://www.mosaicprojects.com.au/WhitePapers/WP1019\_Charter.pdf\](http://www.mosaicprojects.com.au/WhitePapers/WP1019\_Charter.pdf](http://www.mosaicprojects.com.au/WhitePapers/WP1019_Charter.pdf]\(http://www.mosaicprojects.com.au/WhitePapers/WP1019_Charter.pdf)

