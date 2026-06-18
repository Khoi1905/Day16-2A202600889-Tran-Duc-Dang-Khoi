---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI hỗ trợ chủ shop online phản hồi câu hỏi trước mua hàng

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

- **Dự án của nhóm tôi là:** Công cụ hỗ trợ chủ shop online trả lời inbox/comment trước mua hàng nhanh và nhất quán hơn.
- **Lát cắt tôi chọn để phân tích hôm nay là:** Chủ shop online trong giờ cao điểm, khi có nhiều inbox/comment hỏi về giá, size, tồn kho, phí ship, thời gian giao hàng và đổi trả.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là tình huống đủ cụ thể để map workflow: khách đang có ý định mua nhưng cần được trả lời nhanh. Nếu phản hồi chậm hoặc sai, shop có thể mất đơn ngay.

## Bước 1 — Project Snapshot

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Chủ shop online bị quá tải khi phải trả lời nhiều câu hỏi lặp lại trước mua hàng trong giờ cao điểm, dẫn tới phản hồi chậm, thiếu nhất quán và bỏ lỡ cơ hội chốt đơn.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Chủ shop online nhỏ hoặc nhân viên trực inbox/comment cho shop trên Facebook, TikTok Shop, Shopee hoặc Instagram.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Tự trả lời thủ công, dùng mẫu copy-paste, tra bảng sản phẩm/chính sách, nhờ nhân viên phụ trực chat, hoặc thử dùng chatbot rule-based/ChatGPT rời rạc.

## Bước 2 — Market Context

1. **Ai đang gặp vấn đề này?**  
   > Chủ shop online nhỏ, người bán livestream, nhân viên CSKH/sales inbox phải trả lời khách trước mua hàng.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi chạy ads, livestream, flash sale hoặc giờ cao điểm buổi tối, nhiều khách hỏi cùng lúc về thông tin sản phẩm và chính sách mua hàng.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Trả lời tay, copy-paste mẫu, thuê người trực inbox, dùng chatbot rule-based, dùng ghi chú/bảng tính, hoặc hỏi ChatGPT rồi chỉnh lại.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Người mua kỳ vọng phản hồi gần như ngay lập tức, còn shop nhỏ thường thiếu nhân sự trực chat liên tục. AI đã đủ tốt để hỗ trợ nhận diện câu hỏi lặp lại và soạn nháp câu trả lời theo ngữ cảnh, nhưng vẫn cần kiểm soát thông tin quan trọng.

### Tóm tắt market context trong 3-4 dòng

> Shop online nhỏ sống nhờ tốc độ phản hồi và độ tin của tư vấn trước mua hàng. Trong giờ cao điểm, chủ shop hoặc nhân viên trực chat phải vừa hiểu câu hỏi, vừa tra thông tin sản phẩm/chính sách, vừa trả lời đủ nhanh để không mất khách. Các giải pháp hiện tại rẻ nhưng dễ chậm, sai hoặc thiếu nhất quán. Cơ hội nằm ở việc hỗ trợ đúng bước tra cứu và soạn phản hồi, không thay toàn bộ người bán.

## Bước 3 — Xác định Job Executor

- **Job executor của dự án này là:** Chủ shop online hoặc nhân viên trực inbox/comment trực tiếp trả lời khách trước mua hàng.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Đây là người trực tiếp đọc câu hỏi, tìm thông tin sản phẩm/chính sách, soạn câu trả lời và chịu áp lực nếu khách bỏ đi. Buyer có thể là chủ shop, nhưng job executor trong workflow thực tế là người đang trực chat.

## Bước 4 — Core JTBD

### Bản nháp 1

**Core JTBD bản nháp:**  
> Trả lời câu hỏi trước mua hàng bằng AI cho khách online trong giờ cao điểm.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: AI

### Bản chốt

**Core JTBD cuối cùng:**  
> Giải quyết câu hỏi trước mua hàng nhanh, chính xác và nhất quán trong giờ cao điểm để không mất đơn.

