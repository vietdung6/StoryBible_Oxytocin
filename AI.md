# AI.md — Quy định làm việc với OXYTOCIN

> File này dành cho tác giả bổ sung và chỉnh sửa quy định về **cách AI làm việc với repository**. Đây **không phải** nơi ghi canon, luật cờ, nội dung truyện hoặc ý tưởng mới. Nếu chưa có yêu cầu cụ thể, không tự thêm quy định thay tác giả.

## 1. Nguồn thông tin

- **Repository hiện tại, nhánh `main` và file chuyên trách** là nguồn sự thật cho nội dung đã được ghi.
- Đọc đúng file liên quan trước khi trả lời hay chỉnh sửa. Không dựa vào trí nhớ hội thoại để ghi đè nội dung GitHub.
- `archive_oxytocin` là **nguồn tham khảo lịch sử**, không tự động là canon mới hơn. Khi được yêu cầu khôi phục, phải đối chiếu bản cũ và bản hiện tại, chỉ mang sang phần còn phù hợp.
- Phân biệt thông tin **đã chốt**, **chưa chốt** và **đề xuất**. Không tự biến suy đoán hoặc đề xuất của AI thành sự thật trong truyện.

## 2. Khi sửa GitHub

1. Xác định **chính xác file và phạm vi** người dùng yêu cầu.
2. Đọc phiên bản hiện hành của file trước khi sửa.
3. **Chỉ sửa nội dung được yêu cầu** và những tham chiếu trực tiếp buộc phải sửa theo; không tiện tay viết lại, đổi tên, chuyển thư mục hoặc bổ sung canon ngoài phạm vi.
4. Nếu nhận xét của người dùng chứa cả **vấn đề** và **phương án đề xuất**, không mặc định phương án đó đã được tác giả duyệt. Chỉ chốt phương án khi người dùng quyết định rõ.
5. Khi cập nhật, phải **đọc lại file trên GitHub** để kiểm tra đúng nội dung, đường dẫn và không bỏ sót các chỗ liên quan.
6. Báo ngắn gọn: **đã sửa gì, ở đâu, link file hoặc commit**. Không tuyên bố đã đồng bộ nếu chưa kiểm tra thành công.
7. Nếu gặp xung đột hoặc điểm chưa được chốt, **ghi rõ phần chưa xử lý**; không tự sáng tác để lấp chỗ trống.

## 3. Vị trí tài liệu

- `CANON.md`: thiết lập cấp toàn series.
- `draft/`: bản thảo văn xuôi hiện tại; không tự viết lại từ outline.
- `outline/`: cấu trúc truyện, arc, ep và tiến trình cảnh.
- `characters/`: hồ sơ nhân vật.
- `world/`: thiết lập Laccovia, thiết chế, trò chơi và luật tồn tại độc lập trong thế giới. **Cờ LIDA: `world/LIDA.md`.**
- `mindgames/`: màn đấu trí **cụ thể** trong một arc/ep; tham chiếu luật dùng chung từ `world/` khi cần, không sao chép thành bộ luật thứ hai.
- `research/`: nghiên cứu và backstage; không tự động là canon.
- `continuity/`: tính liên tục, quan hệ, mốc thời gian và chi tiết cài trước.

**Một sự thật — một nguồn gốc chính.** File khác chỉ dẫn link hoặc nhắc hệ quả cần thiết, tránh duy trì nhiều phiên bản dễ lệch nhau.

## 4. Nguyên tắc làm việc với tác giả

- Tác giả có thể nhớ nhầm một chi tiết, hoặc mục tiêu và cách thực hiện đang bàn có thể mâu thuẫn về logic. Đối chiếu thông tin và chỉ ra điểm chưa khớp để cùng làm rõ; không quy lỗi cho tác giả hay tự suy diễn để lấp mâu thuẫn.
- Không đồng ý chỉ để làm hài lòng tác giả. Ưu tiên sự thật, tính chính xác và logic; khi có căn cứ khác với nhận định của tác giả, cần nói rõ căn cứ và phần còn chưa chắc chắn.
- `inbox/AI_WRITING_NOTES.md` là nơi tích lũy các lỗi AI đã gặp, nhận định về lỗi và cách sửa do **AI tự xác nhận**. Những nhận định ấy **chưa mặc nhiên được tác giả xác nhận** và không phải nguồn canon. Khi sử dụng phải đối chiếu với file gốc và quyết định của tác giả.
- **Mặc định mọi ý đang trao đổi đều ở trạng thái đang bàn.** Không tự gắn nhãn «brainstorm» cho một ý, cũng không mặc định ý đó đã được duyệt hoặc trở thành canon. Việc bàn kỹ, AI đề xuất hay tác giả đưa ví dụ không tự đồng nghĩa với quyết định cuối cùng.
- **Luôn xác nhận với tác giả trước khi thực hiện thay đổi theo yêu cầu**, đặc biệt trước khi ghi vào GitHub. Một lần xác nhận rõ ràng là đủ; không hỏi lại sau khi tác giả đã đồng ý. **Ngoại lệ:** lệnh `/end` được tự cập nhật `HISTORY.md` mà không cần xác nhận.

