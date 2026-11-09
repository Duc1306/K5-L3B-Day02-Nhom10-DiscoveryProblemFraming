# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trương Anh Đức
- MSSV:2A202604096
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:Nhóm 10
- Link repo nhóm: https://github.com/Duc1306/K5-L3B-Day02-Nhom10-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

**Chủ đề: Lên kế hoạch bữa ăn và đi chợ cho cả nhà với nhân vật là người chuẩn bị và nấu ăn chính trong căn nhà nhưng vẫn phải đi làm** 

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi chuẩn bị bữa tối mỗi ngày, tôi muốn biết trong nhà còn những nguyên liệu nào, để không mua lại thứ đã có. | Người đi chợ, người nấu | Ước lượng: cứ mỗi lần sắm đồ đều mua trùng ít nhất 1 nguyên liệu vì không nhớ trong tủ còn hay hết. |
| 2 | Lặp lại | Khi đi chợ cho tuần tới, tôi muốn biết cần mua bao nhiêu thực phẩm, để không mua quá nhiều rồi phải bỏ đi. | Người đi chợ, cả nhà | Ước lượng: có khoảng 1–2 món rau hoặc thực phẩm tươi bị bỏ mỗi tuần. |
| 3 | Tốn thời gian | Khi cả nhà chưa thống nhất ăn gì, tôi muốn chốt được bữa tối sớm, để không mất thời gian hỏi qua lại lúc ai cũng đói. | Cả nhà | Ước lượng: bữa tối nào cũng mất 20-25 phút để chọn món và kiểm tra nguyên liệu. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị danh sách đi chợ, tôi muốn gom nhu cầu nấu ăn của vài ngày vào một danh sách rõ ràng, để không phải quay lại cửa hàng vì thiếu món. | Người lập danh sách, người đi chợ | Ước lượng: mỗi lần đi mua hàng đều phải quay lại cửa hàng; mỗi lần khoảng 20 phút đi xe. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi trong nhà có người không ăn được hoặc không thích một số món, tôi muốn nhớ các lưu ý đó lúc chọn thực đơn, để không phải đổi món vào phút cuối. | Người nấu, thành viên gia đình | Ước lượng: trong 2 tuần có it nhất 1 bữa vắng đi 1 người vì không ăn được hoặc không thích món ăn. |
| 6 | Pain từ người khác | Khi nhờ người nhà mua thực phẩm, tôi muốn nói rõ loại và số lượng cần mua, để tránh mua nhầm hoặc mua thiếu. | Người nhờ mua, người đi mua | Ước lượng: trong 1 lần nhà mua hộ đều mua sai loại hoặc thiếu số lượng; phải đổi món. |
| 7 | Pain từ người khác | Khi nấu bữa tối, tôi muốn biết mọi người về nhà lúc nào, để không phải chờ lâu hoặc việc có nấu cho người đó hay không. | Người nấu, người ăn | Ước lượng: trong tuần có 6/7 bữa tối có người về lệch giờ. |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận nhiều tin nhắn để sắp xếp một buổi gặp mặt, tôi muốn nắm được ngày giờ mọi người đều rảnh, để chốt lịch không phải hỏi đi hỏi lại. | Người tổ chức, bạn bè | Ước lượng: Lần gần nhất, phải cố gắng liên lạc trong mấy ngày mới chốt được lịch. |


