### Day 21 - AI Ethics, Responsible AI, Luật AI

* Họ và tên: Ho Hoang Phuong Anh
* MSSV / mã học viên: 2A202602460
* Lớp: [Điền lớp]
* Ngành đã chọn: **HR / Tuyển dụng**


## 1. Industry Risk Snapshot

AI trong tuyển dụng có thể mang lại lợi ích cho cả ứng viên và HR. Với ứng viên, AI có thể hỗ trợ hoàn thiện CV và phát hiện những transferable skills mà ứng viên chưa nhận ra. Ví dụ, việc từng tổ chức một chuyến du lịch nhóm có thể thể hiện khả năng planning, coordination, budget management và problem solving. Với HR, AI có thể tự động lọc và phân loại số lượng lớn CV, giúp giảm các công việc lặp lại và tiết kiệm thời gian.

Tuy nhiên, AI cũng có thể hiểu sai thông tin, tạo bias hoặc suy luận dựa trên những dữ liệu không phù hợp. Nếu HR quá phụ thuộc vào điểm số AI, ứng viên có thể bị đánh giá sai và mất cơ hội việc làm
| Nội dung                                 | Đánh giá của tôi và lý do                                                                                                                                                                                                                                                                                                                                                                               |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **Những tác hại chính có thể xảy ra**    | AI có thể tạo hoặc tái tạo bias từ dữ liệu tuyển dụng lịch sử, khiến một số nhóm ứng viên bị đánh giá bất lợi. AI cũng có thể sử dụng những tín hiệu không thực sự liên quan đến năng lực công việc, dẫn đến đánh giá sai hoặc làm ứng viên mất cơ hội việc làm. Ngoài ra, việc xử lý dữ liệu cá nhân và việc recruiter quá phụ thuộc vào điểm số AI có thể tạo thêm rủi ro về privacy và over-reliance. |
| **Mức độ high-stakes**                   | **Cao.** Quyết định tuyển dụng có thể ảnh hưởng trực tiếp đến cơ hội việc làm, thu nhập và sự nghiệp của ứng viên. Một lỗi trong bước sàng lọc có thể khiến ứng viên không được tiếp tục trong quy trình tuyển dụng.                                                                                                                                                                                     |
| **Dữ liệu nhạy cảm có thể được sử dụng** | Hệ thống AI tuyển dụng có thể xử lý dữ liệu cá nhân như họ tên, thông tin liên hệ, học vấn, kinh nghiệm và lịch sử việc làm. Một số hệ thống còn có thể sử dụng dữ liệu từ video phỏng vấn như khuôn mặt, giọng nói hoặc các tín hiệu hành vi. Việc sử dụng những dữ liệu này cần được xem xét về tính cần thiết, quyền riêng tư và mức độ liên quan đến công việc.                                      |
| **Nhu cầu human review**                 | **Cao.** AI nên đóng vai trò hỗ trợ bằng cách sàng lọc, đưa ra điểm số hoặc cung cấp evidence, nhưng HR cần kiểm tra kết quả trước khi đưa ra quyết định ảnh hưởng đến ứng viên. Human review đặc biệt quan trọng khi AI đưa ra kết quả thấp, đề xuất loại ứng viên hoặc sử dụng những tín hiệu có khả năng tạo bias.                                                                                    |

---

## 2. Case study 1 — Amazon AI Recruiting Tool

### Brief Case

