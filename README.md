# 🌐 Local Passport Website

---

## 📑 Quy trình demo

### 📝 Đăng ký tài khoản
- Người dùng thực hiện đăng ký:  
  ![Register](assets/image.png)

- Kiểm tra CSDL sau khi đăng ký:  
  ![Show CSDL](assets/image-1.png)

---

### ⚠️ Đăng ký tài khoản trùng lặp
- Hệ thống vấn cho đăng ký trùng lặp
  ![Show CSDL bị trùng lặp tài khoản](assets/image-5.png)

---

### 🔐 Đăng nhập tài khoản
- Người dùng đăng nhập thành công:  
  ![Login](assets/image-2.png)

---

### 👤 Giao diện sau khi đăng nhập
- Trang hiển thị thông tin profile:  
  ![Profile](assets/image-3.png)

---

### 🚪 Logout
- Khi logout, hệ thống tự động trả về trang Login:  
  ![Logout](assets/image-4.png)

---

## 📌 Tổng kết
- **Passport.js** giúp xác thực username/password trong ứng dụng web.  
- Chưa đăng nhập thực hiện vào profile tự dộng được chuyển hướng vào login
- Khi đăng ký, tài khoản mới được lưu vào CSDL. Vẫn cho phép đăng ký trùng
- Khi đăng nhập, Passport tạo session và cookie để duy trì đăng nhập.  
- Nếu đăng nhập khi dữ liệu trong CSDL trùng lặp, tự động hướng đến giá trị so sánh đầu tiên
- Logout sẽ xóa session và điều hướng người dùng về trang login.  

✍️ *Demo phục vụ học tập về Authentication*
