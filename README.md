---
layout: default
title: 📼 Hệ thống chèn video tự động
---

# 📼 HỆ THỐNG CHÈN VIDEO TỰ ĐỘNG – INOX MẠNH HƯNG

## 🎯 Mục tiêu hệ thống

Tự động chèn video YouTube vào **bài viết và sản phẩm** trên website [inoxmanhhung.vn](https://inoxmanhhung.vn) với mục tiêu:

- ⏱️ Tăng **thời gian ở lại trang (time on page)**
- 📉 Giảm **tỷ lệ thoát trang (bounce rate)**
- 🚀 Cải thiện **SEO**, kích hoạt **Rich Snippet Video**
- 🧠 Loại bỏ thao tác thủ công, hoạt động **hoàn toàn tự động**

---

## 📁 Cấu trúc file sử dụng

### 1. [`video.json`](https://inoxmanhhung.com/video.json)

> 📦 Danh sách video đã phân tích SEO, đánh giá hiệu suất, và phân loại tự động.  
> 🔍 Dùng làm nguồn dữ liệu để lựa chọn video phù hợp với từng bài viết/sản phẩm.

**Các trường chính:**

- `title`: Tiêu đề video
- `embed_url`: Link nhúng YouTube
- `description_optimized`: Mô tả đã tối ưu SEO
- `views`: Lượt xem
- `upload_date`: Ngày đăng
- `thumbnail_url`: Ảnh đại diện
- `seo_score`: Điểm SEO đánh giá chất lượng
- `auto_category`: Danh mục tự động phân loại

> 📄 Truy cập trực tiếp: [inoxmanhhung.com/video.json](https://inoxmanhhung.com/video.json)

---

### 2. [`video_insert_config.json`](https://inoxmanhhung.com/video_insert_config.json)

> ⚙️ File điều khiển toàn bộ logic chèn video.  
> AI và Plugin sẽ dựa vào file này để quyết định **chèn video nào, ở đâu và như thế nào.**

**Tính năng hỗ trợ:**

- Lọc video theo: `seo_score`, từ khóa, chủ đề, loại máy
- Cấu hình số lượng video chèn (3–5/video)
- Chọn vị trí chèn trong bài viết
- Tự động sinh `Schema VideoObject` chuẩn Google
- Hỗ trợ responsive + tăng tốc độ tải

> 📄 Truy cập cấu hình: [inoxmanhhung.com/video_insert_config.json](https://inoxmanhhung.com/video_insert_config.json)

---

## 🔁 Quy trình hoạt động

1. **AI phân tích nội dung** bài viết (tiêu đề, từ khóa, danh mục…)
2. **So khớp thông minh** với video phù hợp từ `video.json`
3. **Chèn tự động 3–5 video** liên quan vào nội dung bài viết/sản phẩm
4. **Sinh Schema VideoObject** để hỗ trợ SEO
5. Hiển thị video **tối ưu hóa tốc độ và trải nghiệm**

---

## 📈 Kỳ vọng kết quả

| Chỉ số | Kết quả mong đợi |
|-------|------------------|
| ⬆️ Time on Page | +30–70% |
| ⬇️ Bounce Rate | Giảm mạnh |
| 🟢 Rich Snippet Video | Được Google nhận dạng |
| 🧠 Tự động hóa | 100% không cần thao tác tay |

---

## 📞 Liên hệ & Hỗ trợ

- 🌐 Website: [inoxmanhhung.vn](https://inoxmanhhung.vn)
- 📧 Email: sales@inoxmanhhung.com
- ☎️ Hotline: 0903 162 066 – 0908 414 555

> 🔧 Cập nhật hệ thống bởi đội ngũ kỹ thuật INOX MẠNH HƯNG  
> Phiên bản hệ thống: **Inox Manh Hung – Video Engine 3.0**