* **Tổ chức / sản phẩm AI:** Amazon — experimental AI recruiting tool
* **Thời gian, địa điểm / bối cảnh:** Amazon phát triển công cụ từ khoảng năm 2014 để hỗ trợ đánh giá CV cho các vị trí, trong đó có software developer và technical roles.
* **AI được dùng để làm gì:** Công cụ sử dụng machine learning để phân tích CV và chấm ứng viên theo thang điểm từ 1 đến 5, nhằm tự động hóa việc tìm kiếm ứng viên phù hợp.
* **Vấn đề hoặc sự kiện đáng chú ý:** Reuters đưa tin Amazon phát hiện hệ thống không đánh giá ứng viên theo hướng gender-neutral. Mô hình được huấn luyện trên dữ liệu CV trong khoảng 10 năm, trong đó phần lớn CV đến từ nam giới. Hệ thống đã học các pattern từ dữ liệu lịch sử và đánh giá bất lợi đối với một số CV có các từ liên quan đến phụ nữ. Reuters cũng đưa tin hệ thống hạ điểm CV có cụm từ như "women's" và hạ điểm ứng viên tốt nghiệp từ hai trường dành cho nữ. Amazon đã cố gắng chỉnh sửa hệ thống nhưng vẫn không đảm bảo rằng mô hình sẽ không tìm ra các pattern phân biệt đối xử khác.
* **Số liệu có nguồn:** Công cụ được xây dựng từ năm **2014** và sử dụng dữ liệu CV trong khoảng **10 năm** để tìm pattern tuyển dụng. Hệ thống chấm ứng viên theo thang **1–5 sao**. Reuters cho biết đến **2015**, Amazon nhận ra hệ thống không đánh giá các ứng viên technical roles theo hướng gender-neutral.
* **Nguồn:** Jeffrey Dastin, Reuters, *Amazon scraps secret AI recruiting tool that showed bias against women*, 10/10/2018.
* **Phân biệt bằng chứng và nhận định:** Nguồn xác nhận hệ thống học pattern từ dữ liệu tuyển dụng lịch sử và đánh giá bất lợi đối với một số tín hiệu liên quan đến phụ nữ. Từ case này, tôi nhận định rằng việc chỉ loại bỏ một trường dữ liệu trực tiếp như gender chưa đủ để loại bỏ bias, vì mô hình có thể học các proxy hoặc pattern gián tiếp khác.

### Harm Map Worksheet

| Trường                       | Phân tích của tôi                                                                                                                                                                                                                                                         |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **High-risk moment**         | AI sử dụng CV và dữ liệu tuyển dụng lịch sử để xếp hạng ứng viên trước khi recruiter quyết định ứng viên nào được tiếp tục.                                                                                                                                               |
| **Stakeholder bị ảnh hưởng** | Ứng viên, đặc biệt là những ứng viên nữ hoặc ứng viên có đặc điểm tương tự nhóm bị hệ thống đánh giá bất lợi; recruiter và tổ chức cũng bị ảnh hưởng bởi kết quả không công bằng.                                                                                         |
| **Failure mode**             | **Bias / fairness** — mô hình học lại bias từ dữ liệu lịch sử và sử dụng các pattern liên quan đến giới tính trong đánh giá CV.                                                                                                                                           |
| **Layer bắt đầu lỗi**        | **Model / Grounding.** Model học từ dữ liệu tuyển dụng lịch sử có sự mất cân bằng giới tính. Tuy nhiên, nguồn công khai không đủ để xác định chính xác kiến trúc kỹ thuật hoặc layer duy nhất bắt đầu lỗi.                                                                |
| **Harm xảy ra là gì?**       | Ứng viên có thể bị đánh giá thấp dựa trên các đặc điểm không liên quan trực tiếp đến khả năng thực hiện công việc và có thể mất cơ hội được tiếp tục trong quy trình tuyển dụng.                                                                                          |
| **Harm lens**                | **Opportunity loss + dignity loss / fairness concern**                                                                                                                                                                                                                    |
| **Severity**                 | **High** — vì kết quả có thể ảnh hưởng trực tiếp đến cơ hội việc làm.                                                                                                                                                                                                     |
| **Scale**                    | **Medium–High.** Công cụ được xây dựng để tự động hóa việc đánh giá số lượng lớn CV, nhưng nguồn công khai không cung cấp đủ dữ liệu để xác định chính xác số ứng viên bị ảnh hưởng.                                                                                      |
| **Probability**              | **Medium.** Case thực tế cho thấy bias có thể xuất hiện khi mô hình học từ dữ liệu lịch sử không cân bằng, nhưng không đủ dữ liệu để xác định xác suất xảy ra trong mọi hệ thống AI tuyển dụng.                                                                           |
| **Frequency**                | **Medium.** Đây là một failure mode có thể lặp lại khi hệ thống tiếp tục được huấn luyện hoặc đánh giá bằng dữ liệu lịch sử có bias. Tuy nhiên, không có dữ liệu đủ để định lượng tần suất.                                                                               |
| **Vì sao?**                  | Reuters cho biết mô hình được huấn luyện trên CV trong khoảng 10 năm, phần lớn đến từ nam giới, và hệ thống đã học các pattern khiến một số CV liên quan đến phụ nữ bị đánh giá thấp. Vì nguồn không cung cấp tỷ lệ ứng viên bị ảnh hưởng nên tôi không tự đặt phần trăm. |