**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #1 — Mua trùng nguyên liệu khi chuẩn bị bữa tối | Theo ước lượng, xảy ra mỗi lần sắm đồ; actor và tình huống rõ, có thể đếm số món mua trùng. | Tần suất thực tế là bao nhiêu; nguyên nhân là không nhớ, không kiểm tra tủ hay danh sách chưa cập nhật? |
| 2 | #4 — Danh sách đi chợ chưa gom đủ nhu cầu, phải quay lại cửa hàng | Có ảnh hưởng thời gian cụ thể: khoảng 20 phút đi xe mỗi lần quay lại; có thể quan sát quy trình lập danh sách và đi chợ. | Có phải lần quay lại nào cũng do thiếu món trong danh sách, hay do hết hàng/đổi ý? Cần ghi nhận để xác nhận dấu hiệu “mỗi lần”. |
| 3 | #8 — Mất vài ngày trao đổi để chốt lịch gặp mặt | Có tình huống và actor rõ; có thể xem lại tin nhắn để xác định thời điểm bắt đầu và lúc chốt. | Chưa biết tần suất xảy ra và thời gian chủ động đọc/nhắn; CP1 mới ghi “mấy ngày”. Vấn đề này cũng khác chủ đề bữa ăn/đi chợ. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị bữa tối mỗi ngày, tôi muốn biết trong nhà còn những nguyên liệu nào, để không mua lại thứ đã có. |
| Actor | Người đi chợ và người chuẩn bị/nấu bữa tối trong gia đình. |
| Thời điểm / bối cảnh | Trước khi đi sắm nguyên liệu cho bữa tối hoặc những ngày sắp tới. |
| Quy trình hiện tại (3–7 bước) | 1. Nghĩ các món định nấu. 2. Mở tủ lạnh/tủ đồ khô kiểm tra. 3. Cố nhớ món nào còn hoặc đã hết. 4. Ghi hoặc nhớ danh sách cần mua. 5. Đi sắm đồ. 6. Về nhà và phát hiện có món bị mua trùng. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: nhớ lại và đối chiếu nguyên liệu; thời gian chưa được đo, cần bấm giờ trong vài lần đi chợ. |
| Impact (nếu không giải thì sao) | CP1 ước lượng mỗi lần sắm đồ có ít nhất một nguyên liệu mua trùng; gây tốn tiền và có thể làm thực phẩm dư, hỏng. |
| Success metric (baseline → target) | Baseline ước lượng: ít nhất 1 món mua trùng mỗi lần sắm đồ. Target thử nghiệm: giảm xuống tối đa 1 món mua trùng/tuần trong 2 tuần; ghi số món trùng sau mỗi lần đi chợ. |
| Phương án không dùng AI | Dán danh sách nguyên liệu lên tủ lạnh, đánh dấu khi dùng hết và kiểm tra danh sách trước khi đi chợ. |
| Giả thuyết về AI (nếu có) | Nếu danh sách viết tay vẫn hay bị bỏ quên hoặc không cập nhật, AI có thể hỗ trợ tạo bản nháp danh sách mua từ ghi chú; người đi chợ kiểm tra trước khi dùng. |
| Cảm nhận nhanh | Rule: danh sách dùng chung và quy tắc đánh dấu có thể giải quyết trước; chưa có bằng chứng cần AI. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — thời gian từng bước chưa được bấm giờ

[1 Nghĩ món định nấu] → [2 Kiểm tra tủ lạnh/tủ đồ khô]
→ [3 Nhớ và đối chiếu nguyên liệu] ← BOTTLENECK
→ [4 Ghi/nhớ danh sách cần mua] → [5 Đi sắm đồ]
→ [6 Phát hiện có nguyên liệu mua trùng]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị danh sách đi chợ, tôi muốn gom nhu cầu nấu ăn của vài ngày vào một danh sách rõ ràng, để không phải quay lại cửa hàng vì thiếu món. |
| Actor | Người lập danh sách mua sắm và người đi chợ (có thể là cùng một người). |
| Thời điểm / bối cảnh | Trước khi đi mua thực phẩm cho vài ngày hoặc cho tuần tới. |
| Quy trình hiện tại (3–7 bước) | 1. Nghĩ các bữa cần chuẩn bị. 2. Hỏi hoặc tham khảo nhu cầu của người trong nhà. 3. Kiểm tra nguyên liệu sẵn có. 4. Lập danh sách món cần mua. 5. Đi đến cửa hàng. 6. Nhận ra thiếu món cần thiết. 7. Quay lại cửa hàng để mua bổ sung. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–4: gom nhu cầu và chuyển thành danh sách đầy đủ; thời gian lập danh sách chưa đo. Hệ quả được ước lượng là phải quay lại cửa hàng, mất khoảng 20 phút đi xe mỗi lần. |
| Impact (nếu không giải thì sao) | Mỗi chuyến quay lại mất khoảng 20 phút đi xe, làm chậm việc nấu và tăng công sức đi lại. Cần xác nhận các chuyến quay lại có thực sự do thiếu món trong danh sách. |
| Success metric (baseline → target) | Baseline ước lượng: phải quay lại sau mỗi lần đi mua hàng. Target thử nghiệm: tối đa 1 chuyến quay lại trong 2 tuần; ghi số chuyến quay lại và nguyên nhân sau mỗi lần mua sắm. |
| Phương án không dùng AI | Dùng danh sách chung theo từng bữa, kiểm tra tủ trước khi ra cửa và gạch món đã mua. |
| Giả thuyết về AI (nếu có) | Nếu nhu cầu nấu ăn nằm rải rác trong nhiều ghi chú/tin nhắn, AI có thể gom chúng thành bản nháp danh sách; người trong nhà xác nhận món và số lượng trước khi đi. |
| Cảm nhận nhanh | Rule hoặc Workflow: danh sách chung và bước kiểm tra có thể đủ; chỉ cân nhắc AI nếu việc gom thông tin từ nhiều nơi thật sự tốn công. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — thời gian lập danh sách chưa đo; quay lại cửa hàng mất khoảng 20' đi xe

