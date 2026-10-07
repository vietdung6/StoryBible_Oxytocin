# OXYTOCIN — Story Bible

Đây là repository hiện hành của **OXYTOCIN**.

Mục tiêu của repo này là giữ đủ thông tin để viết truyện lâu dài mà không biến việc quản lý tài liệu thành một hệ thống phức tạp hơn chính câu chuyện.

Repo cũ chỉ được xem là **archive/reference**. Một chi tiết chỉ thuộc phiên bản hiện hành khi nó đã được đưa vào repository này.

---

## Cấu trúc chính

OXYTOCIN dùng hierarchy:

**Part → Arc → Ep → Chapter**

Tuy nhiên, workflow sáng tác không bắt đầu từ Chapter.

Trong lúc viết, mỗi **Ep** là một file văn bản. Chỉ sau khi **toàn bộ Arc đã hoàn chỉnh**, Arc mới được đọc lại và chia thành các Chapter theo nhịp truyện thực tế.

Không tạo Chapter trước chỉ để lấp cấu trúc.

### Các tuyến chính

- Part 00 — **ZEROTH AXIOM**
- Part I — **SIXTEEN**
- Part II — **NETWORK**
- Part III — **AMYGDALA**
- Part IV — **LIMBIC**
- Spin-off I — **FOIL**
- Spin-off II — **PAST**

---

## Bản đồ repository

```text
.
├─ README.md
├─ CURRENT.md
├─ CANON.md
├─ STYLE.md
│
├─ story/
├─ outline/
├─ mindgames/
├─ characters/
│  ├─ 01_CORE/
│  ├─ 02_MAJOR/
│  ├─ 03_SUPPORTING/
│  └─ 04_MINOR/
├─ continuity/
├─ world/
├─ research/
└─ inbox/
```

### `story/`

Văn bản truyện thực tế.

Đây là nơi trả lời câu hỏi:

> Truyện hiện tại thực sự viết gì?

Trong giai đoạn sáng tác, prose được giữ theo từng **Ep**. Không dựng lại prose từ outline nếu file truyện chưa tồn tại.

### `outline/`

Dàn ý của Part, Arc và Ep.

Outline giữ những gì cần để nhớ và tiếp tục câu chuyện:

- chuyện gì xảy ra;
- thứ tự các beat;
- mục đích của Ep/Arc;
- thay đổi nhân vật và quan hệ;
- chuỗi nhân quả quan trọng;
- các điểm chưa chốt.

Outline không phải văn bản truyện.

### `mindgames/`

Thiết kế kỹ thuật cho các màn đấu trí.

Có thể chứa:

- luật;
- dữ kiện;
- giới hạn;
- cách suy luận;
- lời giải;
- thông tin mỗi bên biết;
- tính công bằng;
- biến gây nhiễu;
- phương án phản ứng.

Không phải Arc nào cũng cần file mindgame. Chỉ tạo khi cơ chế đủ phức tạp để cần tách riêng khỏi outline.

### `characters/`

Hồ sơ nhân vật, chia thành bốn cấp:

- **01_CORE** — nhân vật cốt lõi của toàn bộ series.
- **02_MAJOR** — nhân vật lớn, có ảnh hưởng dài hoặc giữ vai trò quan trọng trong một tuyến.
- **03_SUPPORTING** — nhân vật phụ có tác động đáng kể nhưng không cần hồ sơ cấp Major.
- **04_MINOR** — nhân vật nhỏ cần giữ nhất quán.

Hồ sơ nhân vật giữ identity, voice, giới hạn năng lực, đặc điểm ổn định và những điều không được viết lệch.

### `continuity/`

Chỉ giữ những thứ cần theo dõi xuyên nhiều Arc:

- `TIMELINE.md` — thứ tự sự kiện;
- `RELATIONSHIPS.md` — trạng thái và các mốc quan hệ;
- `SEEDS.md` — chi tiết cài trước và payoff cần nhớ.

Không tạo thêm registry nếu chưa có nhu cầu thực tế.

### `world/`

Thiết lập thế giới và các tổ chức/địa điểm quan trọng.

### `research/`

Tài liệu nghiên cứu phục vụ việc viết.

**Research không tự trở thành canon.**

### `inbox/`

Nơi giữ ý tưởng chưa chốt.

Một ý tưởng trong `inbox/` không được xem là thiết lập chính thức cho tới khi nó được quyết định và chuyển sang đúng nguồn.

---

## Các file ở root

### `CURRENT.md`

Điểm bắt đầu khi quay lại dự án.

Chỉ cần trả lời:

- đang viết gì;
- file hiện tại là gì;
- đã dừng ở đâu;
- bước tiếp theo là gì;
- có vấn đề cục bộ nào cần nhớ.

Giữ file này ngắn.

### `CANON.md`

Chỉ giữ thiết lập cấp toàn series và những invariant thật sự cần tồn tại xuyên nhiều phần.

Không dùng nó làm kho chứa mọi fact của truyện.

### `STYLE.md`

Luật viết văn bản truyện.

Voice riêng của từng nhân vật nên nằm trong hồ sơ nhân vật tương ứng thay vì dồn tất cả vào đây.

---

## Workflow viết

Khi quay lại viết:

1. Đọc `CURRENT.md`.
2. Mở đúng file trong `outline/` của phần đang viết.
3. Nếu có đấu trí phức tạp, đọc file tương ứng trong `mindgames/`.
4. Chỉ mở character, continuity hoặc world file thực sự liên quan tới cảnh.
5. Trước khi viết prose, đọc `STYLE.md`.
6. Viết trực tiếp vào Ep tương ứng trong `story/`.
7. Khi toàn bộ Arc hoàn chỉnh, đọc lại Arc và mới chia Chapter.

**Không đọc toàn bộ repo theo mặc định.**

---

## Nguyên tắc giữ repo gọn

- Một loại thông tin nên có một nơi chịu trách nhiệm chính.
- Không copy cùng một fact vào nhiều file chỉ vì nó có liên quan.
- `story/` là prose, `outline/` là thiết kế câu chuyện, `mindgames/` là cơ chế đấu trí.
- Chat, brainstorm và repo cũ không tự override nội dung hiện hành.
- Không tự biến ý tưởng chưa chốt thành canon.
- Git giữ lịch sử thay đổi; repo hiện tại chỉ cần phản ánh trạng thái đang dùng.
- Chỉ thêm file hoặc hệ thống mới khi việc viết thực sự cần nó.

Mục tiêu cuối cùng của Story Bible là **giúp viết OXYTOCIN dễ hơn**, không phải biến OXYTOCIN thành một dự án quản trị tài liệu.
