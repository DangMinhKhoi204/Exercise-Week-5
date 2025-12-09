# 📝 Flutter Notes Application  
### **Sinh viên thực hiện: Đặng Minh Khôi**  
> *Để chứng minh bài tập được tự tay thực hiện, em có đính kèm ảnh đánh dấu chủ quyền bên dưới.*

---

## 📸 Xác nhận sở hữu bài làm

> Ảnh minh họa nhằm xác nhận đây là sản phẩm do chính em hoàn thiện.

![chu_quyen](images/chu_quyen1.jpg)

---

# 📚 Giới thiệu dự án

Ứng dụng **Flutter Notes** là một sản phẩm mẫu giúp người học làm quen với cách tổ chức dữ liệu cục bộ bằng SQLite, kết hợp quản lý trạng thái thông qua Provider.  
Dự án phù hợp cho sinh viên, người mới bắt đầu và cả những ai muốn xây dựng ứng dụng ghi chú cá nhân đơn giản nhưng hiệu quả.

---

# 🌟 Chức năng nổi bật

- **Tạo ghi chú nhanh chóng** với tiêu đề + nội dung + thời gian tạo tự động.  
- **Danh sách ghi chú thông minh**: sắp xếp theo thời điểm chỉnh sửa gần nhất.  
- **Giao diện chỉnh sửa riêng**, dễ sử dụng và trực quan.  
- **Xóa ghi chú có xác nhận**, hạn chế thao tác nhầm.  
- **Dữ liệu lưu vĩnh viễn** nhờ SQLite — tắt app vẫn còn.  
- **Tự động cập nhật giao diện** mỗi khi dữ liệu có thay đổi (Provider lắng nghe state).

---

# 🛠 Công nghệ & package được sử dụng

- **sqflite** – xử lý CRUD SQLite  
- **provider** – quản lý trạng thái theo mô hình lắng nghe–thay đổi  
- **path_provider** – truy vấn thư mục lưu trữ database  
- **path** – hỗ trợ xử lý đường dẫn  
- **intl** – format ngày giờ hiển thị  
- **cupertino_icons** – icon giao diện iOS  

---

# 📁 Cây thư mục của dự án

```
lib/
│── main.dart
│
├── models/
│   └── note.dart
│
├── database/
│   └── db_helper.dart
│
├── providers/
│   └── note_provider.dart
│
├── screens/
│   ├── home_page.dart
│   └── note_editor_screen.dart
│
└── widgets/
    └── note_card.dart
```

---

# 🚀 Cách chạy dự án

```bash
flutter pub get
flutter run
```

---

# 🖼️ Hình ảnh giao diện ứng dụng

### **Trang danh sách ghi chú – Trang tạo mới**
| Home | New Note |
|------|----------|
| ![Home](images/home.png) | ![New](images/new_note.png) |

### **Trang chỉnh sửa – Popup xác nhận xóa**
| Edit | Delete |
|------|--------|
| ![Edit](images/edit_note.png) | ![Delete](images/delete_note.png) |

---

# ✅ Tiến độ và yêu cầu đã hoàn thành

- Tích hợp SQLite bằng sqflite → **Hoàn thành**  
- Provider quản lý trạng thái → **Hoàn thành**  
- CRUD đầy đủ (Create–Read–Update–Delete) → **Hoàn thành**  
- Lưu thời gian tạo & cập nhật → **Hoàn thành**  
- Xác nhận trước khi xóa → **Hoàn thành**  
- Lưu trữ dữ liệu bền vững → **Hoàn thành**

---

