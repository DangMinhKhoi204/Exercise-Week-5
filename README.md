# Flutter Note App  
**Ứng dụng ghi chú sử dụng Flutter – SQLite – Provider**

---

## 📌 Mục đích dự án

Dự án này được xây dựng nhằm minh họa cách lưu trữ dữ liệu cục bộ bằng SQLite và quản lý trạng thái bằng Provider trong Flutter.
Ứng dụng nhỏ gọn nhưng đầy đủ tính năng CRUD, phù hợp cho người mới học hoặc dùng làm template cho các app cá nhân.

---

## ✨ Tính năng chính

📝 Thêm ghi chú mới gồm tiêu đề, nội dung và thời gian tạo tự động.

📚 Hiển thị danh sách ghi chú theo thứ tự cập nhật mới → cũ.

🛠 Chỉnh sửa thông tin ghi chú ngay trong giao diện riêng.

🗑️ Xóa ghi chú kèm hộp thoại xác nhận, tránh thao tác sai.

💽 Lưu trữ local bằng SQLite, dữ liệu không bị mất khi tắt app.

🔄 Tự động cập nhật giao diện khi dữ liệu thay đổi nhờ Provider.

---

## 🧰 Thư viện sử dụng

• sqflite – Thư viện làm việc với cơ sở dữ liệu SQLite trong Flutter  
• provider – Quản lý trạng thái theo mô hình reactive  
• path_provider – Lấy đường dẫn thư mục lưu trữ dữ liệu (database)  
• path – Hỗ trợ thao tác xử lý và nối đường dẫn  
• intl – Format ngày giờ, chuyển đổi kiểu hiển thị thời gian  
• cupertino_icons – Bộ icon phong cách iOS dùng trong ứng dụng  

---

## 📁 Cấu trúc thư mục


```
lib/
├── main.dart                     
├── models/
│   └── note.dart                 
├── database/
│   └── db_helper.dart            
├── providers/
│   └── note_provider.dart       
├── screens/
│   ├── home_page.dart            
│   └── note_editor_screen.dart   
└── widgets/
    └── note_card.dart            
```

---

### Hướng dẫn cài đặt & chạy

#### Các bước thực hiện
```bash
# 1. Clone hoặc giải nén source code
Fluter create week5_exercise
# 2. Vào thư mục dự án
cd week5_exercise
# 3. Lấy dependencies
flutter pub get
# 4. Chạy ứng dụng
flutter run
```

---

###  Ảnh chụp màn hình 
| Màn hình chính           | Tạo ghi chú mới             |
|--------------------------|-----------------------------|
| ![Home](images/home.png) | ![Add](images/new_note.png) |


| Chỉnh sửa                     | Xác nhận xóa                      |
|-------------------------------|-----------------------------------|
| ![Edit](images/edit_note.png) | ![Delete](images/delete_note.png) |
---

### ✅ Mức độ hoàn thành yêu cầu

• SQLite + sqflite: ✔ Hoàn thành  
• Provider (state management): ✔ Hoàn thành  
• Chức năng CRUD đầy đủ: ✔ Hoàn thành  
• Timestamp (createdAt, updatedAt): ✔ Hoàn thành  
• Xác nhận trước khi xóa: ✔ Hoàn thành  
• Lưu dữ liệu local sau khi thoát ứng dụng: ✔ Hoàn thành  

---
