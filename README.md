# User Support Analysis & Strategy Presentation

Dự án này chứa tài liệu phân tích và slide thuyết trình về chiến lược cải thiện hệ thống User Support cho Internal Tools.

## 📂 Cấu Trúc Dự Án

- **`/Internal_Tool_Presentation`**: Chứa source code của Slide thuyết trình (HTML/CSS/JS).
    - `index.html`: File chính của presentation.
    - `style.css`: File định dạng giao diện.
    - `script.js`: Xử lý logic chuyển slide.
- **`5whys.md`**: Tài liệu phân tích nguyên nhân gốc rễ (5 Whys Analysis).
- **`pareto.md`**: Tài liệu phân tích Pareto 80/20 về các vấn đề User Support.
- **`solution.md`**: Chi tiết các giải pháp đề xuất (UserHub, Feedback Gateway, etc.).

## 🚀 Hướng Dẫn Chạy (Local)

1.  Clone repository về máy:
    ```bash
    git clone https://github.com/ht-nah98/UserSuport-Analysis.git
    ```
2.  Mở thư mục `Internal_Tool_Presentation`.
3.  Click đúp vào file `index.html` để mở slide trên trình duyệt.

## 🌐 Hướng Dẫn Deploy Lên Vercel

Dự án này hoàn toàn sẵn sàng để deploy lên Vercel.

1.  Truy cập [Vercel Dashboard](https://vercel.com/dashboard).
2.  Chọn **"Add New..."** -> **"Project"**.
3.  Import repository `UserSuport-Analysis` từ GitHub của bạn.
4.  Tại phần **"Configure Project"**:
    - **Framework Preset**: Chọn `Other`.
    - **Root Directory**: Nhấn nút `Edit` và chọn thư mục `Internal_Tool_Presentation`.
      *(Lý do: File website `index.html` nằm trong thư mục này, không phải ở ngoài cùng)*.
5.  Nhấn **Deploy**.

Sau khi deploy xong, bạn sẽ có link presentation online (ví dụ: `project-name.vercel.app`).

## 🛠️ Công Nghệ Sử Dụng

- **HTML5 / CSS3**: Layout và hiệu ứng slide.
- **Vanilla JavaScript**: Logic điều hướng (Next/Back).
- **Google Fonts & Icons**: Typography và Iconography.
- **Pareto & 5 Whys**: Phương pháp luận phân tích.

---
© 2024 Strategic Presentation.
