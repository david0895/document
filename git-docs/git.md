Lệnh Essential Git:
Bắt đầu
- Khởi tạo kho: git init 🌱
- Kho Clone: git clone [URL] 📦
Làm việc với điều khiển từ xa
- List Remote: git remote -v 📡
- Thêm Remote: git remote thêm [tên] [URL] ➕ 📡
- Gỡ Remote: git remote rm [tên] ➖ 📡
- Lấy thay đổi từ xa: lấy git [từ xa] 🔄
- Kéo Thay đổi: kéo git [từ xa] [chi nhánh] ⬇️
- Push Thay đổi: git push [từ xa] [chi nhánh] ⬆️
Chi nhánh & sáp nhập
- Danh sách Chi nhánh: Chi nhánh Git 🌿
- Tạo Chi nhánh: Chi nhánh git [tên] ➕🌿
- Switch Branch: thanh toán git [tên] ↔️🌿
- Tạo & Chuyển Nhánh: thanh toán git -b [name] ➕ ↔️🌿
- Merge Chi nhánh: git merge [chi nhánh] 🔄🌿
- Xóa Nhánh: Nhánh git -d [tên] ➖🌿
Thực hiện thay đổi
- Status: trạng thái git 📊
- Thêm Thay đổi: thêm git [tệp/directory] ➕ 📄
- Cam kết Thay đổi: git commit -m "[tin nhắn]" ✉️
- Sửa đổi Commit: git commit --sửa đổi 🛠️✉️
- Đặt lại: đặt lại git [tệp] ⏪
- Reset cứng: reset git --hard [cam kết] ⏪💥
Xem lại lịch sử
- Đăng ký: người git 📜
- Đăng nhập (Đồ họa): ghit --đồ thị 📊📜
- Show Thay đổi: git show [cam kết] 🔍
- Diff: git diff [chi nhánh] 🆚
Dọn dẹp & bảo trì
- Thay đổi Stash: git stash 📥
- Áp dụng Stash: git stash pop 📤
- Làm sạch các tập tin không theo dõi: git clean -f 🧽
Nâng cao & Lừa
- Rebase: git rebase [chi nhánh] 🏗️
- Cherry-pick: git cherry-pick [cam kết] 🍒
- Tag: git tag [tên] 🏷️
- Nhật ký Tìm kiếm: git log --grep="[mẫu]" 🔍 📜
Danh sách này bao gồm nhiều lệnh Git cốt lõi nhưng không mệt mỏi.
Sự linh hoạt và chiều sâu của Git có nghĩa là có lệnh và cờ cho các tình huống chuyên biệt khác nhau, bao gồm cấu hình (`git config`), vá (`git apply`), và các tùy chọn hợp nhất nâng cao.
Những lệnh này hình thành xương sống của hầu hết các hoạt động Git, tạo điều kiện thuận lợi cho việc kiểm soát phiên bản và hợp tác trong các dự án phát triển phần mềm.