---

## 3. Case study 2 — HireVue Facial Analysis

### Brief Case

* **Tổ chức / sản phẩm AI:** HireVue — AI-based hiring and video assessment platform
* **Thời gian, địa điểm / bối cảnh:** Năm 2019, EPIC filed a complaint với U.S. Federal Trade Commission liên quan đến việc HireVue sử dụng facial analysis và các thuật toán độc quyền trong đánh giá ứng viên. Năm 2021, HireVue thông báo dừng sử dụng facial analysis để đánh giá ứng viên.
* **AI được dùng để làm gì:** HireVue sử dụng video-based assessments và các thuật toán để hỗ trợ đánh giá ứng viên. Theo complaint của EPIC, hệ thống phân tích các đặc điểm như facial expressions, facial movements, intonation, inflection và các tín hiệu khác để đưa ra đánh giá về ứng viên.
* **Vấn đề hoặc sự kiện đáng chú ý:** EPIC cáo buộc rằng HireVue sử dụng các thuật toán opaque và dữ liệu biometric để đánh giá ứng viên, đồng thời đặt vấn đề về tính hợp lệ, tính minh bạch và nguy cơ bias. Năm 2021, HireVue thông báo sẽ ngừng dựa vào facial analysis để đánh giá ứng viên và cho biết công nghệ này "wasn't worth the concern".
* **Số liệu có nguồn:** Complaint của EPIC cho biết HireVue thực hiện đánh giá ứng viên cho **hơn 700 employers** và tuyên bố thu thập **hàng chục nghìn biometric data points** từ các cuộc phỏng vấn của ứng viên. Đây là các con số được nêu trong complaint của EPIC, không phải kết luận của FTC.
* **Nguồn:** Electronic Privacy Information Center (EPIC), *In re HireVue* và *HireVue, Facing FTC Complaint From EPIC, Halts Use of Facial Recognition*, 2019–2021.
* **Phân biệt bằng chứng và nhận định:** Nguồn xác nhận EPIC đã khiếu nại FTC và sau đó HireVue dừng facial analysis. Các cáo buộc về unfair/deceptive practices là nội dung của complaint; tôi không coi complaint là bằng chứng cho một kết luận pháp lý cuối cùng. Từ case này, tôi nhận định rằng dữ liệu như khuôn mặt và các tín hiệu hành vi cần được đánh giá về tính cần thiết và độ tin cậy trước khi sử dụng trong tuyển dụng.

### Harm Map Worksheet

