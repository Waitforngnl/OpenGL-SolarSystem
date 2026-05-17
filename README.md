# Mô phỏng Hệ Mặt Trời OpenGL 🌌

Một dự án mô phỏng Hệ Mặt Trời 3D được xây dựng bằng C++, Modern OpenGL và GLFW. Dự án này đã được tùy chỉnh và nâng cấp để hỗ trợ hiển thị giao diện tiếng Việt (UTF-8) và sử dụng các bản đồ bề mặt hành tinh (texture) ở độ phân giải cao.

## 🚀 Hướng dẫn Cài đặt & Chạy dự án

Kho lưu trữ này chứa mọi thứ bạn cần để chạy hoặc biên dịch (build) dự án:
* **Bản Build Release:** Các file thực thi (exe) có thể chạy ngay cho hệ điều hành x86/x64.
* **Visual Studio Solution:** File dự án `.sln` đã thiết lập sẵn sàng để biên dịch.
* **Mã nguồn & Thư viện:** Đã bao gồm tất cả các thư viện phụ thuộc cần thiết (OpenGL, GLFW, GLAD, GLM, FreeType).

### Cài đặt & Biên dịch (Build)
1. Clone hoặc tải về (download) kho lưu trữ này.
2. Mở file `DiamondEngine.sln` bằng phần mềm **Visual Studio**.
3. Đảm bảo cấu hình build ở thanh công cụ phía trên đang được đặt là **Release** và **x64**.
4. Nhấn phím `F5` để biên dịch và khởi chạy mô phỏng.

## 🎮 Điều khiển & Góc nhìn

#### 🎥 GÓC NHÌN CỐ ĐỊNH (Mặc định)
* Nhấn phím **SPACE** (Phím cách) để bật chế độ GÓC NHÌN CỐ ĐỊNH.
* Sử dụng các phím **W, A, S, D** để di chuyển camera xung quanh hệ mặt trời.
* **Giữ chuột phải + Kéo** để xoay góc nhìn.

#### 🛸 GÓC NHÌN TỰ DO
* Nhấn phím **F1** để bật chế độ GÓC NHÌN TỰ DO.
* Sử dụng **W, A, S, D** và **Chuột** để tự do bay lượn trong mô hình không gian.

#### 🪐 GÓC NHÌN HÀNH TINH
* Nhấn các phím số từ **1 ... 8** để camera bám theo một hành tinh cụ thể (VD: phím 1 cho Sao Thủy, phím 3 cho Trái Đất).
* Ở chế độ này, thông tin chi tiết về hành tinh (Vận tốc quỹ đạo, Khối lượng, Trọng lực) sẽ được hiển thị ở góc trên cùng bên trái màn hình.

#### 🌌 SKYBOX (Bầu trời nền)
* Nhấn phím **E** để chuyển đổi qua lại giữa các môi trường không gian nền khác nhau.

## 🛠️ Công nghệ sử dụng

* **[OpenGL](https://www.opengl.org/)** - API đồ họa cốt lõi được sử dụng.
* **[GLAD](https://glad.dav1d.de/)** - Thư viện nạp các hàm OpenGL đa ngôn ngữ.
* **[GLFW](https://www.glfw.org/)** - Quản lý việc tạo cửa sổ, ngữ cảnh (context) và xử lý sự kiện đầu vào (chuột, phím).
* **[FreeType](https://www.freetype.org/)** - Thư viện render font chữ (Đã được nâng cấp để đọc mã Unicode ký tự rộng, hỗ trợ hiển thị tiếng Việt hoàn chỉnh).
* **[GLM](https://glm.g-truc.net/0.9.9/index.html)** - Thư viện toán học chuyên dụng cho phần mềm đồ họa.

## 🎨 Tài nguyên & Tham khảo

* **Textures:** Các bản đồ bề mặt hành tinh đã được nâng cấp lên độ phân giải cao (4K/8K).
* **Fonts:** [Roboto](https://fonts.google.com/specimen/Roboto) - Dùng để hiển thị giao diện UI tiếng Việt sắc nét, chống răng cưa.
* **Hướng dẫn (Tutorials):** Các bài học tuyệt vời từ [LearnOpenGL](https://learnopengl.com/).
* **Skyboxes:** [SkyBox Không gian mặc định](http://www.custommapmakers.org/skyboxes.php) và [SkyBox Xanh](https://opengameart.org/content/space-skyboxes-0).

---
**Tác giả:** Nguyễn Tuấn Anh (MSSV: 4901104003)  
*Trường Đại học Sư phạm TP.HCM (HCMUE)*