[1 Xác định các bữa cần chuẩn bị] → [2 Gom nhu cầu trong nhà]
→ [3 Kiểm tra nguyên liệu có sẵn] → [4 Lập danh sách mua]
→ [5 Đi mua hàng] → [6 Phát hiện thiếu món và quay lại: khoảng 20'] ← BOTTLENECK/CHI PHÍ PHÁT SINH
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận nhiều tin nhắn để sắp xếp một buổi gặp mặt, tôi muốn nắm được ngày giờ mọi người đều rảnh, để chốt lịch không phải hỏi đi hỏi lại. |
| Actor | Người tổ chức buổi gặp mặt và những người được mời. |
| Thời điểm / bối cảnh | Khi cần chọn ngày, giờ cho buổi gặp có nhiều bạn tham gia. |
| Quy trình hiện tại (3–7 bước) | 1. Người tổ chức đề xuất ngày/giờ. 2. Gửi tin nhắn hỏi lịch trong nhóm. 3. Chờ mọi người trả lời. 4. Hỏi lại người chưa phản hồi hoặc làm rõ lựa chọn. 5. So sánh các khung giờ. 6. Chốt và thông báo lịch. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: chờ và tổng hợp câu trả lời rải rác; CP1 ghi lần gần nhất mất vài ngày. Thời gian chủ động đọc/nhắn chưa được đo. |
| Impact (nếu không giải thì sao) | Việc chốt kế hoạch bị kéo dài, có thể khiến người tham gia khó sắp xếp hoặc bỏ lỡ buổi gặp. Tần suất vấn đề chưa rõ. |
| Success metric (baseline → target) | Baseline sơ bộ: lần gần nhất mất vài ngày; cần xem lại tin nhắn để ghi ngày bắt đầu và ngày chốt. Target thử nghiệm: chốt trong tối đa 24 giờ từ tin nhắn hỏi lịch đầu tiên; đo thời điểm tin nhắn đầu và tin xác nhận. |
| Phương án không dùng AI | Đưa ra 2–3 khung giờ cụ thể và yêu cầu mọi người trả lời theo cùng định dạng trước hạn chót. |
| Giả thuyết về AI (nếu có) | Nếu câu trả lời tự do trong nhiều tin nhắn khó tổng hợp, AI có thể tóm tắt các khung giờ đã nêu; người tổ chức kiểm tra trước khi chốt. |
| Cảm nhận nhanh | Rule/Workflow: bình chọn theo lựa chọn và hạn trả lời có thể đủ; AI chỉ đáng cân nhắc nếu phải tổng hợp nhiều phản hồi tự do. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — lần gần nhất kéo dài vài ngày; thời gian chủ động chưa đo

[1 Đề xuất ngày/giờ] → [2 Gửi tin nhắn hỏi lịch]
→ [3 Chờ phản hồi: vài giờ đến vài ngày] ← BOTTLENECK
→ [4 Hỏi lại/làm rõ] → [5 So sánh các khung giờ]
→ [6 Chốt và thông báo lịch]
```

### Card muốn pitch nhất

- Card số: 2 — Problem Card của vấn đề #4 (lập danh sách đi chợ và phải quay lại cửa hàng).
- Vì sao: mỗi lần quay lại ước lượng mất 20 phút đi xe; có thể kiểm tra nguyên nhân và đo số chuyến phát sinh qua nhật ký mua sắm.
- Câu hỏi muốn nhóm phản biện: “Làm sao xác nhận việc quay lại cửa hàng là do danh sách thiếu món, thay vì hết hàng hoặc đổi ý? Danh sách chung và bước kiểm tra trước khi đi đã đủ xử lý chưa?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: số liệu “mỗi lần mua trùng ít nhất một nguyên liệu” mới là ước lượng, chưa có ghi chép xác nhận. | Đồng ý. | Xem baseline là giả thuyết; đếm số nguyên liệu mua trùng sau mỗi lần đi chợ trong 2 tuần. |
| Card #2 (vấn đề CP1 #4): chưa chứng minh mọi chuyến quay lại đều do danh sách thiếu món. | Đồng ý. | Ghi lại nguyên nhân từng chuyến quay lại (quên ghi, hết hàng, đổi ý hoặc lý do khác) trước khi kết luận bottleneck. |
| Card #3: “mất vài ngày” không cho biết thời gian chủ động hay tần suất vấn đề. | Đồng ý. | Xem lại tin nhắn để ghi thời điểm đề xuất đầu tiên và lúc chốt; theo dõi thêm số lần tổ chức gặp. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
