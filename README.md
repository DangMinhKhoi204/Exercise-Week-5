# 📘 Flutter Note App  
***Sinh viên: Đặng Minh Khôi - Để xác nhận là em tự làm thì em sẽ đánh dấu chủ quyền để chứng minh ạ
Ứng dụng ghi chú sử dụng Flutter – SQLite – Provider**
# 📸 Ảnh xác nhận chủ quyền

> Đây là ảnh dùng để đánh dấu bài làm do **tự bản thân thực hiện**.

![chu_quyen](images/chu_quyen.jpg)

---



## 📌 Mục đích dự án

Dự án được xây dựng nhằm minh họa việc lưu trữ dữ liệu cục bộ bằng SQLite và quản lý trạng thái bằng Provider trong Flutter.  
Ứng dụng nhỏ gọn nhưng đầy đủ CRUD, phù hợp cho người mới học hoặc dùng làm template cá nhân.

---

## ✨ Tính năng chính

📝 Thêm ghi chú mới gồm tiêu đề, nội dung và thời gian tạo tự động.  
📚 Hiển thị danh sách ghi chú theo thứ tự cập nhật mới → cũ.  
🛠 Chỉnh sửa nội dung ghi chú.  
🗑️ Xóa ghi chú kèm hộp thoại xác nhận tránh thao tác nhầm.  
💽 Lưu dữ liệu cục bộ bằng SQLite.  
🔄 Giao diện tự cập nhật khi dữ liệu thay đổi nhờ Provider.

---

## 🧰 Thư viện sử dụng

• sqflite – Làm việc với cơ sở dữ liệu SQLite  
• provider – Quản lý trạng thái reactive  
• path_provider – Lấy đường dẫn lưu database  
• path – Hỗ trợ xử lý đường dẫn  
• intl – Format ngày giờ  
• cupertino_icons – Icon phong cách iOS  

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

## 🚀 Hướng dẫn cài đặt & chạy

```bash
# 1. Tạo project hoặc giải nén source
Flutter create week5_exercise

# 2. Vào thư mục dự án
cd week5_exercise

# 3. Tải gói
flutter pub get

# 4. Chạy app
flutter run
```

---

## 📸 Ảnh chụp màn hình

| Màn hình chính | Tạo ghi chú |
|----------------|-------------|
| ![Home](images/home.png) | ![Add](images/new_note.png) |

| Chỉnh sửa | Xóa |
|----------|------|
| ![Edit](images/edit_note.png) | ![Delete](images/delete_note.png) |

---

## ✅ Mức độ hoàn thành

• SQLite + sqflite: ✔ Hoàn thành  
• Provider: ✔ Hoàn thành  
• CRUD đầy đủ: ✔ Hoàn thành  
• Timestamp: ✔ Hoàn thành  
• Xác nhận trước khi xóa: ✔ Hoàn thành  
• Lưu dữ liệu cục bộ: ✔ Hoàn thành  

---