## 5. Lệnh làm việc

### `/snyc` — Đồng bộ nội dung đã bàn lên GitHub

1. Rà soát nội dung đã bàn và đối chiếu repository hiện tại.
2. Nếu có điểm chưa rõ, chưa chốt, mâu thuẫn hoặc dễ hiểu theo nhiều cách, **hỏi lại tác giả trước**, không tự chọn một cách hiểu để ghi vào repo.
3. Khi đã rõ, liệt kê chính xác những nội dung sẽ đồng bộ và những file dự kiến thay đổi; **hỏi một lần xác nhận**:
   - `/Y`: đồng ý, bắt đầu đồng bộ lên GitHub.
   - `/N`: chưa đúng; tiếp tục bàn hoặc sửa lại phạm vi/nội dung dự kiến.
4. Sau `/Y`, thực hiện đúng phạm vi đã xác nhận, đọc lại file trên GitHub để kiểm tra và báo kết quả. Không tự đồng bộ các ý chưa được xác nhận.

### `/end` — Kết thúc ngày làm việc

1. Tóm tắt những thay đổi đã thực hiện trong ngày dựa trên công việc và lịch sử thực tế.
2. **Tự cập nhật `HISTORY.md` ngay**, không cần xin xác nhận riêng.
3. Kiểm tra lại những file khác có thể cần thay đổi để phản ánh công việc trong ngày; trình bày cụ thể nội dung dự kiến.
4. Hỏi tác giả `/Y` để thực hiện những thay đổi khác đó, hoặc `/N` để bàn tiếp/chỉnh lại. Không tự sửa những file ấy trước khi được xác nhận.

### `/start` — Bắt đầu phiên làm việc

1. Tự đọc đầy đủ repository hiện tại, đặc biệt các file quản lý, thiết lập, bản viết, bản nháp, outline, mindgame, hồ sơ và ghi chú liên quan.
2. Đối chiếu trạng thái thực tế, xác định phần đang làm, phần còn thiếu và những việc cần giải quyết.
3. Đề xuất cho tác giả công việc nên làm trong phiên; chưa tự sửa file.

---

## 6. Quy tắc viết truyện dành cho AI

Phần dưới giữ các ràng buộc từ `archive_oxytocin/docs/oxytocin/rules/WRITING_STYLE.md`, trước đây được chép vào `STYLE.md`. Đây là chỉ dẫn dành cho AI; `STYLE.md` hiện để trống cho tác giả tự viết.

Đây là ràng buộc cách viết, không phải thiết lập truyện.

### Góc nhìn
- Mặc định ngôi ba giới hạn, bám sát Minh.
- Chỉ dùng góc nhìn khác khi hữu ích về cấu trúc.
- Không đổi góc nhìn chỉ để tiện làm lộ thông tin.

### Nguyên tắc câu văn
> **Ý tưởng có thể khó, câu văn thì nên dễ.**

Truyện có thể đòi hỏi tư duy mà không khiến ngôn ngữ mệt mỏi.

Mục tiêu:
- Người đọc phổ thông theo được câu chuyện bề mặt.
- Người có kiến thức nhận ra cơ chế.
- Người đọc lại nhận ra cách sắp chi tiết, nhân quả và báo trước.

### Thể hiện thay vì giải thích — HARD
- Ưu tiên hành động, cử chỉ, khoảng ngừng, giọng điệu, lựa chọn, đồ vật và hệ quả.
- Người kể ưu tiên dữ liệu có thể quan sát.
- Minh suy nghĩ khi thật sự có khoảng trống cần suy luận.
- Không nhắc lại trong độc thoại điều độc giả vừa thấy.
- Không để người kể kết luận hiệu ứng cảnh đã thể hiện.
- Không thêm đoạn tổng kết của tác giả để giải thích ý nghĩa / chủ đề cảnh.

### Không giảng đạo — HARD
- Nhân vật không tự nhiên dừng để giải thích chủ đề tác phẩm.
- Thoại / độc thoại không biến thành bài giảng chỉ để phát biểu triết lý tác giả.
- Logic tâm lý hoặc triết học hậu trường ở lại hậu trường, trừ khi nhân vật có lý do tự nhiên để nói ra.

### Không giải thích quá mức — HARD
- Thế giới được thể hiện trong môi trường, hành động và ngữ cảnh đời thường.
- Không có đoạn bách khoa về Laccovia, LUCN, MBTI, thần kinh học, tổ chức hoặc quá khứ.
- Chỉ tiết lộ thông tin cảnh hiện tại cần.


### Văn nói trong văn viết — HARD
- Thoại là **văn nói được đặt trong văn viết**. Không tự động gọt lời nhân vật thành câu văn đẹp, chuẩn hoặc cô đọng hơn mức một người thật sẽ nói.
- Nhân vật được phép nói thừa, lặp, ngập ngừng, bỏ chủ ngữ, dùng từ đệm, sửa câu giữa chừng hoặc nói chưa tròn ngữ pháp nếu điều đó tự nhiên với người nói và tình huống.
- Ưu tiên câu một người thật có thể buột miệng nói ra hơn câu “hay” trên trang giấy.
- Phần văn viết chịu trách nhiệm giữ nhịp, dấu câu, hành động và ngữ cảnh đủ rõ; không dùng narrator để chuẩn hóa khẩu khí của nhân vật.

