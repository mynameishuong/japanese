# Hiragana & Katakana Quiz — bản web cho điện thoại

Đây là website tĩnh, mở trực tiếp bằng đường link trên Chrome/Safari. Giao diện đã được tối ưu cho màn hình điện thoại. Không cần backend, không cần cài ứng dụng, và **không hỗ trợ offline** (cần Internet để tải trang).

## Cách nhanh nhất: xuất bản bằng GitHub Pages

1. Đăng nhập hoặc tạo tài khoản tại https://github.com/
2. Tạo repository mới, ví dụ `hiragana-katakana-quiz`.
   - Có thể chọn **Public** để dùng GitHub Pages miễn phí.
   - Không cần thêm README/license từ GitHub vì gói này đã có file.
3. Giải nén gói ZIP này trên máy tính.
4. Mở repository vừa tạo → **Add file** → **Upload files**.
5. Kéo thả `index.html` và `.nojekyll` vào trang upload. Có thể tải cả file `README.md` lên nếu muốn lưu hướng dẫn trong repo.
6. Bấm **Commit changes**.
7. Trong repository, vào **Settings** → **Pages**.
8. Ở phần **Build and deployment**, chọn:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/(root)`
   rồi bấm **Save**.
9. Chờ GitHub Pages triển khai xong. Đường link sẽ có dạng:
   `https://TEN-TAI-KHOAN.github.io/hiragana-katakana-quiz/`
   Thay `TEN-TAI-KHOAN` bằng tên tài khoản GitHub của bạn.
10. Mở đường link đó trên điện thoại để kiểm tra. Có thể gửi link cho người khác.

## Cách thay đổi website về sau

Sửa file `index.html` trên máy tính, sau đó upload/commit phiên bản mới lên repository GitHub với cùng tên file. GitHub Pages sẽ tự cập nhật website sau ít phút.

## Lưu ý

- Website hiện là một file HTML độc lập, không cần build bằng Node.js hay cài thư viện.
- Nếu trình duyệt còn hiển thị bản cũ, thử tải lại trang hoặc mở trong tab ẩn danh.
- Nếu cần âm thanh, hãy bật âm lượng điện thoại; một số trình duyệt chỉ phát âm thanh sau khi người dùng chạm vào trang.
- File HTML vẫn giữ nội dung/logic học hiện có. Chế độ Katakana đang dùng cơ chế hiển thị kana tương ứng từ bộ dữ liệu Hiragana; nếu muốn học từ vựng Katakana chuẩn riêng, cần bổ sung bộ từ vựng Katakana riêng sau.
# japanese
# japanese