## Bước 5 — 3 Job Stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi livestream hoặc chạy ads làm inbox/comment đổ dồn trong vài phút | Tôi muốn hiểu nhanh khách đang hỏi gì và trả lời đúng thông tin sản phẩm | Tôi có thể giữ khách đang nóng nhu cầu mua thay vì để họ chờ rồi rời đi | Pain lớn nằm ở tốc độ hiểu câu hỏi và phản hồi trong cao điểm |
| JS2 | Khi nhiều khách hỏi lặp lại về size, giá, tồn kho, phí ship và đổi trả | Tôi muốn có câu trả lời nhất quán dựa trên thông tin shop đang dùng | Tôi có thể giảm sai sót và không phải gõ lại cùng một nội dung hàng chục lần | Pain nằm ở câu hỏi lặp lại nhưng vẫn cần đúng ngữ cảnh |
| JS3 | Khi khách hỏi thêm một câu cuối trước khi quyết định mua | Tôi muốn phản hồi nhanh, rõ và đủ tin để khách yên tâm | Tôi có thể tăng khả năng chốt đơn trước khi khách chuyển sang shop khác | Pain nằm ở thời điểm cận chốt đơn, nơi phản hồi chậm làm mất doanh thu |

## Bước 6 — Current Alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Tự trả lời thủ công | Đọc từng inbox/comment, tra thông tin, gõ phản hồi | Linh hoạt, hiểu ngữ cảnh shop, kiểm soát chất lượng | Chậm khi nhiều khách, dễ mệt, dễ bỏ sót, khó nhất quán | Thấp, vì không cần học tool mới |
| Copy-paste mẫu chat | Trả lời nhanh các câu hỏi lặp lại | Rẻ, dễ dùng, nhanh với câu hỏi đơn giản | Dễ sai ngữ cảnh, phải tự chọn mẫu, khó cập nhật theo tồn kho/chính sách | Thấp |
| Thuê nhân viên/intern CSKH | Tăng người trực chat và chia tải | Có người thật xử lý linh hoạt | Tốn chi phí, cần training, vẫn sai nếu thông tin phân tán | Trung bình |
| Chatbot rule-based hoặc ChatGPT thủ công | Tự động hóa một phần câu trả lời | Tốt với câu hỏi phổ biến hoặc soạn nháp nhanh | Rule cứng, thiếu dữ liệu shop; ChatGPT rời rạc dễ bịa nếu không có catalog/chính sách | Trung bình |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Tự trả lời thủ công kết hợp copy-paste mẫu chat và nhờ nhân viên phụ khi quá tải.

## Bước 7 — JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Hiểu khách đang hỏi về sản phẩm, chính sách hay ý định mua | Đọc inbox/comment bằng mắt, tự phân loại | Nhiều câu hỏi cùng lúc, câu hỏi viết tắt/sai chính tả, dễ hiểu nhầm | Med |
| Locate | Tìm thông tin đúng về giá, size, tồn kho, ship, đổi trả | Ghi chú, bảng sản phẩm, trí nhớ, hỏi nhân viên khác | Thông tin nằm rải rác, cập nhật không kịp, dễ trả lời sai | High |
| Prepare | Soạn câu trả lời phù hợp với câu hỏi và giọng shop | Gõ tay, copy-paste mẫu, chỉnh lại câu cũ | Tốn thời gian, câu trả lời thiếu cá nhân hóa, dễ lặp máy móc | High |
| Confirm | Kiểm tra lại thông tin quan trọng trước khi gửi | Tự đối chiếu tồn kho/giá/chính sách | Bước này hay bị bỏ qua khi quá tải, gây sai thông tin | High |
| Execute | Gửi phản hồi cho khách ở đúng kênh | Messenger, comment, TikTok/Shopee chat | Chậm nếu phải chuyển qua nhiều tab/kênh | Med |
| Monitor | Theo dõi khách có phản hồi, hỏi tiếp hay bỏ đi | Nhìn notification, tự nhớ khách nào cần follow-up | Dễ sót khách, không biết ai đang gần chốt | Med |
| Modify | Điều chỉnh câu trả lời khi khách đổi nhu cầu hoặc hỏi thêm | Gõ lại thủ công, sửa mẫu | Cần giữ ngữ cảnh hội thoại, dễ trả lời lệch | Med |
| Conclude | Chốt đơn, gửi link mua, lưu lead hoặc kết thúc hội thoại | Gửi link, nhập đơn, đánh dấu thủ công | Dữ liệu sau chat không được lưu có cấu trúc, khó học lại pattern | Low |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate  
**Bước đau nhất #2:** Prepare + Confirm