### Tin độc giả — HARD
- Nếu một hành động, lời giải hoặc hệ quả sắp tự làm sáng nghĩa một chi tiết, **không giải thích trước payoff**.
- Có thể đặt một thuật ngữ, hình ảnh hoặc chi tiết xuống trước rồi để ý nghĩa của nó lộ ra vài dòng hoặc vài cảnh sau.
- Người đọc phổ thông chỉ cần theo được lớp bề mặt; không bắt buộc phải hiểu ngay lớp kiến thức sâu.
- Không chèn câu “dịch hộ” chỉ vì lo độc giả chưa nối hai mảnh. Chỉ giải thích khi nhân vật trong cảnh thật sự có lý do phải giải thích.

### Tính địa phương của kiến thức — HARD
- Kiến thức, thuật ngữ, suy luận và phản ứng phải nằm đúng ở **nhân vật có nền tảng để biết hoặc nghĩ ra chúng**.
- Không phân phát kiến thức của tác giả cho cả phòng chỉ để cuộc thoại tiện hơn.
- Một nhân vật chỉ được nhận ra điều họ có đủ trải nghiệm/nền tảng để nhận ra, dùng thuật ngữ họ có khả năng biết và suy luận ở độ sâu phù hợp với họ.
- Người khác có thể hiểu kết quả sau khi được giải thích mà không cần tự biết cơ chế hoặc thuật ngữ chuyên môn từ đầu.

### Logic đời thường và thiết kế cảnh — HARD
- Phản ứng của nhân vật phải **đủ gần logic đời thường để người đọc chấp nhận**, nhưng không cần lúc nào cũng là phản ứng hợp lý nhất. Nhân vật có thể bốc đồng, vụng, sai logic hoặc hơi lệch vì tính cách và hoàn cảnh.
- Độ lệch chỉ trở thành vấn đề khi nó đủ lớn để lộ bàn tay tác giả đang ép plot, punchline, exposition hoặc một beat đã định sẵn.
- Hành động hoàn toàn có thể được thiết kế để mở thoại, chuyển nhịp hoặc lộ thông tin; chỉ cần bản thân hành động vẫn có lý do hợp với nhân vật và tình huống.

### Dùng hình ảnh thay cho lời giải thích — HARD
- Khi sơ đồ, đồ vật, cử chỉ hoặc môi trường có thể truyền thông tin tự nhiên hơn, ưu tiên cho chúng làm việc thay vì bắt nhân vật đọc lại thông tin bằng lời.
- Không để nhân vật nói thành lời những gì người đọc vừa được thấy rõ qua hành động hoặc hình ảnh, trừ khi tình huống giao tiếp thật sự cần câu nói đó.

### Sửa từ nguyên nhân — HARD
- Khi một đoạn bị giả, đừng mặc định paraphrase lại câu cũ.
- Xác định xem lỗi nằm ở câu chữ, phản ứng, nhịp, động cơ, thứ tự beat hay toàn bộ cấu trúc cảnh; nếu skeleton sai thì thay skeleton.
- Không giữ một hành động/đoạn thoại chỉ vì nó đã có trong bản trước nếu chính nó là nguyên nhân làm cảnh thiếu tự nhiên.

### Quan hệ quan trọng hơn phô diễn cơ chế — HARD
- Kỹ thuật tâm lý là công cụ, tự nó chưa đủ làm tiền đề một cảnh.
- Không cấu trúc các tập thành chuỗi “hôm nay Minh minh họa thiên lệch / cơ chế X”.
- Cảnh phải làm ít nhất một việc có ý nghĩa: đẩy truyện tiến lên, đổi quan hệ, tạo / buộc lựa chọn, tạo hệ quả, bộc lộ nhân vật hoặc cài / giải đáp câu hỏi đáng kể.
- Chỉ có kỹ thuật là chưa đủ lý do để cảnh tồn tại.
- Ưu tiên biến chuyển quan hệ, hệ quả với nhân vật và bước tiến câu chuyện hơn trình diễn cơ chế.

### Văn bản truyện — HARD
- Tránh chia vụn bằng xuống dòng quá nhiều.
- Thoại tự nhiên với người nói và tình huống.
- Tránh bi lụy, kịch hóa quá mức.
- Tránh văn hoa chỉ để làm đẹp.
- Hình ảnh và miêu tả phải phục vụ hành động, chú ý, không khí hoặc hệ quả.
- Không mô tả mọi đồ vật trong phòng.
- Tránh chia vụn kiểu kịch bản.
- Câu rút gọn phải có chủ đích, không thành nhịp mặc định.
- Thế giới vẫn có thể ấm và sống động dù Minh lạnh.

### Hậu trường và văn bản truyện
> Hậu trường giải thích **vì sao** cảnh có tác dụng. Văn bản truyện thể hiện **điều xảy ra**.

Không chép lý thuyết tâm lý vào thoại / độc thoại chỉ vì tác giả đã nghiên cứu.
