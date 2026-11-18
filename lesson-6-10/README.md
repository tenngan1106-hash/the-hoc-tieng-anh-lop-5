# 🎒 Thẻ Học & Luyện Nghe Tiếng Anh Lớp 5 — Unit 6 đến Unit 10 (Global Success)

Ứng dụng web thẻ học, luyện nghe và **trình chiếu bảng lớn trên lớp** dành cho học sinh Lớp 5 (9–11 tuổi) theo chương trình sách giáo khoa **Global Success – Kết nối tri thức với cuộc sống (Học kỳ 1 · Unit 6 – Unit 10)**.

---

## 🌟 Tính Năng Nổi Bật

1. **Bám sát chương trình chuẩn Lớp 5 (Unit 6 – Unit 10):**
   * **Unit 6: Our School Rooms** (Các phòng học trong trường, số tầng & chỉ đường trong trường)
   * **Unit 7: Our Favourite School Activities** (Các hoạt động ở trường yêu thích & nêu lý do *Why – Because*)
   * **Unit 8: In Our Classroom** (Đồ dùng học tập, giới từ vị trí & sở hữu cách *Whose*)
   * **Unit 9: Our Outdoor Activities** (Địa điểm vui chơi ngoài trời & thì Quá khứ đơn với *Were / Did*)
   * **Unit 10: Our School Trip** (Chuyến đi dã ngoại trường học, danh lam thắng cảnh Việt Nam & Quá khứ đơn)

2. **Hình Ảnh Thực Tế Chuẩn Việt Nam & Tối Ưu Trình Chiếu Lớp Học:**
   * 100% ảnh cục bộ gọn nhẹ trong thư mục `assets/` (ảnh thực tế học sinh tiểu học Việt Nam, Cầu Vàng Bà Nà Hills, Hồ Hoàn Kiếm, Chùa Bái Đính, Suối Tiên, Nhà hát Lớn Hà Nội & đồ họa SVG sắc nét cho sơ đồ tầng, chỉ đường, giới từ, lịch quá khứ) — không lo vỡ ảnh khi dạy trên lớp!
   * Tích hợp **chế độ Toàn màn hình (`📺 Toàn màn hình`)** và hỗ trợ **bút trình chiếu / phím mũi tên (`◀` `▶`, `PageUp`/`PageDown`, `Space`)** để giáo viên giảng dạy mượt mà trên bảng lớn.

3. **Phiên Âm IPA Chuẩn Quốc Tế 100% & Phát Âm Tự Động:**
   * Hiển thị **phiên âm IPA chuẩn** đồng bộ trên toàn bộ 5 mục: Từ vựng, Câu ví dụ, Mẫu câu + từng cụm tách nhỏ, Ngữ pháp, Dịch câu và Đáp án trò chơi — không dùng phiên âm bồi để các em luyện chuẩn âm đuôi (*ending sounds*).
   * Phát âm tự động bằng Google Translate TTS (có dự phòng Web Speech API) với 2 tốc độ **1.0x (Chuẩn)** và **0.75x (Chậm)**.

4. **Góc Ngữ Pháp Trực Quan & 3 Dạng Câu Khẳng Định (+) · Phủ Định (−) · Nghi Vấn (?):**
   * Mỗi Unit đều có **Sơ đồ Infographic trực quan** riêng (Sơ đồ trường học 3 tầng & chỉ đường, Công thức `like + V-ing` & `Why ➔ Because`, 4 giới từ lớp học & mẹo `Whose ➔ Tên's`, Bảng phân biệt `WERE` vs `DID` ở Quá khứ đơn, Hành trình 4 điểm dã ngoại Việt Nam & mẹo bỏ `-ed` sau `Did`).
   * Trình bày rõ ràng **3 dạng câu Khẳng định (+), Phủ định (−), Nghi vấn (?)** kèm công thức ngắn gọn, giải thích dễ hiểu cho học sinh tiểu học, phiên âm IPA và nút loa bấm nghe từng ví dụ.

5. **Dịch Câu Phản Xạ & Minigame Ôn Tập 10 Câu/Unit:**
   * **Tab 4 (Dịch câu):** Học sinh nhìn tranh và tự nói tiếng Anh trước khi thầy cô bấm mở đáp án kèm IPA và phát âm chuẩn.
   * **Tab 5 (Ôn tập & Trò chơi):** 10 câu hỏi trắc nghiệm hình ảnh + âm thanh mỗi Unit (tổng 50 câu), hiển thị IPA các đáp án và chấm điểm sao khích lệ cả lớp.

---

## 📁 Cấu Trúc Thư Mục Gọn Nhẹ

```text
lesson-6-10/
├── index.html       # Ứng dụng web chính (mở trực tiếp bằng trình duyệt)
├── README.md        # Tài liệu giới thiệu & hướng dẫn
└── assets/          # Toàn bộ hình ảnh chuẩn Việt Nam & đồ họa SVG
```

---

## 🚀 Hướng Dẫn Sử Dụng & Đưa Lên GitHub Pages

* **Mở trực tiếp trên máy tính:** Nhấp đúp vào file `index.html` bằng Chrome hoặc Edge (cần kết nối mạng để tải font chữ và giọng đọc Google TTS).
* **Đưa lên GitHub Pages (miễn phí, chạy trên mọi điện thoại/tivi/máy chiếu):**
  1. Tạo repository mới trên GitHub (ví dụ: `the-hoc-tieng-anh-lop-5-u6-10`) ở chế độ **Public**.
  2. Chọn **Add file → Upload files**, kéo thả `index.html`, `README.md` và thư mục `assets/` vào rồi bấm **Commit changes**.
  3. Vào **Settings → Pages** → Mục **Branch** chọn `main` / `/ (root)` → Bấm **Save**.
  4. Chờ 1–2 phút, mở đường link dạng `https://<ten-tai-khoan>.github.io/<ten-repo>/` để giảng dạy ngay!