**Vì sao đây là nơi đáng chú ý nhất:**  
> Nếu không tìm đúng thông tin, shop trả lời nhanh cũng vô ích vì có thể sai giá, sai tồn kho hoặc sai chính sách. Nếu soạn câu trả lời chậm hoặc thiếu nhất quán, khách có thể chuyển sang shop khác trước khi được tư vấn đủ rõ.

## Bước 8 — AI Leverage Point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Locate | Nhận diện ý định câu hỏi và truy xuất thông tin liên quan từ catalog, FAQ, chính sách, tồn kho đã được shop cung cấp | Câu hỏi lặp lại nhiều, có thể map sang dữ liệu bán hàng có cấu trúc | Nếu dữ liệu shop cũ hoặc thiếu, AI có thể gợi ý sai |
| Prepare + Confirm | Soạn nháp câu trả lời theo giọng shop và highlight thông tin cần người bán kiểm tra trước khi gửi | AI mạnh ở tổng hợp ngữ cảnh và tạo phản hồi nhanh, còn người bán giữ quyền kiểm soát điểm rủi ro | AI có thể bịa, trả lời quá tự tin, hoặc dùng wording không phù hợp thương hiệu |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Hỗ trợ Locate + Prepare + Confirm: AI gợi ý câu trả lời dựa trên dữ liệu sản phẩm/chính sách của shop, đồng thời nhắc người bán kiểm tra các trường nhạy cảm như tồn kho, giá, đổi trả trước khi gửi.

**Vì sao không phải ở bước khác:**  
> Execute và Monitor cũng có thể tối ưu, nhưng nếu câu trả lời chưa đúng và chưa đủ tin, tự động gửi nhanh chỉ làm tăng rủi ro. Giá trị lớn nhất nằm trước khi gửi: tìm đúng thông tin, soạn đúng câu, và kiểm tra điểm có thể gây mất đơn hoặc khiếu nại.

## Bước 9 — Product Hypothesis

### Bản hypothesis của tôi

> Nếu chúng ta giúp chủ shop online hoặc nhân viên trực inbox giải quyết câu hỏi lặp lại trước mua hàng tốt hơn ở bước Locate + Prepare + Confirm, bằng cách gợi ý câu trả lời theo catalog và chính sách shop, thì họ sẽ chuyển từ trả lời thủ công/copy-paste sang giải pháp của nhóm, vì họ giảm thời gian phản hồi trong giờ cao điểm mà vẫn giữ kiểm soát chất lượng câu trả lời.

### Tín hiệu sớm nếu hypothesis này đúng

1. Chủ shop chấp nhận dùng gợi ý trả lời trong các ca cao điểm và gửi ít nhất 30-50% câu trả lời từ nháp được đề xuất sau khi chỉnh nhẹ.
2. Thời gian phản hồi trung bình cho câu hỏi lặp lại giảm rõ rệt, trong khi số lỗi về giá/tồn kho/chính sách không tăng.

