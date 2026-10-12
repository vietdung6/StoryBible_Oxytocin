# OXYTOCIN

Repository dùng để quản lý bản thảo, dàn ý, nhân vật, thế giới và các tài liệu phát triển của **OXYTOCIN**.

## Cấu trúc truyện

**Part → Arc → Ep → Chapter**

Trong quá trình viết, nội dung được phát triển theo **Ep**.  
Sau khi một **Arc** hoàn chỉnh, toàn bộ Arc mới được đọc lại và chia thành **Chapter** theo nhịp truyện thực tế.

## Cấu trúc repository

```text
.
├─ README.md
├─ CURRENT.md
├─ HISTORY.md
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
   ├─ IDEAS.md
   └─ AI_WRITING_NOTES.md
```

## Nội dung từng thư mục

### `story/`

Bản thảo truyện.

Mỗi Ep được viết thành một file riêng trong Arc tương ứng.

### `outline/`

Dàn ý của Part, Arc và Ep.

Dùng để giữ:
- diễn biến chính;
- thứ tự sự kiện;
- chức năng của từng Ep;
- thay đổi nhân vật và quan hệ;
- các điểm chưa hoàn thiện.

### `mindgames/`

Thiết kế các màn đấu trí hoặc cơ chế cần tách riêng khỏi outline.

Có thể bao gồm:
- luật;
- dữ kiện;
- giới hạn;
- cách suy luận;
- lời giải;
- thông tin mỗi bên nắm giữ;
- biến gây nhiễu.

### `characters/`

Hồ sơ nhân vật.

Bốn cấp:

- **01_CORE** — nhân vật trung tâm của toàn series.
- **02_MAJOR** — nhân vật lớn.
- **03_SUPPORTING** — nhân vật phụ quan trọng.
- **04_MINOR** — nhân vật nhỏ cần giữ nhất quán.

### `continuity/`

Theo dõi các yếu tố xuyên nhiều phần của truyện.

- `TIMELINE.md` — dòng thời gian.
- `RELATIONSHIPS.md` — trạng thái và tiến triển quan hệ.
- `SEEDS.md` — chi tiết cài trước và payoff.

### `world/`

Thiết lập thế giới, địa điểm và tổ chức.

### `research/`

Tài liệu nghiên cứu phục vụ quá trình viết.

### `inbox/`

Nơi lưu các nội dung hỗ trợ quá trình phát triển OXYTOCIN, không tự động trở thành canon:

- [`IDEAS.md`](inbox/IDEAS.md) — brainstorm, các ý tưởng đang thử và những việc cần cải thiện hoặc thiết kế lại.
- [`AI_WRITING_NOTES.md`](inbox/AI_WRITING_NOTES.md) — các lỗi AI đã gặp và thông tin dễ hiểu sai cần ghi nhớ để tránh viết lệch truyện. Có thể bổ sung ghi chú mới khi phát hiện lỗi.

## Các file chính

### `CURRENT.md`

Trạng thái hiện tại của dự án: phần nào đã xong, đang viết ở đâu và ưu tiên tiếp theo.

### `HISTORY.md`

Nhật ký theo ngày về những thay đổi và công việc đã thực hiện.

### `CANON.md`

Story bible và thiết lập của series.

### `STYLE.md`

Quy tắc văn phong và cách viết bản thảo.

## Workflow

1. Xác định Arc và Ep đang viết trong `CURRENT.md`.
2. Đọc outline tương ứng.
3. Đọc mindgame nếu Ep có cơ chế đấu trí riêng.
4. Mở các hồ sơ nhân vật hoặc world cần thiết.
5. Viết Ep trong `story/`.
6. Hoàn thiện toàn bộ Arc.
7. Chia Arc thành Chapter sau cùng.
