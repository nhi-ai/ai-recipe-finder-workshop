---
title: "Event 1"
date: 2026-07-07
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch “AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY”

### Mục Đích Của Sự Kiện

-	Cập nhật các xu hướng thực tiễn về Cloud Computing và cách ứng dụng Generative AI (GenAI) vào môi trường doanh nghiệp.
-	Chia sẻ kinh nghiệm triển khai các giải pháp công nghệ, từ thiết kế kiến trúc hệ thống, xây dựng mô hình AI đa tác nhân (Multi-Agent) đến các phương pháp tăng cường bảo mật hạ tầng trên nền tảng đám mây.
-	Tạo cơ hội để cộng đồng công nghệ thông tin giao lưu, trao đổi kinh nghiệm, đồng thời định hướng các kỹ năng và kiến thức cần thiết cho đội ngũ kỹ sư trong bối cảnh AI ngày càng phát triển mạnh mẽ.


### Danh Sách Diễn Giả

-	**Nguyễn Gia Hưng** - Solutions Architect, AWS Vietnam (Founder FCAJ)
-	**Tinh Truong** - Platform Engineer, GoTymeX
-	**Anh Pham** - Cloud Consultant, G-AsiaPacific Vietnam
-	**Thinh Nguyen** - DevOps Engineer, FCAJ
-	**Uyển Lê, Thảo Nguyễn, Mai Nguyễn** - GenAI Engineers, VIB
-	**Duc Dao** - Solutions Architect, Cloud Kinetics
-	**Vy Lâm** - Senior Business Systems Analyst, VPBank


### Nội Dung Nổi Bật

####	Xu hướng nghề nghiệp trong kỷ nguyên AI:
Sự phát triển mạnh mẽ của AI đã rút ngắn thời gian và chi phí phát triển phần mềm, khiến nhu cầu xây dựng sản phẩm ngày càng gia tăng. Vì vậy, kỹ sư CNTT không chỉ cần kiến thức kỹ thuật mà còn phải hiểu yêu cầu nghiệp vụ, đồng thời sở hữu các dự án thực tế để chứng minh năng lực.
#### Quản lý ngữ cảnh khi làm việc với AI:
Một trong những yếu tố quyết định chất lượng phản hồi của mô hình AI là ngữ cảnh (context). Thay vì cung cấp lượng dữ liệu lớn từ nhiều nguồn, cần truyền vào những thông tin liên quan và có chọn lọc để giảm hiện tượng AI tạo ra nội dung không chính xác (hallucination).
####	Ứng dụng Amazon Q trong tự động hóa công việc:
Chương trình giới thiệu cách tận dụng Amazon Q như một AI Agent để hỗ trợ xử lý dữ liệu Excel, tạo báo cáo trực quan, tóm tắt nội dung cuộc họp và kết nối với các công cụ làm việc thông qua Model Context Protocol (MCP).
####	Giải pháp bảo mật với Amazon CloudFront:

Diễn giả trình bày cách sử dụng CloudFront nhằm phân phối lưu lượng truy cập hiệu quả, kết hợp cơ chế Flat-rate Pricing để hạn chế rủi ro phát sinh chi phí ngoài mong muốn. Ngoài ra, VPC Origin giúp kết nối trực tiếp đến hệ thống backend trong private subnet, giảm thiểu nguy cơ bị tấn công từ Internet.
####	Kinh nghiệm phát triển sản phẩm GenAI trong Hackathon:

Nhóm diễn giả chia sẻ quá trình xây dựng ứng dụng tạo giao diện người dùng bằng kiến trúc Serverless cùng nhiều AI Agent. Thay vì yêu cầu AI sinh lại toàn bộ giao diện sau mỗi lần chỉnh sửa, nhóm đã phát triển chức năng chỉnh sửa trực tiếp từng thành phần, giúp tiết kiệm tài nguyên và nâng cao hiệu quả phát triển.
####	Đảm bảo tính ổn định của mô hình LLM:

Buổi chia sẻ giải thích rằng kết quả của mô hình ngôn ngữ lớn vẫn có thể thay đổi ngay cả khi đặt Temperature bằng 0 do ảnh hưởng từ quá trình suy luận và phần cứng. Để giảm sai lệch, cần kết hợp nhiều giải pháp như JSON Mode, tự triển khai mô hình hoặc xây dựng hệ thống có khả năng xử lý các phản hồi bất thường.
####	Thiết kế hệ thống Multi-Agent cho doanh nghiệp:

Nội dung cuối giới thiệu mô hình nhiều AI Agent phối hợp thực hiện các tác vụ khác nhau trong quy trình đánh giá tín dụng doanh nghiệp. Đồng thời nhấn mạnh các yêu cầu về bảo mật như chống Prompt Injection, lưu nhật ký hoạt động (Audit Trail), quản lý API Key và kiểm soát các rủi ro liên quan đến MCP.


### Những Gì Học Được

