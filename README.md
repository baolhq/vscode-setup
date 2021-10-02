# Cài đặt & cấu hình Visual Studio Code 🧑‍💻🧑‍💻🧑‍💻

---

### # 1. Link download:

Nhấp vào [đây](https://code.visualstudio.com/Download), sau đó chọn phiên bản phù hợp với hệ điều hành trong máy của bạn, tải về và cài đặt.
**Đối với máy MacOS, làm theo hướng dẫn tại [trang setup dành cho Mac](https://code.visualstudio.com/docs/setup/mac)**.

**Lưu ý dành cho các bạn dùng Windows 7 trở xuống, kiểm tra 32bit hoặc 64bit bằng cách nhấn tổ hợp phím `Windows + R`, nhập `dxdiag` sau đó chọn `Yes` khi được hỏi. Trong cửa sổ hiện lên có dòng Operating System, chú ý xem nó để 32bit hay 64bit rồi mới chọn phiên bản VSCode phù hợp.**

### # 2. Cài đặt extensions:

Nhấn tổ hợp phím `Ctrl + Shift + X` để mở thanh extensions.
Tại đây, các bạn có thể thấy các extensions đã cài đặt trong mục `INSTALLED`.

Nhấp vào thanh tìm kiếm ở phía trên (dưới chữ `EXTENSIONS`) để tìm kiếm thêm các extensions trong thư viện.

Danh sách những extensions cần cài đặt để lập trình web:

- `Live Server`: Cho phép chạy trang web của mình trong mạng cục bộ, tự động reload (f5) lại trang mỗi khi mình save code.

- `HTML Snippets`: Giúp thêm màu cho các dòng code, gợi ý code cho mình trong lúc làm việc, từ đó tăng tốc độ phát triển.

- `Auto Rename Tag`: Mỗi khi đổi tên 1 thẻ trong HTML, extension này sẽ tự động đổi tên thẻ đi cặp với nó.

- `Prettier`: Chuyên dùng để format (định dạng, căn lề) cho code, giúp file của chúng ta dễ đọc hơn. Lưu ý sau khi cài xong nhớ chọn default formatter của VSCode là Prettier.

- `Visual Studio IntelliCode`: Dựa vào các đoạn code có sẵn trên mạng để gợi ý cho chúng ta trong lúc code, tăng hiệu suất đáng kể.

Một số extensions hay ho muốn chia sẻ cho ae (**không bắt buộc**):

- `Code Spell Checker`: Bắt lỗi chính tả tự động, khỏi phải quan tâm việc sai chính tả nữa.

- `Better Comments`: Thêm những dòng chú thích vào code, ví dụ //TODO sẽ có màu cam, nhắc nhở chúng ta nên code thêm phần nào.

- `Polacode`: Hay vì chụp màn hình rồi cắt kéo mệt mỏi, chỉ việc dùng extension này kéo thả một tí là có 1 bức ảnh chụp code đẹp như mơ.

- `Material Icon Theme`: Thêm icon cho file/thư mục, giúp chúng ta dễ nhận dạng code hơn, không cần phải nhìn cái đuôi loằng ngoằng.

### # 3. Mẹo & Thủ thuật sử dụng VSCode:

1. Mọi thao tác trong VSCode đều có thể thực hiện bằng lệnh mà không cần mất công tìm kiếm, chỉ cần nhấn tổ hợp `Ctrl + Shift + P`, trong hộp thoại `Command Palette` hiện ra, gõ thử `view zoom in` sau đó nhấn `Enter` để thấy điều kì diệu 🪄🪄.

2. Ngoài ra, nếu muốn nhanh hơn nữa các bạn có thể dành ít thời gian xem qua cái này, không cần thuộc lòng đâu, dùng từ từ là quen.
   ![Visual Studio Code Keyboard Cheetsheet](https://code.visualstudio.com/assets/docs/getstarted/tips-and-tricks/KeyboardReferenceSheet.png)

3. Để di chuyển qua lại giữa các file nhanh chóng, nhấn tổ hợp `Ctrl + P` rồi nhập tên file vào sau đó `Enter`, VSCode sẽ tự chuyển sanh file đó.

4. Có thể tuỳ chỉnh theme của VSCode bằng cách dùng `Command Palette` để chọn theme mình thích.

5. Trong lúc code, khi nó hiện gợi ý có thể gõ `TAB` để xác nhận, không cần click chuột hay `Enter`.

6. Từ góc trên bên trái, chọn `File -> Auto Save` để không bị mất code sau cả ngày trâu cày 🐃.
