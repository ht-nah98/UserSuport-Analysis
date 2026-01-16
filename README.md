# User Support Analysis & Strategy Presentation

Dự án này chứa tài liệu phân tích và slide thuyết trình về chiến lược cải thiện hệ thống User Support cho Internal Tools.

## 📂 Cấu Trúc Dự Án (Mới)

- **`/` (Root)**: Chứa source code website chính.
    - `index.html`: File chính của presentation.
    - `style.css`: File định dạng giao diện.
    - `script.js`: Xử lý logic chuyển slide.
- **`/docs`**: Chứa tài liệu phân tích chi tiết.
    - `5whys.md`: Phân tích nguyên nhân gốc rễ.
    - `pareto.md`: Phân tích Pareto 80/20.
    - `solution.md`: Giải pháp đề xuất.

## 🚀 Hướng Dẫn Deploy Lên Vercel (Zero Config)

Dự án này đã được chuẩn hóa để deploy **TỰ ĐỘNG** 100% trên Vercel.

1.  Truy cập [Vercel Dashboard](https://vercel.com/dashboard).
2.  Chọn **"Add New..."** -> **"Project"**.
3.  Import repository `UserSuport-Analysis`.
4.  **QUAN TRỌNG:** Không cần chỉnh sửa gì cả.
    - **Framework Preset**: `Other` (Mặc định).
    - **Root Directory**: `./` (Mặc định).
5.  Nhấn **Deploy**.

Vercel sẽ tự động tìm thấy file `index.html` ở thư mục gốc và chạy website.

## 🛠️ Công Nghệ Sử Dụng

- **HTML5 / CSS3**: Layout và hiệu ứng slide.
- **Vanilla JavaScript**: Logic điều hướng (Next/Back).
- **Google Fonts & Icons**: Typography và Iconography.

---
© 2024 Strategic Presentation.
