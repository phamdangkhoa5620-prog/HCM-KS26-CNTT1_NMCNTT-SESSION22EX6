## 1. Prompt AI theo công thức 3 thành phần

**Công thức:** Vai trò (Role) + Bối cảnh (Context) + Yêu cầu (Task).

```text
Bạn là chuyên gia hỗ trợ kỹ thuật Git và GitHub.

Tôi đang sử dụng Git trên Windows để đẩy code lên GitHub, nhưng Terminal báo lỗi:
error: open(".git/FETCH_HEAD"): Permission denied.

Tôi đã thử chạy lại lệnh nhưng vẫn không thành công.

Hãy giải thích nguyên nhân lỗi bằng ngôn ngữ bình dân, dễ hiểu. Sau đó hướng dẫn tôi cách khắc phục từng bước, ưu tiên phương án an toàn, không làm mất dữ liệu hoặc ảnh hưởng đến mã nguồn. Giải thích rõ tác dụng của từng câu lệnh trước khi tôi thực hiện.
```

## 2. Thực hiện khắc phục bằng quyền Administrator

**Các bước thực hiện:**

1. Đóng cửa sổ Terminal đang sử dụng.
2. Mở Start Menu trên Windows.
3. Tìm `Command Prompt` hoặc `PowerShell`.
4. Nhấn chuột phải và chọn **Run as Administrator**.
5. Di chuyển đến thư mục dự án bằng lệnh:

```bash
cd đường_dẫn_thư_mục_dự_án
```

6. Kiểm tra trạng thái Git:

```bash
git status
```

7. Thử đẩy code lên GitHub:

```bash
git push origin main
```


## 3. Ảnh chụp màn hình minh họa

- Mở Terminal bằng quyền Administrator.
- Thực hiện lệnh kiểm tra và khắc phục lỗi.
- Nhấn `Windows + Shift + S` để chụp màn hình.
- Dùng Paint khoanh vùng lỗi hoặc kết quả xử lý.
- Che tên tài khoản Windows, email và thông tin cá nhân.
- Chèn ảnh chụp thực tế vào phần này.

## 4. Tin nhắn nhờ giảng viên hỗ trợ theo Bug Reporting Framework

**Tiêu đề: Nhờ hỗ trợ lỗi Git Permission Denied khi Push code lên GitHub**

Em chào thầy/cô,

Em đang gặp lỗi khi đẩy mã nguồn lên GitHub và mong thầy/cô hỗ trợ.

**1. Context (Bối cảnh):**
- Hệ điều hành: Windows.
- Công cụ: Git và Terminal.
- Thao tác: Push code lên GitHub.

**2. Expected (Kết quả mong đợi):**
- Code được đẩy lên GitHub thành công.

**3. Actual (Kết quả thực tế):**
- Terminal báo lỗi `error: open(".git/FETCH_HEAD"): Permission denied`.
- Em đã thử chạy lại lệnh nhưng vẫn không thành công.

**4. Log (Thông tin lỗi):**

```text
error: open(".git/FETCH_HEAD"): Permission denied
```

**Các cách em đã thử:**
- Chạy lại lệnh Git.
- Mở Terminal bằng quyền Run as Administrator.
- Kiểm tra trạng thái Git.

Em mong thầy/cô hướng dẫn cách khắc phục để em có thể tiếp tục đẩy code lên GitHub mà không làm mất dữ liệu dự án.

Em cảm ơn thầy/cô!