## Bước 10 — Assumptions to Validate

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Pain trả lời inbox/comment trong giờ cao điểm xảy ra đủ thường xuyên | Nếu shop chỉ thỉnh thoảng quá tải, họ không có động lực đổi workflow | Quan sát phổ biến từ hành vi bán hàng online, nhưng chưa có phỏng vấn người dùng thật | Phỏng vấn 5-7 chủ shop/nhân viên trực chat về số lượng câu hỏi mỗi ca cao điểm |
| A2: Chủ shop có dữ liệu sản phẩm/chính sách đủ sạch để AI dùng | Nếu dữ liệu phân tán hoặc sai, gợi ý sẽ không đáng tin | Giả định từ việc shop thường có bảng giá, ảnh sản phẩm, chính sách ship/đổi trả | Xin sample catalog/FAQ từ 2-3 shop và thử map thành dữ liệu đầu vào |
| A3: Người bán tin gợi ý AI đủ để dùng trong chat thật | Nếu họ luôn phải kiểm tra lại từ đầu, sản phẩm không tiết kiệm thời gian | Bằng chứng hiện tại còn yếu, mới dựa trên logic workflow | Prototype nháp trả lời, cho người bán đánh giá độ đúng và mức chỉnh sửa cần thiết |
| A4: Người bán sẵn sàng chuyển khỏi copy-paste/thủ công | Workflow cũ rẻ và quen thuộc, dù chậm | Có logic pain nhưng chưa đo switching cost thật | Test landing/prototype trong 1 tuần với shop nhỏ, đo tần suất dùng lại |
| A5: Tốc độ phản hồi ảnh hưởng conversion đủ mạnh | Nếu khách không mua vì lý do khác như giá/sản phẩm, tốc độ trả lời không đủ tạo value | Bằng chứng hiện tại còn yếu, chưa đo bằng dữ liệu bán hàng của shop thật | So sánh đơn/chốt lead giữa nhóm câu hỏi được trả lời nhanh và nhóm bị trễ |

### Assumption nguy hiểm nhất nếu tôi đang sai

> A2 là nguy hiểm nhất: nếu dữ liệu sản phẩm/chính sách của shop không đủ sạch hoặc không được cập nhật, AI leverage point ở Locate + Prepare + Confirm sẽ tạo rủi ro trả lời sai thay vì tạo giá trị.

## Bước 11 — Share trong bàn

### Ghi nhanh sau khi nghe bạn cùng bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| Bùi Ngọc Khánh góp ý: nếu shop có nhân viên trực chat riêng, cần phân biệt rõ buyer là chủ shop và job executor là người đang trực tiếp trả lời inbox/comment. Khánh cũng nhắc AI có thể trả lời sai tồn kho, giá khuyến mãi hoặc chính sách đổi trả nếu dữ liệu không cập nhật, nên không nên tự động gửi ngay. | Job executor, AI leverage point, Assumption A2/A3 | Giữ job executor là "chủ shop hoặc nhân viên trực inbox/comment", nhưng ghi rõ người trực tiếp làm job là người đang trả lời khách. Giữ AI leverage point ở Locate + Prepare + Confirm, trong đó Confirm phải có người bán kiểm soát trước khi gửi. |

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Tôi giữ hướng phân tích vì job đủ cụ thể, workflow có điểm đau rõ và AI leverage point nằm ở bước trước khi gửi câu trả lời. Tuy nhiên tôi ghi rõ hơn rằng AI chỉ nên gợi ý và hỗ trợ kiểm tra, không tự động thay người bán ở các thông tin rủi ro như giá, tồn kho, đổi trả.

### Version cuối cùng tôi nộp

**Job executor:**  
> Chủ shop online hoặc nhân viên trực inbox/comment trực tiếp trả lời khách trước mua hàng.

**Core JTBD:**  
> Giải quyết câu hỏi trước mua hàng nhanh, chính xác và nhất quán trong giờ cao điểm để không mất đơn.

**2 bước đau nhất trong workflow:**  
> Locate; Prepare + Confirm.

**AI leverage point chính:**  
> Gợi ý câu trả lời dựa trên catalog/chính sách shop ở bước Locate + Prepare + Confirm, kèm kiểm soát của người bán trước khi gửi.

**Product hypothesis:**  
> Nếu giúp người trực inbox trả lời câu hỏi lặp lại trước mua hàng nhanh và nhất quán hơn bằng gợi ý dựa trên dữ liệu shop, họ sẽ chuyển khỏi trả lời thủ công/copy-paste vì giảm thời gian phản hồi trong giờ cao điểm mà vẫn kiểm soát được độ đúng.

**Assumption cần validate đầu tiên:**  
> Chủ shop có dữ liệu sản phẩm/chính sách đủ sạch và đủ cập nhật để AI dùng mà không tạo rủi ro trả lời sai.

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.