- **Tư duy phát triển theo nhu cầu thực tế:** 
Nhận thấy việc xây dựng sản phẩm cần bắt đầu từ bài toán của doanh nghiệp và trải nghiệm người dùng thay vì chỉ tập trung vào công nghệ. Việc chia nhỏ chức năng cho từng AI Agent cũng giúp hệ thống hoạt động hiệu quả và dễ bảo trì hơn.

- **Kiến thức về kiến trúc và bảo mật:** 
Hiểu rõ hơn cách triển khai Amazon CloudFront kết hợp VPC Origin để bảo vệ hệ thống backend, hạn chế việc truy cập trực tiếp từ Internet và tăng cường an toàn cho ứng dụng.

- **Quản lý rủi ro khi ứng dụng AI (AI Risk Management):** 
Nhận thức được rằng AI luôn tồn tại khả năng trả lời sai hoặc không đúng định dạng. Vì vậy, cần xây dựng cơ chế kiểm tra, xử lý lỗi và dự phòng thay vì phụ thuộc hoàn toàn vào kết quả của mô hình.


### Ứng Dụng Vào Công Việc

-	Áp dụng kiến trúc Multi-Agent: Phân chia các Agent phụ trách từng nhiệm vụ như phân tích sở thích người dùng, đề xuất công thức và tính toán giá trị dinh dưỡng nhằm nâng cao độ chính xác của hệ thống. 
-	Tối ưu quy trình tạo nội dung: Chỉ cập nhật phần cần chỉnh sửa thay vì sinh lại toàn bộ kết quả, từ đó tiết kiệm thời gian xử lý và chi phí sử dụng AI. 
-	Thiết lập các tham số phù hợp: Sử dụng Temperature thấp kết hợp JSON Mode để đảm bảo dữ liệu đầu ra có cấu trúc ổn định và dễ xử lý.
-	Tăng cường bảo mật: Sử dụng CloudFront kết hợp VPC Origin, đồng thời chỉ cung cấp những thông tin cần thiết vào prompt để giảm nguy cơ Prompt Injection và hạn chế AI tiếp cận dữ liệu không liên quan. 


### Trải nghiệm trong event

Sự kiện **“AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY”** mang đến cho em nhiều trải nghiệm thực tế và góc nhìn mới về việc ứng dụng AWS Cloud kết hợp Generative AI trong phát triển phần mềm hiện đại. Thông qua các nội dung chia sẻ, em hiểu rõ hơn cách xây dựng những hệ thống AI vừa hiệu quả, vừa đảm bảo tính ổn định và an toàn khi triển khai trong môi trường doanh nghiệp.

#### Học hỏi từ các diễn giả có chuyên môn cao

-	Các diễn giả đến từ AWS, VIB, GoTymeX và Cloud Kinetics đã chia sẻ nhiều kinh nghiệm thực tiễn trong quá trình phát triển và vận hành các hệ thống công nghệ quy mô lớn.
-	Những ví dụ thực tế như dự án Hackathon hay hệ thống đánh giá tín dụng doanh nghiệp giúp em hiểu rõ cách ứng dụng mô hình Multi-Agent để giải quyết các quy trình nghiệp vụ phức tạp.


#### Trải nghiệm kỹ thuật thực tế

-	Em có cơ hội tìm hiểu sâu hơn về nguyên lý hoạt động của LLM, nguyên nhân dẫn đến hiện tượng hallucination cũng như vai trò của Temperature và JSON Mode trong việc cải thiện chất lượng kết quả.
-	Các nội dung về Amazon CloudFront và VPC Origin giúp em hình dung rõ quy trình xây dựng hạ tầng bảo mật, giảm thiểu nguy cơ tấn công DDoS và kiểm soát chi phí khi hệ thống có lưu lượng truy cập lớn.
-	Ngoài ra, em còn được giới thiệu về Model Context Protocol (MCP) và các nguy cơ bảo mật như Prompt Injection hay MCP Attack, từ đó hiểu hơn về những thách thức khi tích hợp AI vào hệ thống doanh nghiệp.

#### Bài học rút ra
-	Việc phân chia hệ thống thành nhiều AI Agent chuyên biệt giúp tăng khả năng mở rộng, nâng cao hiệu quả xử lý và đơn giản hóa quá trình bảo trì.
-	AI chỉ nên được xem là công cụ hỗ trợ. Khi xây dựng ứng dụng thực tế, cần luôn chuẩn bị các phương án kiểm tra và xử lý khi AI tạo ra kết quả không chính xác hoặc không đúng định dạng.
-	Bảo mật phải được đặt lên hàng đầu trong các ứng dụng GenAI. Việc bảo vệ hạ tầng bằng CloudFront, VPC Origin cùng quy trình quản lý và luân chuyển API Key là những giải pháp cần thiết để đảm bảo an toàn cho hệ thống.

#### Một số hình ảnh khi tham gia sự kiện
* Thêm các hình ảnh của các bạn tại đây

![Event 1](/images/4-EventParticipated/image1.png)
![Event 1](/images/4-EventParticipated/image2.png)