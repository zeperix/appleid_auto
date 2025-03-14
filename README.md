<h1 align="center">Quản lý Apple ID tự động</h1>
<p align="center">
    <a href="https://github.com/zeperix/appleid_auto/issues" style="text-decoration:none">
        <img src="https://img.shields.io/github/issues/zeperix/appleid_auto.svg" alt="GitHub issues"/>
    </a>
    <a href="https://github.com/zeperix/appleid_auto/stargazers" style="text-decoration:none" >
        <img src="https://img.shields.io/github/stars/zeperix/appleid_auto.svg" alt="GitHub stars"/>
    </a>
    <a href="https://github.com/zeperix/appleid_auto/network" style="text-decoration:none" >
        <img src="https://img.shields.io/github/forks/zeperix/appleid_auto.svg" alt="GitHub forks"/>
    </a>
    <a href="https://github.com/zeperix/appleid_auto/blob/main/LICENSE" style="text-decoration:none" >
        <img src="https://img.shields.io/github/license/zeperix/appleid_auto" alt="GitHub license"/>
    </a>
</p>
<h3 align="center">Tiếng Việt | <a href="README_en.md">English</a> </h3>
<h3 align="center">Vui lòng đọc kỹ tài liệu này và hướng dẫn sử dụng trước khi sử dụng.</h3>
<h3 align="center">Sử dụng dự án này có thể yêu cầu một số kiến thức cơ bản.</h3>

---
# Cài đặt

```
bash <(curl -Ls https://raw.githubusercontent.com/zeperix/appleid_auto/refs/heads/backend/backend/setup.sh)
```

# Giới thiệu cơ bản

"Quản lý Apple ID theo cách hoàn toàn mới" — Đây là chương trình tự động kiểm tra và mở khóa Apple ID dựa trên câu hỏi bảo mật.

Phần giao diện người dùng (frontend) dùng để quản lý tài khoản, hỗ trợ thêm nhiều tài khoản và cung cấp trang hiển thị tài khoản.

Hỗ trợ tạo trang chia sẻ chứa nhiều tài khoản và có thể đặt mật khẩu cho trang chia sẻ.

Phần máy chủ (backend) định kỳ kiểm tra xem tài khoản có bị khóa hay không, nếu bị khóa hoặc bật xác thực hai yếu tố thì tự động mở khóa, thay đổi mật khẩu và báo cáo mật khẩu mới về API.

Đăng nhập vào Apple ID và tự động xóa thiết bị trong tài khoản Apple ID.

Kích hoạt pool proxy và cụm Selenium để tăng tỷ lệ mở khóa thành công, ngăn chặn kiểm soát rủi ro.

# Tính năng dự án

- Nhiều người dùng, kiểm soát quyền
- Quản lý nhiều tài khoản
- Trang chia sẻ tài khoản, hỗ trợ đặt mật khẩu, thời hạn, nội dung HTML tùy chỉnh
- Tự động mở khóa và tắt xác thực hai yếu tố
- Tự động/định kỳ thay đổi mật khẩu
- Tự động xóa thiết bị trong Apple ID
- Pool proxy và cụm Selenium, tăng tỷ lệ mở khóa thành công
- Cho phép kích hoạt mở khóa thủ công
- ...
