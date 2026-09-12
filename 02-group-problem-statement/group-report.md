# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

> Ghi chú: các quote phỏng vấn, số liệu khảo sát trong Phase 4, và các con số thời gian/tần suất trong Phase 5-6 là **ước lượng minh họa do AI điền theo yêu cầu** (chưa có phỏng vấn/khảo sát thật). Nhóm bắt buộc phải tự phỏng vấn/khảo sát thật và thay các số này trước khi nộp chính thức.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Phùng Quang Minh Huy | 02610  | Facilitator                                                   |
| 2   | Nguyễn Minh Hiếu | 02669  | Researcher                                                    |
| 3   | Lưu Nguyên Khôi | 02547  | Workflow                                                      |
| 4   | Nguyễn Văn Diện | 02615  | Writer                                                        |
| 5   | Trần Đình Duy | 02631  | Writer                                                        |

**Candidate problem nhóm chọn (1 câu):** Hội đồng duyệt đề tài capstone phải vừa tra cứu kho dữ liệu đề tài capstone khổng lồ đã tích lũy nhiều khóa vừa dựa vào kinh nghiệm cá nhân để tránh trùng đề tài cũ và đánh giá độ cần thiết, không có công cụ tra cứu tự động nên dễ chậm hoặc bỏ sót.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Trần Đình Duy | Chuyển requirement assignment thành task/checklist | Sinh viên làm lab/project | Đọc chéo tài liệu guide dài và kiểm tra thiếu sót tiêu chí trước khi nộp bài | Ý tưởng thực tế, format rõ ràng; tuy nhiên có thể giải quyết bằng checklist template tĩnh (Rule), chưa cần thiết phải dùng AI. |
| 2 | Trần Đình Duy | Tìm và tổng hợp kiến thức AI từ nhiều nguồn | Sinh viên tự học AI | Lọc các nguồn tài liệu uy tín và nối các bài viết rời rạc thành kết luận logic | Nhu cầu tự học cao nhưng phạm vi kiến thức quá rộng; khó kiểm chứng độ chính xác và nguy cơ AI bị ảo giác cao. |
| 3 | Trần Đình Duy | Debug lỗi code qua nhiều vòng thử | Sinh viên coding | Chẩn đoán nguyên nhân gốc rễ giữa bug thuật toán trong code và lỗi thư viện/môi trường | Đo được bằng thời gian sửa bug, nhưng các công cụ IDE/ChatGPT hiện nay đã làm rất tốt; khó tạo ra bài toán sản phẩm riêng biệt. |
| 4 | Nguyễn Minh Hiếu | Làm sạch và tiền xử lý dữ liệu cho bài tập máy học (Tabular/CSV) | Sinh viên / học viên thực hành Machine Learning | Viết code pandas/numpy thủ công xử lý ngoại lệ, missing values và định dạng tensor (mất 90') | Tốn 3–4 tiếng/assignment; tuy nhiên dữ liệu thực tế quá đa dạng (bảng, ảnh, text) nên rủi ro scope giải pháp bị phình to. |
| 5 | Nguyễn Minh Hiếu | Tổng hợp và hệ thống hóa kiến thức từ slide bài giảng lý thuyết AI (60–80 slide PDF) sau mỗi buổi học | Sinh viên học AI nền tảng chuyên sâu | Bóc tách công thức toán trừu tượng từ file PDF và giải mã sang ví dụ trực quan / code PyTorch (mất 55') | Rất thuyết phục, tần suất cao (2 buổi/tuần), ai cũng gặp; workflow rõ ràng và dễ đo lường kết quả tiết kiệm thời gian. |
| 6 | Nguyễn Minh Hiếu | Đọc hiểu và trích xuất kiến trúc mô hình từ Paper AI học thuật (10–18 trang) | Sinh viên đang nghiên cứu thuật toán AI | Tra cứu và giải mã công thức toán học lạ, hàm loss và ký hiệu viết tắt không đồng nhất (mất 45') | Giá trị học thuật cao nhưng kỹ thuật OCR toán và mapping code rất phức tạp, AI dễ bị ảo giác với công thức mới. |
| 7 | Nguyễn Văn Diện | Xâu chuỗi thông tin bối cảnh task mới rải rác giữa Jira, Notion, Slack | Junior Dev, Designer trong team công nghệ | Phải tìm đọc chéo qua nhiều nền tảng, lướt luồng tin nhắn dài để chốt yêu cầu thực tế | Nỗi đau kinh điển của người đi làm; tuy nhiên phụ thuộc lớn vào quyền truy cập API nội bộ doanh nghiệp và chính sách bảo mật. |
| 8 | Nguyễn Văn Diện | Đối chiếu chéo bản draft (báo cáo, bài tập) với Rubric/Checklist để tìm ý bỏ sót | Sinh viên, giảng viên, PM reviewer | Đọc dò thủ công từng dòng tiêu chí giữa 2 văn bản dài, rất dễ sót ý do kiệt sức và quá tải nhận thức | Workflow văn bản 2 đầu vào cực kỳ rõ ràng, giải quyết triệt để tình trạng nộp bài thiếu ý; nhóm đánh giá rất cao và đưa vào Shortlist. |
| 9 | Nguyễn Văn Diện | Nhắn tin ping-pong nhiều lượt để thu thập đủ thông tin cấu hình/version từ user báo lỗi | Customer Support, IT Helpdesk | Mất nhiều thời gian nhận diện thông tin bị khuyết và chờ đợi user phản hồi từng câu hỏi | Vấn đề có thật nhưng hoàn toàn có thể giải quyết bằng Form nhập lỗi bắt buộc (No-AI / Rule), chưa cần đến AI. |
| 10 | Lưu Nguyên Khôi | Thẩm định đề tài Capstone (chống trùng lặp + đối chiếu checklist) | Hội đồng thẩm định đề tài / Giảng viên review | Vừa phải lục lọi kho đề tài cũ tích lũy nhiều khóa vừa so từng dòng checklist Excel bằng tay (mất 12–15'/đề tài) | **Ứng viên xuất sắc nhất!**; actor rõ, metric đo được; phù hợp tuyệt đối cho AI Workflow hỗ trợ con người (LI-3). |
| 11 | Lưu Nguyên Khôi | Gợi ý ăn gì hôm nay theo quán gần, thời tiết, filter cá nhân | Sinh viên, nhân viên văn phòng | Mất 15–20 phút phân vân mỗi bữa trưa vì quá nhiều lựa chọn nhưng thiếu bộ lọc theo ngữ cảnh | Đề tài thú vị và gần gũi; tuy nhiên quyết định ăn uống mang tính cảm tính cao, khó xác định tiêu chí thành công rõ ràng. |
| 12 | Lưu Nguyên Khôi | Điều phối xe đạp công cộng free tập trung ở trạm đón bus | Sinh viên di chuyển hằng ngày tại campus | Giờ cao điểm trạm bus hết sạch xe trong khi các trạm xa lại thừa; điều phối thủ công không kịp | Pain point vận hành thực tế tại campus; tuy nhiên nhóm không có thẩm quyền vận hành xe và thiếu dữ liệu định vị GPS để giải quyết. |
| 13 | Phùng Quang Minh Huy | Quy trình gọi món và thanh toán trực tiếp thủ công tại quầy gây nghẽn giờ cao điểm | Sinh viên, nhân viên thu ngân canteen | Khách đứng phân vân chọn món tại quầy và thu ngân nhập máy thủ công làm tắc nghẽn hàng đợi | Vấn đề vật lý tại quầy; giải pháp tối ưu là dùng Web App/Kiosk tự order (No-AI) thay vì đưa AI vào xử lý. |
| 14 | Phùng Quang Minh Huy | Dự báo lượng khách theo lịch học và phân ca cho 30 nhân viên canteen lặp lại hằng tuần | Quản lý canteen (Manager), 30 nhân viên | Phân ca thủ công mất 2 tiếng/tuần nhưng vẫn lệch ca: giờ cao điểm thiếu người, giờ vắng thừa nhân sự | Bài toán tối ưu nhân sự rất thực tế và có sẵn dữ liệu POS; nhóm đánh giá cao về mặt impact nội bộ và đưa vào Shortlist. |
| 15 | Phùng Quang Minh Huy | Dự báo tiêu thụ nguyên liệu và cảnh báo nguy cơ lãng phí thực phẩm hằng ngày | Bếp trưởng, Quản lý canteen | Ước lượng nguyên liệu theo kinh nghiệm cảm tính, dẫn đến thừa thức ăn phải đổ bỏ hoặc thiếu món bán | Tác động tài chính trực tiếp đến canteen; tuy nhiên độ chính xác phụ thuộc vào dữ liệu báo cáo hao hụt từ bếp rất khó kiểm chứng. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A (Thẩm định & Đối chiếu tiêu chí) | #8 (Diện: Đối chiếu draft với Rubric), #10 (Khôi: Thẩm định đề tài Capstone) | Đọc văn bản đề xuất/báo cáo và đối chiếu với bộ tiêu chí hoặc kho dữ liệu cũ để phát hiện sai sót, thiếu hụt hoặc trùng lặp ý tưởng | Actor rõ ràng (hội đồng/giảng viên), workflow đối chiếu có tính chuẩn hóa cao, mang lại giá trị học thuật thực tế |
| B (Tổng hợp & Trích xuất học thuật) | #2 (Duy: Tổng hợp kiến thức AI), #5 (Hiếu: Tổng hợp slide lý thuyết AI thành code), #6 (Hiếu: Trích xuất kiến trúc paper AI) | Trích xuất, phân tích và diễn giải thông tin lý thuyết/học thuật phức tạp (slide, paper, công thức toán) thành định dạng dễ hiểu | Phục vụ học tập cá nhân sinh viên tốt, nhưng phạm vi kiến thức rộng và khó định lượng impact bằng số liệu cụ thể |
| C (Hỗ trợ Lập trình & Kỹ thuật) | #1 (Duy: Chuyển requirement thành checklist), #3 (Duy: Debug lỗi code), #4 (Hiếu: Tiền xử lý dữ liệu tabular ML) | Tự động hóa các tác vụ lặp đi lặp lại trong quy trình viết code, chuẩn bị dữ liệu và sửa lỗi kỹ thuật | Nhu cầu thực tế cao nhưng môi trường kỹ thuật và định dạng dữ liệu rất đa dạng, rủi ro phát sinh nhiều edge case |
| D (Tối ưu Vận hành & Giao tiếp) | #7 (Diện: Xâu chuỗi context Jira/Slack), #9 (Diện: Ping-pong lấy info bug), #11 (Khôi: Gợi ý ăn gì), #12 (Khôi: Xe đạp Vin), #13 (Huy: Kiosk gọi món), #14 (Huy: Phân ca canteen), #15 (Huy: Dự báo nguyên liệu) | Tổng hợp luồng thông tin phân tán hoặc dự báo nhu cầu vận hành thực tế để giảm thời gian chờ và phân bổ nguồn lực | Phụ thuộc nhiều vào hệ thống vận hành vật lý hoặc quyền truy cập tích hợp dữ liệu nội bộ (POS, GPS, log hệ thống) |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| Thẩm định đề tài Capstone (#10) | • Actor rất rõ ràng (Hội đồng thẩm định / giảng viên review).<br>• Pain point có bằng chứng thực tế từ báo cáo kiểm định FCTMS ("difficult to verify duplication across 2 semesters manually").<br>• Đo lường được rõ ràng thời gian thẩm định và tỷ lệ trùng lặp; phù hợp tuyệt đối cho bài toán Workflow AI hỗ trợ con người (LI-3). | • Trường/khoa đã có kho dữ liệu đề tài cũ tập trung, số hóa được chưa? (Nếu chưa, cần làm bước database trước AI).<br>• Ngưỡng % tương đồng bao nhiêu thì coi là "trùng" — cần hội đồng thật định nghĩa.<br>• Tất cả số liệu thời gian/số lượng đề tài hiện tại đều là ước lượng, chưa phỏng vấn giảng viên/phòng đào tạo thật. |
| Đối chiếu chéo bản draft với Rubric/Checklist (#8) | • Actor quen thuộc (sinh viên, giảng viên, PM), gặp thường xuyên mỗi kỳ học.<br>• Input/output văn bản cụ thể (bản draft và file rubric tiêu chí). | • Rubric giữa các môn/chuyên ngành rất khác nhau, khó chuẩn hóa logic đối chiếu; AI dễ sinh ảo giác khi đánh giá nội dung mang tính định tính cao. |
| Dự báo lượng khách và phân ca nhân viên canteen (#14) | • Actor cụ thể (Manager canteen), giải quyết bài toán chi phí nhân công và tránh quá tải ca làm.<br>• Nguồn dữ liệu đầu vào xác định (lịch học trường, dữ liệu POS cũ). | • Biến số ngoại cảnh nhiều (lịch nghỉ lễ, sự kiện phát sinh, thời tiết); khó tiếp cận dữ liệu thực tế và triển khai mô hình thử nghiệm trong lab. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Thẩm định đề tài Capstone (#10) | 5 | 5 | 5 | 4 | 5 | 5 | 4 | 33 |
| Đối chiếu draft với Rubric/Checklist (#8) | 4 | 4 | 4 | 3 | 4 | 4 | 4 | 27 |
| Dự báo lượng khách và phân ca canteen (#14) | 5 | 4 | 4 | 4 | 3 | 3 | 4 | 27 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Thẩm định đề tài Capstone
```

**Vì sao chọn (4-5 câu):**

```text
1. Vấn đề có bằng chứng đau thật (pain evidence) được xác nhận trực tiếp từ tài liệu kiểm định FCTMS §3.2 ("difficult to verify duplication across 2 semesters manually"), không phải suy đoán chủ quan.
2. Actor và luồng làm việc rất cụ thể: Hội đồng thẩm định đề tài capstone (Appraisal Council) / giảng viên review phải thẩm định 30–40 đề tài/đợt bằng checklist Excel thủ công và tra cứu đề tài cũ.
3. Điểm nghẽn tập trung rõ nét ở bước nhớ lại/tra cứu kho đề tài nhiều kỳ và đối chiếu checklist từng dòng, tốn ~12 phút/đề tài (~6–8 giờ/đợt).
4. Bài toán có ranh giới can thiệp AI rõ ràng (Semantic Search/Embedding so khớp ý tưởng + đối chiếu checklist), tuân thủ đúng giới hạn LI-3 (AI chỉ cung cấp bằng chứng và cờ cảnh báo, con người giữ quyền quyết định cuối).
5. Rất phù hợp để phân tích so sánh Rule vs Workflow vs Agent, có thể đo lường trực tiếp bằng thời gian thẩm định và số ca trùng lặp lọt lưới.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Đối chiếu draft với Rubric/Checklist (#8): Mặc dù workflow đối chiếu khá trực quan, nhưng rubric giữa các môn học và giảng viên có độ đa dạng quá lớn, khó chuẩn hóa tiêu chuẩn chấm trong lab và dễ vướng vào đánh giá chất lượng học thuật chuyên sâu ngoài khả năng của LLM đơn thuần.
- Dự báo lượng khách và phân ca canteen (#14): Bài toán mang đặc thù dự báo định lượng/time-series hơn là GenAI/NLP, đồng thời phụ thuộc nhiều dữ liệu nhạy cảm nội bộ doanh nghiệp và các biến số ngoại cảnh bất định (lịch thi, thời tiết) khó giả lập trọn vẹn trong khuôn khổ lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Thảo luận nhóm có băn khoăn về 2 điểm: (1) Trường/khoa đã có kho dữ liệu đề tài cũ tập trung hay chưa, và (2) Định nghĩa ngưỡng % tương đồng thế nào là "trùng lặp".
Chốt giải pháp: Thống nhất tiếp tục bài toán vì pain point cốt lõi là trùng lặp ngữ nghĩa (semantic similarity) - thứ mà tra cứu từ khóa không làm được. Nhóm giả định phạm vi lab sẽ chuẩn hóa tập dữ liệu đề tài cũ dạng JSON/CSV; còn ngưỡng % tương đồng sẽ đóng vai trò là cờ cảnh báo (flag) gợi ý để Hội đồng thẩm định xem xét và ra phán quyết cuối cùng chứ AI không tự ý từ chối đề tài.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview *(ước lượng minh họa)* | 3 giảng viên từng ngồi hội đồng thẩm định | 2/3 xác nhận từng bỏ sót/nghi ngờ trùng ít nhất 1 lần/kỳ. GV A: "Nhiều lúc duyệt xong mới nhớ ra kỳ trước có nhóm làm gần giống, lúc đó sinh viên đã làm được 2-3 tuần rồi." GV B: "Tôi phải hỏi thêm đồng nghiệp cùng khoa xem đề tài này có quen không, vì không nhớ hết được." | GV C cho rằng số ca trùng thực tế không nhiều, chủ yếu chỉ "gần giống hướng nghiên cứu" chứ không hẳn trùng đề tài | Thu hẹp phạm vi: ưu tiên "gợi ý đề tài gần giống kèm % tương đồng" thay vì chỉ báo nhị phân trùng/không trùng |
| Survey / poll *(ước lượng minh họa)* | 8 giảng viên hướng dẫn | 6/8 xác nhận từng mất hơn 10 phút/đề tài để tự tra cứu trùng lặp; 5/8 nói checklist Excel hiện tại dễ bỏ sót tiêu chí khi duyệt nhanh vào cuối đợt | 2/8 cho biết khoa của họ đã có sẵn một file dùng chung lưu đề tài các kỳ nên đỡ mất thời gian hơn các khoa khác | Bổ sung bước khảo sát xem khoa/bộ môn nào đã có kho dữ liệu tập trung, tránh build trùng nơi đã có giải pháp |
| Log / ticket / review (nếu có) | Một báo cáo đồ án capstone khác đã tham khảo được (mô tả hệ thống quản lý đề tài) — dùng làm bằng chứng gián tiếp | Tài liệu ghi nhận: việc kiểm tra trùng lặp đề tài giữa các kỳ trước hiện làm thủ công và rất khó xác minh chính xác — xác nhận pain có thật ở quy mô rộng hơn 1 lớp/1 khoa | Chỉ là 1 nguồn tham khảo duy nhất, không phải khảo sát trực tiếp tại đơn vị mình; chưa rõ mức độ nghiêm trọng (bao nhiêu ca/kỳ) | Không được coi đây là đã "validate" — vẫn phải phỏng vấn/khảo sát thật trước khi chốt candidate |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Số liệu minh họa cho thấy phần lớn giảng viên (ước lượng >70%) xác nhận việc tra cứu trùng lặp thủ công mất thời gian và dễ bỏ sót, nhưng mức độ nghiêm trọng có thể khác nhau tùy khoa/bộ môn (một số nơi đã có sẵn file dùng chung). Đây vẫn là số liệu AI ước lượng minh họa — nhóm bắt buộc phải phỏng vấn/khảo sát thật tại đơn vị mình trước khi chốt candidate chính thức.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Turnitin | https://www.turnitin.com/ | Similarity/originality check cho văn bản học thuật | Chính xác, được nhiều trường dùng, báo cáo % tương đồng chi tiết theo từng đoạn | Trả phí; thiết kế cho bài luận dài, không có bước đối chiếu checklist tiêu chí hay đánh giá "độ cần thiết" của đề tài | Có thể học cách hiển thị %-tương đồng kèm trích đoạn giống nhau, nhưng phần checklist + quy trình duyệt nhóm phải tự xây |
| iThenticate | https://www.ithenticate.com/ | Similarity check chuyên cho nghiên cứu/luận văn | Đúng đối tượng học thuật hơn Turnitin | Vẫn chỉ dừng ở check trùng lặp, không tích hợp quy trình hội đồng/duyệt | Xác nhận duplicate-check là bài toán đã có lời giải chuẩn (similarity scoring) — nhóm không cần tự nghĩ lại thuật toán từ đầu |
| pgvector (semantic search pattern) | https://github.com/pgvector/pgvector | Pattern lưu trữ + so khớp embedding cho tìm kiếm ngữ nghĩa | Mã nguồn mở, pattern phổ biến để tìm đề tài "gần giống ý tưởng" chứ không chỉ trùng câu chữ | Cần tự triển khai; không có sẵn UI/checklist cho hội đồng | Nên dùng hướng embedding + vector search (giống pattern này) thay vì so khớp từ khóa, để bắt trùng lặp về Ý TƯỞNG |
| Case tham khảo nội bộ (không public) | Tài liệu đặc tả một đồ án capstone khác (không nêu tên trường/nhóm) | Đã đặc tả 2 use case riêng: "AI kiểm tra theo checklist" và "AI kiểm tra trùng lặp" cho người review | Xác nhận đây là bài toán thật, từng có nhóm khác thiết kế ở mức đặc tả tương tự | Mới là đặc tả, chưa rõ đã cài đặt AI thật chưa; không public nên không học được chi tiết kỹ thuật | Xác nhận hướng tách 2 use case (checklist / duplication) là hợp lý, nhưng nhóm cần tự chọn thuật toán/mô hình, không copy nguyên |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Duplicate/similarity-check là bài toán đã có giải pháp chuẩn trên thị trường (Turnitin, iThenticate dùng similarity scoring; pattern kỹ thuật phổ biến là embedding + vector search như pgvector). Nhóm không cần tự xây thuật toán so khớp từ đầu — nên tích hợp một pattern semantic search có sẵn và dồn công sức vào phần chưa có giải pháp đóng gói: quy trình duyệt, checklist tiêu chí, và ranh giới quyết định giữa AI với hội đồng.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
CURRENT STATE — 22 phút/đề tài, 30–40 đề tài/đợt

[1 GV soạn & nộp đề xuất: batch]
→ [2 Thư ký/người phụ trách tổng hợp danh sách đợt duyệt: batch]
→ [3 Hội đồng đọc đề xuất: 5']
→ [4 Hội đồng tra cứu kho đề tài cũ + trí nhớ cá nhân: 12']  <-- bottleneck
→ [5 Đối chiếu checklist tiêu chí: gộp trong bước 6]
→ [6 Thảo luận & ra quyết định: 5']
→ [7 Gửi phản hồi cho GV/SV: batch]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Giảng viên hướng dẫn | Ý tưởng đề tài | File đề xuất đã nộp (Word/form) | 1 lần/đề tài, trước hạn nộp | Handoff sang thư ký/hội đồng |
| 2 | Thư ký / người phụ trách tổng hợp | Các đề xuất đã nộp qua email/form | Danh sách 30–40 đề tài/đợt | 1 lần/đợt | Gộp dữ liệu từ nhiều nguồn rời rạc |
| 3 | Hội đồng thẩm định | Đề xuất đề tài | Hiểu nội dung đề tài | 5 phút/đề tài | — |
| 4 | Hội đồng thẩm định | Đề xuất mới + kho đề tài cũ (không tập trung) + trí nhớ cá nhân | Nhận định trùng/không trùng | 12 phút/đề tài | **Bottleneck** — không có công cụ hỗ trợ, phụ thuộc trí nhớ từng người |
| 5 | Hội đồng thẩm định | Đề xuất + checklist tiêu chí | Đánh giá đạt/chưa đạt từng tiêu chí | Gộp trong bước 6 | Vẫn thủ công, dễ bỏ sót tiêu chí |
| 6 | Hội đồng thẩm định | Nhận định trùng lặp + đánh giá checklist | Quyết định duyệt / từ chối / yêu cầu sửa | 5 phút/đề tài | — |
| 7 | Thư ký / người phụ trách | Quyết định của hội đồng | Thông báo kết quả | 1 lần/đợt (gộp) | Handoff về GV/SV, dễ tồn đọng nếu số lượng đề tài lớn |

**Bottleneck chính (2-3 câu):**

```text
Bước 4 là bottleneck: hội đồng vừa phải lục kho đề tài cũ phân tán qua nhiều khóa, vừa dựa vào trí nhớ cá nhân từng thành viên để đoán xem đề tài có trùng không, tốn 12 phút/đề tài. Với 30–40 đề tài mỗi đợt, riêng bước này chiếm phần lớn thời gian duyệt và vẫn có thể bỏ sót vì phụ thuộc hoàn toàn vào trí nhớ con người.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — dưới 10 phút/đề tài

[1 GV soạn & nộp đề xuất: 5' - người, không đổi]
→ [2 AI quét kho đề tài + checklist, gắn cờ trùng lặp và trả kết quả pass/fail theo từng tiêu chí: 1' - AI]
→ [3 Hội đồng thẩm định xem báo cáo AI (cờ trùng lặp + pass/fail) + tự đánh giá, quyết định: 4' - review, human boundary]
→ [4 Thư ký gửi kết quả cho GV/SV: batch - người]

Fallback: AI gắn cờ sai hoặc bỏ sót → hội đồng quay lại tra cứu kho dữ liệu + trí nhớ cá nhân như quy trình hiện tại.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 22 phút/đề tài | Dưới 10 phút/đề tài | Bấm giờ trung bình N đề tài mỗi đợt duyệt |
| Số bước | 7 | 4 | Đếm bước trong workflow đã vẽ |
| Số bước thủ công | 6/7 | 3/4 (chỉ còn đọc, review/quyết định, gửi kết quả) | Đếm bước có actor là người |
| Bottleneck chính | Tra cứu trùng lặp thủ công (12') | Xem & xác nhận báo cáo AI (gộp trong 4') | So sánh thời gian bước chậm nhất trước/sau |
| Risk mới | Không có | AI bỏ sót (false negative) hoặc báo sai trùng lặp (false positive) | Đếm số ca hội đồng phải tự phát hiện thêm sau khi đã có AI, và số lần khiếu nại báo sai |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Hội đồng thẩm định đề tài capstone / người review là actor chính dùng công cụ; giảng viên hướng dẫn là người nộp đề xuất; sinh viên là người chờ kết quả duyệt. |
| **Workflow** | Giảng viên nộp đề xuất → hội đồng đọc, tra cứu kho đề tài cũ + trí nhớ cá nhân để tìm trùng lặp, đối chiếu checklist tiêu chí → thảo luận và ra quyết định → gửi phản hồi cho giảng viên/sinh viên. |
| **Bottleneck** | Bước tra cứu trùng lặp thủ công (kết hợp kho dữ liệu phân tán + trí nhớ cá nhân từng thành viên hội đồng), tốn khoảng 12 phút/đề tài, nhân với 30–40 đề tài mỗi đợt duyệt. |
| **Impact** | Hội đồng mất nhiều giờ làm việc mỗi đợt duyệt; từng có đề tài trùng/gần giống bị phát hiện sau khi đã duyệt, phải yêu cầu đổi đề tài giữa chừng — ảnh hưởng chất lượng học thuật và tiến độ của sinh viên. |
| **Success Metric** | Giảm thời gian duyệt/đề tài từ 22 phút xuống dưới 10 phút; giảm số ca trùng lặp phát hiện trễ (sau khi đã duyệt) về 0. |
| **Boundary** | AI hỗ trợ tra cứu trùng lặp (semantic search) và đối chiếu checklist tiêu chí, trả kết quả pass/fail theo từng tiêu chí; không tự động duyệt/từ chối đề tài, không đánh giá chất lượng ý tưởng hay code — người thẩm định cuối cùng luôn là hội đồng duyệt đề tài. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: "Impact" và "Success Metric" đang dùng số liệu ước lượng minh họa (12 phút, 30–40 đề tài/đợt), chưa được xác minh bằng phỏng vấn/khảo sát thật với hội đồng.
- Tôi sửa gì: Cần bổ sung số liệu thật ở Phase 4 (interview/survey) trước khi dùng bản v0 này làm chính thức; nếu số liệu thật lệch nhiều, phải viết lại Success Metric cho phù hợp.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: đánh giá "trùng lặp ý tưởng" và "đề tài có thiết yếu hay không" mang tính chủ quan — không có ngưỡng % tương đồng đúng/sai tuyệt đối, cùng một cặp đề tài có thể được người này cho là trùng, người khác cho là chỉ gần hướng; đây là lý do hội đồng hiện phải dùng phán đoán cá nhân thay vì một quy tắc cố định.
- Độ phức tạp: [x] Thấp (1-2 bước) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: chỉ 1 bước AI cố định (so khớp đề xuất mới với kho đề tài cũ + checklist), không cần phối hợp nhiều nguồn dữ liệu động hay ra quyết định nhiều tầng.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ Cao + Độ phức tạp Thấp → thiên về Workflow: không chọn Rule vì phần đánh giá trùng lặp/thiết yếu quá mơ hồ để mã hóa thành luật cứng, nhưng cũng không cần Agent vì số bước vẫn ít và không cần tự lập kế hoạch.
```

**Vì sao (2-3 câu):**

```text
Đầu ra (báo cáo gắn cờ trùng lặp + pass/fail theo checklist) là dữ liệu hỗ trợ có cấu trúc, không cần AI tự suy luận nhiều bước hay tự chọn công cụ — nên không cần Agent. Nhưng vì việc đánh giá "trùng lặp" và "thiết yếu" mang tính mơ hồ, không có luật đúng/sai cố định, nên Rule (từ khóa) không đủ; cần AI hiểu ngữ nghĩa (semantic search) ở giữa quy trình, trong khi người vẫn giữ vai trò phán đoán cuối cùng — đúng đặc điểm của Workflow.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Regex/từ khóa để dò tên đề tài trùng y hệt + checklist dạng câu hỏi có/không (đủ thành viên, đúng định dạng...) | Đủ nếu chỉ cần bắt trùng lặp CHÍNH XÁC câu chữ hoặc tiêu chí đơn giản dạng có/không | Bỏ sót trùng lặp về Ý TƯỞNG khi đề tài diễn đạt khác nhau — đây lại là phần khó nhất hội đồng cần hỗ trợ | Dùng cho phần checklist dạng câu hỏi cố định, không dùng để bắt trùng lặp ngữ nghĩa |
| **Workflow** | Script nhận đề xuất → AI (semantic search/embedding) so khớp với kho đề tài cũ + đối chiếu checklist → trả báo cáo gắn cờ trùng lặp + kết quả pass/fail theo từng tiêu chí cho hội đồng | Hợp vì quy trình đi thẳng 1 đường, đầu ra rõ ràng (danh sách trùng + % tương đồng + pass/fail), không cần rẽ nhánh động | AI có thể báo sai (false positive/negative), cần đặt ngưỡng % tương đồng hợp lý | **Chọn** — dùng cho bước gắn cờ trùng lặp + đối chiếu checklist trước khi hội đồng thẩm định xem |
| **Agent** | AI tự tra cứu nhiều nguồn, tự đặt ngưỡng, tự trao đổi qua lại với giảng viên để làm rõ đề tài trước khi báo cáo | Chỉ cần nếu phải tự thương lượng với nhiều bên hoặc tự chọn công cụ tra cứu khác nhau tùy tình huống | Rủi ro cao: agent có thể tự đưa nhận định thay hội đồng, khó kiểm soát, không cần thiết ở quy mô bài toán này | Chưa chọn |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? Không — rule/từ khóa chỉ bắt được trùng lặp câu chữ y hệt, trong khi phần lớn ca trùng thật là do diễn đạt khác nhau nhưng cùng ý tưởng, đúng phần mà hội đồng đang phải dùng trí nhớ cá nhân để xử lý.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Có, đi thẳng một đường: nộp đề xuất → AI so khớp → hội đồng xem báo cáo → quyết định, không có nhánh rẽ động tùy tình huống.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Không — chỉ cần một bước gọi semantic search cố định với đầu vào/đầu ra rõ ràng, không cần AI tự quyết định bước tiếp theo hay gọi thêm tool khác.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Hội đồng thẩm định đọc báo cáo AI ngay trong buổi duyệt nên phát hiện báo sai (false positive) gần như ngay lập tức; trường hợp AI bỏ sót (false negative) có thể phát hiện muộn hơn, khi có khiếu nại sau khi công bố kết quả.
5. Có hạ được từ Agent → Workflow → Rule không? Có — bài toán được xếp thẳng vào Workflow ngay từ đầu (không cần bắt đầu từ Agent rồi mới hạ xuống), và phần checklist dạng câu hỏi cố định còn hạ được tiếp xuống Rule.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
AI chỉ thực hiện đúng một việc cố định ở giữa quy trình — semantic search so khớp đề xuất với kho đề tài cũ và đối chiếu checklist — không cần tự lập kế hoạch nhiều bước hay gọi nhiều công cụ khác nhau. Đầu ra của AI là dữ liệu hỗ trợ (danh sách trùng + % tương đồng), người vẫn đọc và ra quyết định cuối cùng. Quy trình có input/output rõ ràng, đi một đường không rẽ nhánh — đúng đặc điểm của Workflow.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Không chọn Rule vì bài toán cốt lõi là tìm đề tài "gần giống" về Ý TƯỞNG chứ không chỉ trùng câu chữ, đòi hỏi hiểu ngữ nghĩa — mà rule/từ khóa không làm được. Đây chính là lý do hội đồng hiện đang phải dùng trí nhớ cá nhân thay vì một công cụ tra cứu máy móc đơn giản.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Hội đồng thẩm định đề tài capstone / người review là actor chính dùng công cụ; giảng viên hướng dẫn là người nộp đề xuất; sinh viên là người chờ kết quả duyệt. |
| **Workflow** | Giảng viên nộp đề xuất → hội đồng đọc, tra cứu kho đề tài cũ + trí nhớ cá nhân để tìm trùng lặp, đối chiếu checklist tiêu chí → thảo luận và ra quyết định → gửi phản hồi cho giảng viên/sinh viên. |
| **Bottleneck** | Bước tra cứu trùng lặp thủ công (kết hợp kho dữ liệu phân tán + trí nhớ cá nhân từng thành viên hội đồng), tốn khoảng 12 phút/đề tài, nhân với 30–40 đề tài mỗi đợt duyệt. |
| **Impact** | Hội đồng mất nhiều giờ làm việc mỗi đợt duyệt; từng có đề tài trùng/gần giống bị phát hiện sau khi đã duyệt, phải yêu cầu đổi đề tài giữa chừng — ảnh hưởng chất lượng học thuật và tiến độ của sinh viên. |
| **Success Metric** | Giảm thời gian duyệt/đề tài từ 22 phút xuống dưới 10 phút; giảm số ca trùng lặp phát hiện trễ (sau khi đã duyệt) về 0. |
| **Boundary** (làm / không làm) | Làm: gắn cờ trùng lặp ngữ nghĩa với đề tài cũ, đối chiếu checklist tiêu chí và trả kết quả pass/fail theo từng tiêu chí, tóm tắt điểm khác biệt cho hội đồng. Không làm: không tự động duyệt/từ chối đề tài, không đánh giá chất lượng ý tưởng hay code, không thay thế vai trò con người trong quyết định cuối — người thẩm định luôn là hội đồng duyệt đề tài. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp sau bước hội đồng đọc đề xuất, trước bước hội đồng thảo luận và ra quyết định — tức thay thế bước tra cứu thủ công và tự động trả kết quả pass/fail theo checklist để hội đồng thẩm định xem trước khi quyết định. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow — AI chỉ làm một việc cố định (semantic search + checklist match) ở giữa quy trình tuyến tính, người vẫn kiểm soát đầu vào và quyết định cuối. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất: AI bỏ sót trùng lặp (false negative) khiến đề tài trùng vẫn lọt qua. Người kiểm tra: hội đồng thẩm định đọc báo cáo AI trước khi duyệt, và vẫn giữ bước fallback tra cứu thủ công khi nghi ngờ. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor (hội đồng thẩm định) và workflow trước/sau đã được vẽ rõ ở Phase 5, có bottleneck và AI intervention point cụ thể. |
| Baseline + metric đo được chưa? | Yes | Workflow và điểm đo (thời gian duyệt/đề tài, số ca trùng phát hiện trễ) đã đủ rõ để bắt đầu pilot; số liệu cụ thể (22', 12', 30-40 đề tài) vẫn là ước lượng minh họa và sẽ được thay bằng số thật ngay trong lúc chạy pilot. |
| Data/input đủ dùng chưa? | Yes | Phần đối chiếu checklist tiêu chí thẩm định (bao gồm đánh giá đề tài thiết yếu) dùng được ngay vì checklist đã có sẵn (hiện đang dùng bản Excel) — AI có thể hỗ trợ thẩm định dựa trên tiêu chí này mà không cần chờ kho dữ liệu đề tài cũ. Phần kiểm tra trùng lặp ngữ nghĩa sẽ mở rộng dần khi kho dữ liệu đề tài cũ được số hóa. |
| AI sai, hậu quả chấp nhận được không? | Yes | AI chỉ đưa cảnh báo, hội đồng vẫn đọc và quyết định cuối, nên khi AI sai hậu quả chỉ là hội đồng mất thêm thời gian kiểm tra lại, không có quyết định sai xảy ra tự động. |
| Có người review/owner không? | Yes | Hội đồng thẩm định là owner của quyết định cuối, luôn đọc báo cáo AI trước khi duyệt. |
| Có cách non-AI đơn giản hơn không? | Yes | Chuẩn hóa kho đề tài cũ thành spreadsheet/database tra cứu theo từ khóa (rule-based) là bước có thể làm trước, chưa cần AI — nhưng không cản trở việc bắt đầu Go với phần checklist. |

**Decision:**

```text
Go (scope nhỏ, ưu tiên phần checklist trước)
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Actor và workflow đã rõ ràng, bài toán phù hợp mức Workflow theo phân tích ở 6.1. Quan trọng nhất: AI còn hỗ trợ thẩm định dựa trên tiêu chí (đối chiếu checklist, bao gồm đánh giá đề tài thiết yếu) — phần này dùng được ngay vì checklist đã tồn tại sẵn, không phụ thuộc vào việc phải có kho dữ liệu đề tài cũ hoàn chỉnh như phần kiểm tra trùng lặp. Rủi ro khi AI sai được kiểm soát vì hội đồng luôn đọc báo cáo và quyết định cuối. Vì vậy nhóm chọn Go với scope nhỏ: triển khai trước phần checklist, mở rộng dần sang phát hiện trùng lặp khi dữ liệu sẵn sàng hơn.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Lấy 10–15 đề tài mẫu của một đợt duyệt gần nhất đã có kết quả thật. Chạy thử AI đối chiếu checklist tiêu chí thẩm định (bao gồm tiêu chí thiết yếu) trên bộ đề tài này, và nếu đã có sẵn vài đề tài cũ để thử, chạy thêm bước gắn cờ trùng lặp ở quy mô nhỏ. Đối chiếu kết quả AI với quyết định thật của hội đồng. Đo 3 số: (1) số tiêu chí AI đối chiếu đúng so với hội đồng, (2) số ca AI báo sai (false positive) ở cả checklist lẫn trùng lặp, (3) thời gian hội đồng cần để đọc và xác nhận báo cáo AI so với 22 phút hiện tại.
```

**Nếu Not Yet — cần validate gì trước:**

```text
Không áp dụng cho quyết định hiện tại (Go). Các mục dưới đây là điều kiện để MỞ RỘNG phần kiểm tra trùng lặp ngữ nghĩa sau khi đã Go với phần checklist:
1. Phỏng vấn 2–3 thành viên hội đồng thật để lấy số liệu thời gian/tần suất trùng lặp thật, thay cho số liệu ước lượng.
2. Xác nhận trường/khoa có kho dữ liệu đề tài cũ tập trung, số hóa được không — nếu chưa, cần làm bước chuẩn hóa dữ liệu (non-AI alternative) song song.
3. Cùng hội đồng định nghĩa cụ thể ngưỡng "trùng/gần giống" (bao nhiêu % tương đồng thì gắn cờ).
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu sau khi validate phát hiện kho dữ liệu đề tài cũ không thể số hóa được hoặc pain không đủ lớn để đầu tư AI, phương án thay thế là chuẩn hóa kho đề tài thành spreadsheet/database tra cứu theo từ khóa (rule-based), không cần AI.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nếu sau 2 đợt duyệt thử nghiệm, tỷ lệ AI báo sai (false positive) hoặc bỏ sót (false negative) vượt quá mức hội đồng chấp nhận được, dừng dùng AI và quay lại quy trình tra cứu thủ công + checklist như hiện tại, đồng thời giữ lại phần chuẩn hóa kho dữ liệu (nếu đã làm) để dùng cho tra cứu thủ công nhanh hơn.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