| Trường                       | Phân tích của tôi                                                                                                                                                                                                                                      |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **High-risk moment**         | AI phân tích video hoặc các tín hiệu từ ứng viên để tạo đánh giá trong quá trình tuyển dụng.                                                                                                                                                           |
| **Stakeholder bị ảnh hưởng** | Ứng viên là stakeholder trực tiếp; recruiter và doanh nghiệp cũng bị ảnh hưởng nếu dựa vào một phương pháp đánh giá không đủ minh bạch hoặc không đáng tin cậy.                                                                                        |
| **Failure mode**             | **Privacy leak / Bias / Over-reliance.** Case cũng đặt ra vấn đề về việc sử dụng dữ liệu biometric và các thuật toán khó kiểm chứng.                                                                                                                   |
| **Layer bắt đầu lỗi**        | **Safety / Grounding.** Rủi ro liên quan đến việc thu thập và sử dụng dữ liệu, cũng như việc hệ thống dựa vào những tín hiệu chưa rõ mức độ phù hợp với năng lực công việc. Không đủ bằng chứng để khẳng định một layer kỹ thuật duy nhất.             |
| **Harm xảy ra là gì?**       | Ứng viên có thể mất quyền kiểm soát hoặc không hiểu đầy đủ cách dữ liệu của mình được sử dụng; nếu các tín hiệu được dùng để đánh giá không đáng tin cậy hoặc tạo bias, ứng viên có thể bị đánh giá bất lợi.                                           |
| **Harm lens**                | **Privacy loss + opportunity loss + dignity loss**                                                                                                                                                                                                     |
| **Severity**                 | **High** — vì dữ liệu biometric và kết quả đánh giá có thể liên quan trực tiếp đến cơ hội việc làm.                                                                                                                                                    |
| **Scale**                    | **High.** EPIC complaint cho biết HireVue cung cấp đánh giá cho hơn 700 employers và thu thập hàng chục nghìn biometric data points từ ứng viên. Tuy nhiên, đây là thông tin được nêu trong complaint và không cho biết chính xác số ứng viên bị harm. |
| **Probability**              | **Medium.** Có bằng chứng về tranh cãi và concern đối với phương pháp này, nhưng không có dữ liệu đủ để định lượng xác suất một ứng viên cụ thể bị ảnh hưởng.                                                                                          |
| **Frequency**                | **Medium.** Rủi ro có thể xuất hiện lặp lại nếu hệ thống sử dụng cùng loại dữ liệu và phương pháp đánh giá cho nhiều ứng viên.                                                                                                                         |
| **Vì sao?**                  | EPIC đặt vấn đề về việc sử dụng biometric data và secret algorithms trong đánh giá ứng viên. HireVue sau đó thông báo dừng facial analysis vào năm 2021. Tuy nhiên, tôi phân biệt rõ complaint của EPIC với một kết luận pháp lý đã được chứng minh.   |

---

## 4. Case study 3 — Unilever + HireVue

### Brief Case

* **Tổ chức / sản phẩm AI:** Unilever sử dụng HireVue trong quy trình tuyển dụng kết hợp với các công cụ đánh giá kỹ thuật số.
* **Thời gian, địa điểm / bối cảnh:** Unilever triển khai quy trình tuyển dụng kỹ thuật số trên quy mô quốc tế, với HireVue hỗ trợ recorded video interviews và assessment technology. Case study cho biết quy trình được triển khai tại **hơn 53 quốc gia** và nhiều ngôn ngữ.
* **AI được dùng để làm gì:** AI phân tích recorded interviews và hỗ trợ lọc ứng viên trong quy trình tuyển dụng. Theo case study, HireVue Assessments có thể phân tích phỏng vấn được ghi hình và lọc tới **80% candidate pool** để đưa các ứng viên phù hợp hơn vào các bước tiếp theo.
* **Vấn đề hoặc sự kiện đáng chú ý:** Case này cho thấy AI tuyển dụng có thể tạo ra giá trị khi được sử dụng để giảm công việc thủ công và hỗ trợ quy trình tuyển dụng ở quy mô lớn. Tuy nhiên, nó cũng cho thấy cần phân biệt giữa automation tạo hiệu quả và việc để AI tự quyết định tuyển dụng.
* **Số liệu có nguồn:** Case study của Unilever/HireVue báo cáo **hơn £1 triệu annual cost savings**, **90% reduction in time to hire**, **16% increase in new-hire diversity** và **hơn 50.000 giờ candidate time saved**. Quy trình được triển khai tại **hơn 53 quốc gia** và AI được sử dụng để lọc tới **80% candidate pool**.
* **Nguồn:** Oracle Marketplace, *Unilever + HireVue — Success Story*.
* **Phân biệt bằng chứng và nhận định:** Các số liệu trên là kết quả được báo cáo trong case study của Unilever/HireVue. Tôi sử dụng chúng để cho thấy potential benefit của AI recruitment, nhưng không coi các con số này là bằng chứng rằng mọi hệ thống AI tuyển dụng đều tạo ra cùng mức hiệu quả.

### Harm Map Worksheet

| Trường                       | Phân tích của tôi                                                                                                                                                                                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **High-risk moment**         | AI được sử dụng để lọc một phần lớn candidate pool trước khi ứng viên tiếp tục sang các bước đánh giá hoặc tuyển chọn tiếp theo.                                                                                                                                                              |
| **Stakeholder bị ảnh hưởng** | Ứng viên, recruiter và Unilever. Ứng viên có thể bị ảnh hưởng nếu hệ thống lọc sai; recruiter có thể bị ảnh hưởng nếu quá phụ thuộc vào recommendation của AI.                                                                                                                                |
| **Failure mode**             | **Over-reliance / Escalation failure.** Rủi ro chính tôi tập trung vào là con người có thể quá phụ thuộc vào automated filtering ở quy mô lớn và không kiểm tra đầy đủ các trường hợp bị loại.                                                                                                |
| **Layer bắt đầu lỗi**        | **UX / Safety.** Nếu AI được trình bày như một kết quả đáng tin tuyệt đối hoặc thiếu cơ chế review đối với các trường hợp bị loại, người dùng có thể phụ thuộc quá mức vào hệ thống. Tuy nhiên, case study không cung cấp đủ bằng chứng để khẳng định đây đã xảy ra.                          |
| **Harm xảy ra là gì?**       | **Chưa có bằng chứng trong case study rằng một harm cụ thể đã xảy ra do AI filtering.** Nguy cơ là ứng viên phù hợp có thể bị lọc nhầm và mất cơ hội tiếp tục nếu human review không đủ.                                                                                                      |
| **Harm lens**                | **Opportunity loss**                                                                                                                                                                                                                                                                          |
| **Severity**                 | **High** nếu một ứng viên phù hợp bị loại do lỗi AI, vì hậu quả có thể ảnh hưởng trực tiếp đến cơ hội việc làm.                                                                                                                                                                               |
| **Scale**                    | **High.** AI được báo cáo là có thể lọc tới 80% candidate pool và quy trình được triển khai tại hơn 53 quốc gia. Đây là quy mô của hệ thống, không phải số người chắc chắn bị harm.                                                                                                           |
| **Probability**              | **Chưa đủ dữ liệu để định lượng.** Case study báo cáo hiệu quả nhưng không cung cấp tỷ lệ false negative đủ để tôi tự tính xác suất ứng viên phù hợp bị loại.                                                                                                                                 |
| **Frequency**                | **Chưa đủ dữ liệu để định lượng.** Việc lọc diễn ra thường xuyên trong quy trình tuyển dụng, nhưng không có dữ liệu công khai đủ để xác định tần suất lỗi.                                                                                                                                    |
| **Vì sao?**                  | Case study cho thấy AI có thể tạo ra hiệu quả đáng kể về thời gian và chi phí, nhưng không cung cấp đủ dữ liệu về false positives/false negatives. Vì vậy, tôi không biến nguy cơ thành một sự kiện đã xảy ra. Đây là lý do human review vẫn cần thiết khi AI tham gia quyết định tuyển dụng. |

---

## 5. Kết luận

Qua ba case, tôi nhận thấy rủi ro của AI trong tuyển dụng không chỉ nằm ở việc sử dụng AI, mà còn phụ thuộc vào **dữ liệu đầu vào, tiêu chí đánh giá, cách hệ thống được triển khai và mức độ human oversight**.

Case Amazon cho thấy mô hình có thể học lại bias từ dữ liệu tuyển dụng lịch sử. Case HireVue cho thấy việc sử dụng các tín hiệu như facial analysis và biometric data có thể tạo ra vấn đề về privacy, transparency và fairness. Trong khi đó, case Unilever cho thấy AI cũng có thể tạo ra giá trị thực tế như giảm thời gian và chi phí tuyển dụng khi được triển khai trong một quy trình có cấu trúc.

Từ đó, tôi cho rằng AI trong tuyển dụng nên được sử dụng theo hướng **Human-in-the-loop**: AI hỗ trợ xử lý và cung cấp evidence hoặc recommendation, nhưng con người vẫn chịu trách nhiệm kiểm tra và đưa ra quyết định cuối cùng.

Đối với hệ thống AI tuyển dụng, các tiêu chí đánh giá nên tập trung vào những yếu tố **liên quan trực tiếp đến yêu cầu công việc**, hạn chế sử dụng các tín hiệu không cần thiết hoặc có nguy cơ tạo bias. Kết quả AI cũng nên có explanation và evidence đủ rõ để HR có thể kiểm tra thay vì chỉ dựa vào một điểm số.

**Nguyên tắc tôi rút ra:**

> Luôn luố có Human in the loop, check lại các quyết định mà AI đã đưa ra, như trongproject đang làm, kết hợp thêm AI Logs

