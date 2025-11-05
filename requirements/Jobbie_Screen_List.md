# DANH SÁCH MÀN HÌNH JOBBIE - PHÂN THEO GIAI ĐOẠN

## 📌 Chú giải
- **Đối tượng:** Người dùng tham gia vào màn hình
- **Input:** Dữ liệu đầu vào cần thiết
- **Output:** Kết quả mong muốn sau khi hoàn thành
- **Priority:** P0 (Critical), P1 (High), P2 (Medium), P3 (Low)

---

## 📑 MỤC LỤC (OUTLINE)

### 🚀 [GIAI ĐOẠN 1 - MVP (3 THÁNG ĐẦU)](#-giai-đoạn-1---mvp-3-tháng-đầu) - ~40 màn hình

#### [1. AUTHENTICATION & ONBOARDING](#1-authentication--onboarding) (7 màn hình)
- [1.1. Màn hình Splash Screen](#11-màn-hình-splash-screen)
- [1.2. Màn hình Onboarding (Giới thiệu)](#12-màn-hình-onboarding-giới-thiệu)
- [1.3. Màn hình Đăng ký (Sign Up)](#13-màn-hình-đăng-ký-sign-up)
- [1.4. Màn hình Xác thực OTP](#14-màn-hình-xác-thực-otp)
- [1.5. Màn hình Hoàn thiện hồ sơ](#15-màn-hình-hoàn-thiện-hồ-sơ)
- [1.6. Màn hình Đăng nhập (Login)](#16-màn-hình-đăng-nhập-login)
- [1.7. Màn hình Quên mật khẩu](#17-màn-hình-quên-mật-khẩu)

#### [2. HOME & NAVIGATION](#2-home--navigation) (2 màn hình)
- [2.1. Màn hình Home (Trang chủ)](#21-màn-hình-home-trang-chủ)
- [2.2. Màn hình Bottom Navigation](#22-màn-hình-bottom-navigation)

#### [3. CAREER TEST MODULE](#3-career-test-module) (4 màn hình)
- [3.1. Màn hình Danh sách Bài Test](#31-màn-hình-danh-sách-bài-test)
- [3.2. Màn hình Chi tiết Bài Test (Test Detail)](#32-màn-hình-chi-tiết-bài-test-test-detail)
- [3.3. Màn hình Làm Bài Test (Test Taking)](#33-màn-hình-làm-bài-test-test-taking)
- [3.4. Màn hình Hoàn thành Test](#34-màn-hình-hoàn-thành-test)

#### [4. RESULTS & REPORTS MODULE](#4-results--reports-module) (3 màn hình)
- [4.1. Màn hình Kết quả Cơ bản (Free Result)](#41-màn-hình-kết-quả-cơ-bản-free-result)
- [4.2. Màn hình Báo cáo Chuyên sâu (Premium Report)](#42-màn-hình-báo-cáo-chuyên-sâu-premium-report)
- [4.3. Màn hình Lịch sử Kết quả](#43-màn-hình-lịch-sử-kết-quả)

#### [5. CAREER DATABASE MODULE](#5-career-database-module) (3 màn hình)
- [5.1. Màn hình Khám phá Nghề nghiệp](#51-màn-hình-khám-phá-nghề-nghiệp)
- [5.2. Màn hình Chi tiết Nghề nghiệp](#52-màn-hình-chi-tiết-nghề-nghiệp)
- [5.3. Màn hình Nghề Yêu thích (Saved Careers)](#53-màn-hình-nghề-yêu-thích-saved-careers)

#### [6. USER PROFILE MODULE](#6-user-profile-module) (4 màn hình)
- [6.1. Màn hình Hồ sơ Cá nhân (Profile)](#61-màn-hình-hồ-sơ-cá-nhân-profile)
- [6.2. Màn hình Chỉnh sửa Hồ sơ](#62-màn-hình-chỉnh-sửa-hồ-sơ)
- [6.3. Màn hình Cài đặt (Settings)](#63-màn-hình-cài-đặt-settings)
- [6.4. Màn hình Đổi Mật khẩu](#64-màn-hình-đổi-mật-khẩu)

#### [7. PAYMENT MODULE](#7-payment-module) (5 màn hình)
- [7.1. Màn hình Gói Premium (Premium Plans)](#71-màn-hình-gói-premium-premium-plans)
- [7.2. Màn hình Thanh toán (Payment)](#72-màn-hình-thanh-toán-payment)
- [7.3. Màn hình Thanh toán Thành công](#73-màn-hình-thanh-toán-thành-công)
- [7.4. Màn hình Thanh toán Thất bại](#74-màn-hình-thanh-toán-thất-bại)
- [7.5. Màn hình Lịch sử Thanh toán](#75-màn-hình-lịch-sử-thanh-toán)

#### [8. NOTIFICATION MODULE](#8-notification-module) (1 màn hình)
- [8.1. Màn hình Thông báo (Notifications)](#81-màn-hình-thông-báo-notifications)

#### [9. SUPPORT & HELP MODULE](#9-support--help-module) (2 màn hình)
- [9.1. Màn hình Trợ giúp (Help Center)](#91-màn-hình-trợ-giúp-help-center)
- [9.2. Màn hình Liên hệ Hỗ trợ (Contact Support)](#92-màn-hình-liên-hệ-hỗ-trợ-contact-support)

#### [10. ADMIN MODULE - Web-based](#10-admin-module-web-based) (6 màn hình)
- [10.1. Dashboard Admin](#101-dashboard-admin)
- [10.2. Quản lý Người dùng](#102-quản-lý-người-dùng)
- [10.3. Quản lý Bài Test & Câu hỏi](#103-quản-lý-bài-test--câu-hỏi)
- [10.4. Quản lý Nghề nghiệp](#104-quản-lý-nghề-nghiệp)
- [10.5. Quản lý Giao dịch](#105-quản-lý-giao-dịch)
- [10.6. Quản lý Nội dung & Thông báo](#106-quản-lý-nội-dung--thông-báo)

---

### 🚀 [GIAI ĐOẠN 2 - MỞ RỘNG (THÁNG 4-6)](#-giai-đoạn-2---mở-rộng-tháng-4-6) - +20 màn hình

#### [11. JOB SIMULATOR MODULE](#11-job-simulator-module) (4 màn hình)
- [11.1. Màn hình Danh sách Game Mô phỏng](#111-màn-hình-danh-sách-game-mô-phỏng)
- [11.2. Màn hình Chi tiết Game](#112-màn-hình-chi-tiết-game)
- [11.3. Màn hình Chơi Game (Game Play)](#113-màn-hình-chơi-game-game-play)
- [11.4. Màn hình Kết quả Game](#114-màn-hình-kết-quả-game)

#### [12. MENTOR CONNECT MODULE](#12-mentor-connect-module) (6 màn hình)
- [12.1. Màn hình Danh sách Mentor](#121-màn-hình-danh-sách-mentor)
- [12.2. Màn hình Hồ sơ Mentor](#122-màn-hình-hồ-sơ-mentor)
- [12.3. Màn hình Đặt lịch Mentor](#123-màn-hình-đặt-lịch-mentor)
- [12.4. Màn hình Lịch hẹn của tôi (My Bookings)](#124-màn-hình-lịch-hẹn-của-tôi-my-bookings)
- [12.5. Màn hình Video Call với Mentor](#125-màn-hình-video-call-với-mentor)
- [12.6. Màn hình Đánh giá Mentor](#126-màn-hình-đánh-giá-mentor)

#### [13. AI CAREER COACH MODULE](#13-ai-career-coach-module) (2 màn hình)
- [13.1. Màn hình Chat với AI Coach](#131-màn-hình-chat-với-ai-coach)
- [13.2. Màn hình Lịch sử Chat](#132-màn-hình-lịch-sử-chat)

#### [14. LEARNING PATH MODULE](#14-learning-path-module) (2 màn hình)
- [14.1. Màn hình Lộ trình Học tập](#141-màn-hình-lộ-trình-học-tập)
- [14.2. Màn hình Theo dõi Tiến độ](#142-màn-hình-theo-dõi-tiến-độ)

#### [15. GAMIFICATION MODULE](#15-gamification-module) (1 màn hình)
- [15.1. Màn hình Điểm & Huy hiệu](#151-màn-hình-điểm--huy-hiệu)

---

### 🚀 [GIAI ĐOẠN 3 - HỆ SINH THÁI (THÁNG 7+)](#-giai-đoạn-3---hệ-sinh-thái-tháng-7) - +10 màn hình

#### [16. COMMUNITY MODULE](#16-community-module) (3 màn hình)
- [16.1. Màn hình Cộng đồng (Feed)](#161-màn-hình-cộng-đồng-feed)
- [16.2. Màn hình Tạo Bài viết](#162-màn-hình-tạo-bài-viết)
- [16.3. Màn hình Chi tiết Bài viết](#163-màn-hình-chi-tiết-bài-viết)

#### [17. B2B - SCHOOL MODULE - Web-based](#17-b2b---school-module-web-based) (3 màn hình)
- [17.1. Dashboard Trường học](#171-dashboard-trường-học)
- [17.2. Quản lý Học sinh](#172-quản-lý-học-sinh)
- [17.3. Báo cáo Tổng hợp Lớp](#173-báo-cáo-tổng-hợp-lớp)

#### [18. ADDITIONAL SCREENS](#18-additional-screens) (3 màn hình)
- [18.1. Màn hình Sự kiện & Workshop](#181-màn-hình-sự-kiện--workshop)
- [18.2. Màn hình Giới thiệu Bạn bè (Referral)](#182-màn-hình-giới-thiệu-bạn-bè-referral)
- [18.3. Màn hình Tìm kiếm Toàn cục](#183-màn-hình-tìm-kiếm-toàn-cục)

---

### 📊 [TỔNG KẾT](#-tổng-kết)
- [Thống kê Màn hình theo Giai đoạn](#thống-kê-màn-hình-theo-giai-đoạn)
- [Ưu tiên Phát triển](#ưu-tiên-phát-triển)

---

## 📈 THỐNG KÊ NHANH
- **Tổng số màn hình:** ~70 màn hình
- **Giai đoạn 1 (MVP):** 40 màn hình (P0-P1)
- **Giai đoạn 2 (Mở rộng):** 20 màn hình (P1-P2)
- **Giai đoạn 3 (Hệ sinh thái):** 10 màn hình (P2-P3)

---

# 🚀 GIAI ĐOẠN 1 - MVP (3 THÁNG ĐẦU)

## 1. AUTHENTICATION & ONBOARDING

### 1.1. Màn hình Splash Screen
**Mô tả:** Màn hình khởi động ứng dụng, hiển thị logo Jobbie

**Đối tượng:** Tất cả người dùng

**Công việc:**
- Hiển thị logo và slogan Jobbie
- Kiểm tra trạng thái đăng nhập
- Load dữ liệu cấu hình ban đầu

**Input:** Không

**Output:** 
- Chuyển đến màn hình Onboarding (lần đầu)
- Chuyển đến màn hình Login (chưa đăng nhập)
- Chuyển đến màn hình Home (đã đăng nhập)

**Priority:** P0

---

### 1.2. Màn hình Onboarding (Giới thiệu)
**Mô tả:** Giới thiệu tính năng chính của Jobbie cho người dùng mới

**Đối tượng:** Người dùng lần đầu mở app

**Công việc:**
- Hiển thị 3-4 slide giới thiệu:
  - Slide 1: "Khám phá bản thân qua bài test thông minh"
  - Slide 2: "Tìm nghề phù hợp với tính cách của bạn"
  - Slide 3: "Nhận báo cáo chi tiết và lộ trình phát triển"
  - Slide 4: "Bắt đầu hành trình định hướng nghề nghiệp"
- Nút "Bỏ qua" và "Tiếp theo"
- Nút "Bắt đầu" ở slide cuối

**Input:** Không

**Output:** Chuyển đến màn hình Đăng ký/Đăng nhập

**Priority:** P1

---

### 1.3. Màn hình Đăng ký (Sign Up)
**Mô tả:** Người dùng tạo tài khoản mới

**Đối tượng:** Người dùng chưa có tài khoản

**Công việc:**
- Form đăng ký gồm:
  - Họ và tên (required)
  - Email hoặc Số điện thoại (required)
  - Mật khẩu (required, min 6 ký tự)
  - Xác nhận mật khẩu (required)
  - Checkbox đồng ý điều khoản
- Validation form
- Gửi OTP xác thực (nếu dùng số điện thoại)
- Đăng ký qua Google/Facebook

**Input:** Thông tin cá nhân người dùng

**Output:** 
- Tài khoản được tạo thành công
- Chuyển đến màn hình Hoàn thiện hồ sơ
- Hiển thị lỗi nếu email/phone đã tồn tại

**Priority:** P0

---

### 1.4. Màn hình Xác thực OTP
**Mô tả:** Xác thực số điện thoại/email qua mã OTP

**Đối tượng:** Người dùng đăng ký bằng số điện thoại

**Công việc:**
- Hiển thị thông báo đã gửi OTP
- Input 6 số OTP
- Đếm ngược thời gian (60s)
- Nút "Gửi lại mã"
- Xác thực OTP với backend

**Input:** Mã OTP 6 số

**Output:** 
- Xác thực thành công → Chuyển màn hình tiếp theo
- Xác thực thất bại → Hiển thị lỗi

**Priority:** P0

---

### 1.5. Màn hình Hoàn thiện hồ sơ
**Mô tả:** Thu thập thông tin bổ sung sau khi đăng ký

**Đối tượng:** Người dùng mới đăng ký

**Công việc:**
- Form thu thập:
  - Năm sinh (required)
  - Giới tính (required)
  - Tỉnh/Thành phố (required)
  - Trường đang học (optional)
  - Lớp (optional)
  - Ảnh đại diện (optional)
- Nút "Hoàn thành" và "Bỏ qua"

**Input:** Thông tin cá nhân bổ sung

**Output:** 
- Hồ sơ được lưu vào database
- Chuyển đến màn hình Home

**Priority:** P1

---

### 1.6. Màn hình Đăng nhập (Login)
**Mô tả:** Người dùng đăng nhập vào hệ thống

**Đối tượng:** Người dùng đã có tài khoản

**Công việc:**
- Form đăng nhập:
  - Email/Số điện thoại
  - Mật khẩu
  - Checkbox "Ghi nhớ đăng nhập"
- Nút "Quên mật khẩu?"
- Đăng nhập qua Google/Facebook
- Validation và xác thực với backend

**Input:** Email/Phone + Password

**Output:** 
- Đăng nhập thành công → Chuyển đến Home
- Đăng nhập thất bại → Hiển thị lỗi

**Priority:** P0

---

### 2.2. Màn hình Bottom Navigation
**Mô tả:** Thanh điều hướng chính của ứng dụng

**Đối tượng:** Người dùng đã đăng nhập

**Công việc:**
- 4 tab chính:
  - Tab 1: Trang chủ (Home icon)
  - Tab 2: Bài test (Document icon)
  - Tab 3: Nghề nghiệp (Briefcase icon)
  - Tab 4: Hồ sơ (User icon)
- Highlight tab đang active
- Badge notification (nếu có)

**Input:** User action (tap)

**Output:** Navigate đến màn hình tương ứng

**Priority:** P0

---

## 3. CAREER TEST MODULE

### 3.1. Màn hình Danh sách Bài Test
**Mô tả:** Hiển thị tất cả bài test hướng nghiệp

**Đối tượng:** Người dùng đã đăng nhập

**Công việc:**
- Danh sách 3 bài test chính:
  1. **Test Tính cách** (MBTI rút gọn)
     - Icon, tên test
     - Mô tả ngắn: "Khám phá tính cách của bạn"
     - Thời gian: ~10 phút
     - Số câu hỏi: 20 câu
     - Trạng thái: Chưa làm/Đang làm (50%)/Hoàn thành
     - Nút "Bắt đầu" hoặc "Tiếp tục"

  2. **Test Năng lực** (OCEAN)
     - Tương tự test 1
     - Mô tả: "Đánh giá năng lực cá nhân"
     - 25 câu hỏi, ~12 phút

  3. **Test Sở thích Nghề nghiệp** (Holland)
     - Mô tả: "Tìm nghề phù hợp với sở thích"
     - 30 câu hỏi, ~15 phút

- Hiển thị badge "Miễn phí" hoặc "Premium"
- Gợi ý làm test theo thứ tự

**Input:** User ID, lịch sử test

**Output:**
- Hiển thị danh sách test với trạng thái
- Navigate đến màn hình Test Detail khi tap

**Priority:** P0

---

### 3.2. Màn hình Chi tiết Bài Test (Test Detail)
**Mô tả:** Giới thiệu chi tiết về bài test trước khi bắt đầu

**Đối tượng:** Người dùng chọn một bài test

**Công việc:**
- Header: Tên bài test, icon
- Mô tả chi tiết bài test
- Thông tin:
  - Số câu hỏi
  - Thời gian dự kiến
  - Mục đích của test
  - Bạn sẽ nhận được gì sau khi hoàn thành
- Preview 2-3 câu hỏi mẫu
- Lưu ý khi làm bài:
  - Trả lời trung thực
  - Không có đúng/sai
  - Có thể lưu và quay lại sau
- Nút "Bắt đầu làm bài" (to lớn, nổi bật)
- Nút "Xem kết quả cũ" (nếu đã làm)

**Input:** Test ID

**Output:**
- Navigate đến màn hình Làm bài test
- Hoặc xem kết quả cũ

**Priority:** P0

---

### 3.3. Màn hình Làm Bài Test (Test Taking)
**Mô tả:** Giao diện làm bài test

**Đối tượng:** Người dùng đang làm test

**Công việc:**
- Header:
  - Progress bar (Câu 5/20)
  - Nút "Thoát" (có confirm)
  - Timer (nếu có giới hạn thời gian)

- Body:
  - Hiển thị 1 câu hỏi/màn hình
  - Các dạng câu hỏi:
    * **Multiple Choice:** Chọn 1 đáp án
    * **Rating Scale:** Thang điểm 1-5 (Rất không đồng ý → Rất đồng ý)
    * **Ranking:** Sắp xếp thứ tự ưu tiên
  - Hình ảnh minh họa (nếu có)
  - Animation chuyển câu mượt mà

- Footer:
  - Nút "Quay lại" (câu trước)
  - Nút "Tiếp theo" (câu sau)
  - Nút "Lưu và thoát"

- Auto-save sau mỗi câu trả lời

**Input:** Câu trả lời của user

**Output:**
- Lưu câu trả lời vào database
- Chuyển sang câu tiếp theo
- Hiển thị màn hình Hoàn thành khi hết câu

**Priority:** P0

---

### 3.4. Màn hình Hoàn thành Test
**Mô tả:** Thông báo hoàn thành bài test

**Đối tượng:** Người dùng vừa hoàn thành test

**Công việc:**
- Animation chúc mừng (confetti)
- Icon check/trophy
- Thông báo: "Chúc mừng! Bạn đã hoàn thành bài test"
- Thông tin:
  - Tên bài test
  - Thời gian hoàn thành
  - Số câu đã trả lời
- 2 options:
  1. **"Xem kết quả miễn phí"** (kết quả cơ bản)
  2. **"Nhận báo cáo chuyên sâu"** (Premium - 39.000đ)
     - Hiển thị preview những gì có trong báo cáo premium
     - Badge "Khuyến nghị"

**Input:** Test completion data

**Output:**
- Navigate đến màn hình Kết quả cơ bản
- Hoặc màn hình Thanh toán (nếu chọn Premium)

**Priority:** P0

---

## 4. RESULTS & REPORTS MODULE

### 4.1. Màn hình Kết quả Cơ bản (Free Result)
**Mô tả:** Hiển thị kết quả miễn phí sau khi làm test

**Đối tượng:** Người dùng hoàn thành test

**Công việc:**
- Header: "Kết quả của bạn"
- Section 1: **Nhóm tính cách**
  - Icon/Avatar nhóm tính cách
  - Tên nhóm (VD: "Người sáng tạo - INFP")
  - Mô tả ngắn (2-3 dòng)

- Section 2: **Top 3 Nghề phù hợp**
  - Card 1: Nghề #1 (match 85%)
    - Icon nghề
    - Tên nghề
    - % phù hợp
    - Mô tả 1 dòng
  - Card 2, 3 tương tự
  - Nút "Xem chi tiết nghề"

- Section 3: **Điểm mạnh & Điểm yếu**
  - 3 điểm mạnh nổi bật
  - 2 điểm cần cải thiện
  - Hiển thị dạng bullet points

- Section 4: **Gợi ý định hướng**
  - 2-3 gợi ý ngắn gọn
  - Icon + text

- Banner quảng cáo: "Mở khóa báo cáo chuyên sâu"
  - Preview tính năng premium
  - Giá: 39.000đ
  - Nút "Nâng cấp ngay"

- Footer:
  - Nút "Chia sẻ kết quả" (Facebook, Zalo, Link)
  - Nút "Làm test khác"
  - Nút "Về trang chủ"

**Input:** Test result data

**Output:**
- Hiển thị kết quả cơ bản
- Option nâng cấp Premium
- Share kết quả

**Priority:** P0

---

### 4.2. Màn hình Báo cáo Chuyên sâu (Premium Report)
**Mô tả:** Báo cáo chi tiết sau khi thanh toán

**Đối tượng:** Người dùng mua báo cáo Premium

**Công việc:**
- Header: "Báo cáo chuyên sâu của [Tên user]"
- Nút "Tải PDF" (góc phải)

- **Section 1: Tổng quan**
  - Thông tin cá nhân
  - Ngày làm test
  - Tóm tắt kết quả

- **Section 2: Phân tích Tính cách Chi tiết**
  - Biểu đồ Radar Chart (5-6 chiều)
  - Giải thích từng chiều
  - So sánh với trung bình

- **Section 3: Năng lực & Kỹ năng**
  - Bảng đánh giá năng lực (10+ kỹ năng)
  - Progress bar cho mỗi kỹ năng
  - Điểm số cụ thể

- **Section 4: Top 10 Nghề phù hợp**
  - Danh sách 10 nghề
  - % match chi tiết
  - Lý do phù hợp
  - Yêu cầu kỹ năng
  - Mức lương trung bình
  - Triển vọng nghề

- **Section 5: Kỹ năng cần Phát triển**
  - Danh sách 5-7 kỹ năng
  - Mức độ ưu tiên
  - Gợi ý cách phát triển

- **Section 6: Lộ trình Định hướng**
  - Timeline 3-5 năm
  - Các mốc quan trọng
  - Hành động cụ thể

- **Section 7: Gợi ý Học tập**
  - Ngành học phù hợp
  - Trường đại học đề xuất
  - Khóa học online

- Footer:
  - Nút "Tải PDF"
  - Nút "Chia sẻ"
  - Nút "Đặt lịch tư vấn với Mentor" (CTA)

**Input:** Test result + Payment confirmation

**Output:**
- Hiển thị báo cáo đầy đủ
- File PDF có thể tải về
- Option đặt lịch mentor

**Priority:** P0

---

### 4.3. Màn hình Lịch sử Kết quả
**Mô tả:** Xem lại các lần làm test trước đó

**Đối tượng:** Người dùng đã làm test nhiều lần

**Công việc:**
- Header: "Lịch sử kết quả"
- Danh sách các lần làm test:
  - Card cho mỗi lần test:
    - Tên bài test
    - Ngày làm
    - Kết quả chính (tính cách/nghề)
    - Badge "Premium" nếu đã mua
    - Nút "Xem chi tiết"
- Filter: Theo loại test, theo thời gian
- So sánh kết quả (nếu làm cùng test nhiều lần):
  - Biểu đồ thay đổi theo thời gian
  - Highlight sự khác biệt

**Input:** User ID, test history

**Output:**
- Danh sách lịch sử test
- Navigate đến kết quả cụ thể
- So sánh kết quả

**Priority:** P1

---

## 5. CAREER DATABASE MODULE

### 5.1. Màn hình Khám phá Nghề nghiệp
**Mô tả:** Tìm hiểu về các nghề nghiệp

**Đối tượng:** Tất cả người dùng

**Công việc:**
- Search bar: Tìm kiếm nghề theo tên
- Filter:
  - Theo ngành (IT, Y tế, Kinh doanh, Nghệ thuật...)
  - Theo mức lương
  - Theo triển vọng
  - Theo tính cách phù hợp
- Tabs:
  - "Tất cả"
  - "Nghề hot" (trending)
  - "Nghề mới nổi"
  - "Phù hợp với bạn" (nếu đã làm test)
- Grid/List view các nghề:
  - Card nghề:
    - Icon/Hình ảnh
    - Tên nghề
    - Mô tả 1 dòng
    - Mức lương trung bình
    - Badge "Hot" hoặc "Mới"
    - Icon bookmark (lưu nghề yêu thích)

**Input:** Search query, filters

**Output:**
- Danh sách nghề phù hợp
- Navigate đến Chi tiết nghề

**Priority:** P0

---

### 5.2. Màn hình Chi tiết Nghề nghiệp
**Mô tả:** Thông tin đầy đủ về một nghề

**Đối tượng:** Người dùng quan tâm đến nghề cụ thể

**Công việc:**
- Header:
  - Hình ảnh nghề
  - Tên nghề
  - Icon bookmark (lưu/bỏ lưu)
  - Icon share

- **Section 1: Tổng quan**
  - Mô tả nghề (2-3 đoạn)
  - Công việc hàng ngày
  - Môi trường làm việc

- **Section 2: Yêu cầu**
  - Bằng cấp cần thiết
  - Kỹ năng cần có (list + progress bar)
  - Tính cách phù hợp
  - Kinh nghiệm

- **Section 3: Thu nhập**
  - Mức lương trung bình
  - Biểu đồ lương theo kinh nghiệm
  - Phúc lợi thường gặp

- **Section 4: Triển vọng**
  - Nhu cầu tuyển dụng
  - Xu hướng phát triển
  - Cơ hội thăng tiến

- **Section 5: Lộ trình phát triển**
  - Timeline từ junior → senior
  - Các vị trí liên quan

- **Section 6: Đào tạo**
  - Các trường đại học đào tạo
  - Ngành học liên quan
  - Khóa học online đề xuất

- **Section 7: Nghề liên quan**
  - 4-6 nghề tương tự
  - Horizontal scroll

- CTA:
  - "Làm test để biết bạn có phù hợp?" (nếu chưa test)
  - "Tìm mentor trong ngành" (link đến Mentor - giai đoạn 2)
  - "Lưu vào danh sách yêu thích"

**Input:** Career ID

**Output:**
- Hiển thị thông tin đầy đủ về nghề
- Lưu nghề yêu thích
- Navigate đến Test hoặc Mentor

**Priority:** P0

---

### 5.3. Màn hình Nghề Yêu thích (Saved Careers)
**Mô tả:** Danh sách nghề đã lưu

**Đối tượng:** Người dùng đã bookmark nghề

**Công việc:**
- Header: "Nghề yêu thích của bạn"
- Grid/List các nghề đã lưu
- Tương tự card ở màn hình Khám phá
- Swipe to delete
- Empty state nếu chưa lưu nghề nào

**Input:** User ID

**Output:**
- Danh sách nghề đã lưu
- Navigate đến Chi tiết nghề

**Priority:** P2

---

## 6. USER PROFILE MODULE

### 6.1. Màn hình Hồ sơ Cá nhân (Profile)
**Mô tả:** Thông tin và cài đặt tài khoản

**Đối tượng:** Người dùng đã đăng nhập

**Công việc:**
- Header:
  - Ảnh đại diện (có thể đổi)
  - Tên người dùng
  - Email/Phone
  - Badge Premium (nếu có)

- **Section 1: Thông tin cá nhân**
  - Năm sinh
  - Giới tính
  - Tỉnh/Thành phố
  - Trường học
  - Lớp
  - Nút "Chỉnh sửa"

- **Section 2: Thống kê**
  - Số bài test đã làm
  - Số nghề đã khám phá
  - Số báo cáo Premium
  - Điểm tích lũy (gamification)

- **Section 3: Gói Premium**
  - Trạng thái: Free/Premium
  - Ngày hết hạn (nếu có)
  - Nút "Nâng cấp" hoặc "Gia hạn"

- **Section 4: Menu**
  - Lịch sử kết quả
  - Nghề yêu thích
  - Lịch sử thanh toán
  - Cài đặt
  - Trợ giúp & Hỗ trợ
  - Điều khoản & Chính sách
  - Đăng xuất

**Input:** User ID

**Output:**
- Hiển thị thông tin user
- Navigate đến các màn hình con

**Priority:** P0

---

### 6.2. Màn hình Chỉnh sửa Hồ sơ
**Mô tả:** Cập nhật thông tin cá nhân

**Đối tượng:** Người dùng muốn sửa thông tin

**Công việc:**
- Form chỉnh sửa:
  - Upload/Đổi ảnh đại diện
  - Họ và tên
  - Năm sinh
  - Giới tính
  - Tỉnh/Thành phố
  - Trường học
  - Lớp
- Validation
- Nút "Lưu" và "Hủy"

**Input:** Thông tin mới

**Output:**
- Cập nhật database
- Quay lại màn hình Profile
- Hiển thị thông báo thành công

**Priority:** P1

---

### 6.3. Màn hình Cài đặt (Settings)
**Mô tả:** Cấu hình ứng dụng

**Đối tượng:** Người dùng đã đăng nhập

**Công việc:**
- **Tài khoản:**
  - Đổi mật khẩu
  - Liên kết tài khoản (Google, Facebook)
  - Xóa tài khoản

- **Thông báo:**
  - Bật/tắt push notification
  - Bật/tắt email notification
  - Thông báo test mới
  - Thông báo khuyến mãi

- **Giao diện:**
  - Chế độ sáng/tối (Dark mode)
  - Ngôn ngữ (Tiếng Việt/English)

- **Quyền riêng tư:**
  - Chia sẻ kết quả công khai/riêng tư
  - Cho phép trường học xem kết quả

- **Khác:**
  - Xóa cache
  - Phiên bản ứng dụng

**Input:** User preferences

**Output:**
- Lưu cài đặt
- Apply thay đổi

**Priority:** P1

---

### 6.4. Màn hình Đổi Mật khẩu
**Mô tả:** Thay đổi mật khẩu tài khoản

**Đối tượng:** Người dùng muốn đổi mật khẩu

**Công việc:**
- Form:
  - Mật khẩu hiện tại
  - Mật khẩu mới
  - Xác nhận mật khẩu mới
- Validation:
  - Mật khẩu hiện tại đúng
  - Mật khẩu mới >= 6 ký tự
  - Xác nhận khớp
- Nút "Lưu"

**Input:** Mật khẩu cũ và mới

**Output:**
- Cập nhật mật khẩu
- Hiển thị thông báo thành công
- Đăng xuất và yêu cầu đăng nhập lại

**Priority:** P2

---

## 7. PAYMENT MODULE

### 7.1. Màn hình Gói Premium (Premium Plans)
**Mô tả:** Giới thiệu các gói Premium

**Đối tượng:** Người dùng Free muốn nâng cấp

**Công việc:**
- Header: "Nâng cấp Premium để mở khóa toàn bộ tính năng"

- So sánh gói Free vs Premium (bảng)

- **Các gói Premium:**

  **Gói 1: Báo cáo Đơn lẻ**
  - Giá: 39.000đ/lượt
  - Báo cáo chuyên sâu cho 1 bài test
  - Tải PDF
  - Nút "Mua ngay"

  **Gói 2: Premium Tháng** (Badge "Phổ biến")
  - Giá: 99.000đ/tháng
  - Không giới hạn test
  - Tất cả báo cáo chuyên sâu
  - Tải PDF không giới hạn
  - Ưu tiên hỗ trợ
  - Nút "Đăng ký"

  **Gói 3: Premium Quý**
  - Giá: 249.000đ/3 tháng (tiết kiệm 16%)
  - Tất cả tính năng gói Tháng
  - Tặng 1 session mentor (giai đoạn 2)
  - Nút "Đăng ký"

  **Gói 4: Premium Năm** (Badge "Giá trị nhất")
  - Giá: 799.000đ/năm (tiết kiệm 33%)
  - Tất cả tính năng
  - Tặng 3 session mentor
  - Ưu tiên truy cập tính năng mới
  - Nút "Đăng ký"

- FAQ về Premium
- Chính sách hoàn tiền

**Input:** Không

**Output:**
- Navigate đến màn hình Thanh toán
- Chọn gói Premium

**Priority:** P0

---

### 7.2. Màn hình Thanh toán (Payment)
**Mô tả:** Xử lý thanh toán cho Premium

**Đối tượng:** Người dùng chọn mua Premium

**Công việc:**
- Header: "Thanh toán"

- **Thông tin đơn hàng:**
  - Tên gói/sản phẩm
  - Giá gốc
  - Giảm giá (nếu có)
  - Tổng thanh toán

- **Mã giảm giá:**
  - Input mã
  - Nút "Áp dụng"
  - Hiển thị số tiền giảm

- **Phương thức thanh toán:**
  - Radio buttons:
    - VNPay
    - MoMo
    - ZaloPay
    - Thẻ ngân hàng (ATM/Visa/Mastercard)
  - Icon của từng phương thức

- **Thông tin thanh toán:**
  - Họ tên
  - Email (nhận hóa đơn)
  - Số điện thoại

- Checkbox "Đồng ý điều khoản thanh toán"

- Nút "Thanh toán" (to, nổi bật)

- Badge bảo mật: "Thanh toán an toàn 100%"

**Input:** Gói Premium, phương thức thanh toán

**Output:**
- Redirect đến cổng thanh toán
- Xử lý callback sau thanh toán
- Cập nhật trạng thái Premium

**Priority:** P0

---

### 7.3. Màn hình Thanh toán Thành công
**Mô tả:** Xác nhận thanh toán thành công

**Đối tượng:** Người dùng thanh toán thành công

**Công việc:**
- Icon check/success
- Animation chúc mừng
- Thông báo: "Thanh toán thành công!"
- Thông tin:
  - Mã giao dịch
  - Gói đã mua
  - Số tiền
  - Ngày thanh toán
  - Ngày hết hạn (nếu subscription)
- Nút "Tải hóa đơn"
- Nút "Xem báo cáo Premium" (nếu mua báo cáo)
- Nút "Về trang chủ"

**Input:** Payment confirmation

**Output:**
- Hiển thị thông tin giao dịch
- Gửi email hóa đơn
- Cập nhật trạng thái user

**Priority:** P0

---

### 7.4. Màn hình Thanh toán Thất bại
**Mô tả:** Thông báo thanh toán không thành công

**Đối tượng:** Người dùng thanh toán thất bại

**Công việc:**
- Icon error
- Thông báo: "Thanh toán không thành công"
- Lý do thất bại (nếu có)
- Gợi ý:
  - Kiểm tra số dư
  - Kiểm tra thông tin thẻ
  - Thử phương thức khác
- Nút "Thử lại"
- Nút "Liên hệ hỗ trợ"
- Nút "Về trang chủ"

**Input:** Payment error

**Output:**
- Hiển thị lỗi
- Option thử lại hoặc liên hệ

**Priority:** P1

---

### 7.5. Màn hình Lịch sử Thanh toán
**Mô tả:** Xem lại các giao dịch đã thực hiện

**Đối tượng:** Người dùng đã thanh toán

**Công việc:**
- Header: "Lịch sử thanh toán"
- Danh sách giao dịch:
  - Card cho mỗi giao dịch:
    - Ngày giao dịch
    - Tên gói/sản phẩm
    - Số tiền
    - Trạng thái: Thành công/Thất bại/Đang xử lý
    - Phương thức thanh toán
    - Nút "Xem chi tiết"
    - Nút "Tải hóa đơn"
- Filter: Theo thời gian, theo trạng thái
- Empty state nếu chưa có giao dịch

**Input:** User ID

**Output:**
- Danh sách giao dịch
- Tải hóa đơn PDF

**Priority:** P2

---

## 8. NOTIFICATION MODULE

### 8.1. Màn hình Thông báo (Notifications)
**Mô tả:** Danh sách thông báo của người dùng

**Đối tượng:** Người dùng đã đăng nhập

**Công việc:**
- Header: "Thông báo"
- Tabs:
  - "Tất cả"
  - "Chưa đọc"
  - "Đã đọc"
- Danh sách thông báo:
  - Icon theo loại thông báo
  - Tiêu đề
  - Nội dung ngắn
  - Thời gian
  - Dot màu xanh nếu chưa đọc
  - Swipe to delete
- Các loại thông báo:
  - Test mới
  - Kết quả test
  - Khuyến mãi
  - Cập nhật hệ thống
  - Nhắc nhở làm test
- Nút "Đánh dấu tất cả đã đọc"
- Empty state nếu không có thông báo

**Input:** User ID

**Output:**
- Danh sách thông báo
- Navigate đến nội dung liên quan
- Đánh dấu đã đọc

**Priority:** P1

---

## 9. SUPPORT & HELP MODULE

### 9.1. Màn hình Trợ giúp (Help Center)
**Mô tả:** Hướng dẫn sử dụng và FAQ

**Đối tượng:** Tất cả người dùng

**Công việc:**
- Search bar: Tìm kiếm câu hỏi
- **Danh mục:**
  - Bắt đầu với Jobbie
  - Làm bài test
  - Hiểu kết quả
  - Thanh toán & Premium
  - Tài khoản & Bảo mật
  - Khác
- Mỗi danh mục có list câu hỏi thường gặp
- Expandable accordion cho câu trả lời
- Video hướng dẫn (nếu có)
- Nút "Liên hệ hỗ trợ" (sticky bottom)

**Input:** Search query

**Output:**
- Hiển thị FAQ phù hợp
- Navigate đến Contact Support

**Priority:** P2

---

### 9.2. Màn hình Liên hệ Hỗ trợ (Contact Support)
**Mô tả:** Gửi yêu cầu hỗ trợ

**Đối tượng:** Người dùng cần trợ giúp

**Công việc:**
- Form liên hệ:
  - Họ tên (auto-fill nếu đã đăng nhập)
  - Email (auto-fill)
  - Số điện thoại
  - Chủ đề (dropdown):
    - Vấn đề kỹ thuật
    - Thanh toán
    - Kết quả test
    - Góp ý
    - Khác
  - Mô tả chi tiết (textarea)
  - Upload ảnh (nếu cần)
- Nút "Gửi"
- Thông tin liên hệ khác:
  - Email: support@jobbie.vn
  - Hotline: 1900 xxxx
  - Facebook: fb.com/jobbie
  - Giờ làm việc: 8h-22h hàng ngày

**Input:** Support request

**Output:**
- Gửi ticket hỗ trợ
- Hiển thị thông báo "Đã gửi thành công"
- Email xác nhận

**Priority:** P2

---

## 10. ADMIN MODULE (Web-based)

### 10.1. Dashboard Admin
**Mô tả:** Tổng quan hệ thống

**Đối tượng:** Admin

**Công việc:**
- **Thống kê tổng quan:**
  - Tổng số người dùng
  - Người dùng mới (hôm nay/tuần/tháng)
  - Số bài test đã làm
  - Tỷ lệ chuyển đổi Premium
  - Doanh thu (hôm nay/tuần/tháng)
- **Biểu đồ:**
  - Người dùng theo thời gian (line chart)
  - Doanh thu theo thời gian
  - Phân bố test (pie chart)
  - Phân bố nghề phổ biến
- **Hoạt động gần đây:**
  - Người dùng mới đăng ký
  - Test mới hoàn thành
  - Giao dịch mới
- Quick actions:
  - Thêm nghề mới
  - Thêm câu hỏi test
  - Gửi thông báo

**Input:** Admin credentials

**Output:**
- Dashboard với metrics
- Navigate đến các module quản lý

**Priority:** P1

---

### 10.2. Quản lý Người dùng
**Mô tả:** Xem và quản lý users

**Đối tượng:** Admin

**Công việc:**
- Bảng danh sách users:
  - ID
  - Tên
  - Email/Phone
  - Ngày đăng ký
  - Trạng thái (Free/Premium)
  - Số test đã làm
  - Actions: Xem/Sửa/Khóa/Xóa
- Search và filter:
  - Theo tên, email
  - Theo trạng thái
  - Theo ngày đăng ký
- Pagination
- Export Excel

**Input:** Admin action

**Output:**
- Danh sách users
- CRUD operations

**Priority:** P1

---

### 10.3. Quản lý Bài Test & Câu hỏi
**Mô tả:** Tạo và chỉnh sửa test

**Đối tượng:** Admin, Content Manager

**Công việc:**
- **Danh sách bài test:**
  - Tên test
  - Số câu hỏi
  - Trạng thái: Active/Inactive
  - Actions: Xem/Sửa/Xóa

- **Thêm/Sửa bài test:**
  - Tên test
  - Mô tả
  - Loại test (MBTI/OCEAN/Holland)
  - Thời gian
  - Trạng thái

- **Quản lý câu hỏi:**
  - Danh sách câu hỏi của test
  - Thêm câu hỏi:
    - Nội dung câu hỏi
    - Loại câu hỏi (Multiple choice/Rating/Ranking)
    - Đáp án
    - Điểm số cho mỗi đáp án
    - Mapping với tính cách/nghề
  - Sắp xếp thứ tự câu hỏi (drag & drop)
  - Import/Export Excel

**Input:** Test data, questions

**Output:**
- Tạo/cập nhật test
- Quản lý câu hỏi

**Priority:** P0

---

### 10.4. Quản lý Nghề nghiệp
**Mô tả:** Thêm và cập nhật thông tin nghề

**Đối tượng:** Admin, Content Manager

**Công việc:**
- **Danh sách nghề:**
  - Tên nghề
  - Ngành
  - Trạng thái
  - Actions: Xem/Sửa/Xóa

- **Thêm/Sửa nghề:**
  - Tên nghề
  - Icon/Hình ảnh
  - Ngành (dropdown)
  - Mô tả chi tiết (rich text editor)
  - Công việc hàng ngày
  - Yêu cầu kỹ năng (multi-select)
  - Tính cách phù hợp (mapping với MBTI/Holland)
  - Mức lương (min-max)
  - Triển vọng
  - Trường đào tạo
  - Khóa học liên quan
  - Nghề liên quan
  - Tags (Hot/Mới/Trending)
  - Trạng thái (Active/Inactive)

- Import/Export Excel
- Bulk actions

**Input:** Career data

**Output:**
- Tạo/cập nhật nghề
- Database nghề nghiệp

**Priority:** P0

---

### 10.5. Quản lý Giao dịch
**Mô tả:** Theo dõi và quản lý thanh toán

**Đối tượng:** Admin, Finance

**Công việc:**
- Bảng danh sách giao dịch:
  - Mã giao dịch
  - User
  - Gói/Sản phẩm
  - Số tiền
  - Phương thức
  - Trạng thái
  - Ngày giao dịch
  - Actions: Xem chi tiết/Hoàn tiền
- Filter:
  - Theo trạng thái
  - Theo phương thức
  - Theo thời gian
  - Theo gói
- Thống kê:
  - Tổng doanh thu
  - Doanh thu theo gói
  - Doanh thu theo phương thức
- Export báo cáo Excel/PDF

**Input:** Admin query

**Output:**
- Danh sách giao dịch
- Báo cáo doanh thu

**Priority:** P1

---

### 10.6. Quản lý Nội dung & Thông báo
**Mô tả:** Gửi thông báo và quản lý content

**Đối tượng:** Admin, Marketing

**Công việc:**
- **Gửi thông báo:**
  - Chọn đối tượng:
    - Tất cả user
    - User Free
    - User Premium
    - User cụ thể
  - Tiêu đề
  - Nội dung
  - Link đính kèm
  - Hình ảnh
  - Lên lịch gửi
  - Nút "Gửi ngay" hoặc "Lên lịch"

- **Quản lý Banner/Popup:**
  - Tạo banner trang chủ
  - Popup khuyến mãi
  - Thời gian hiển thị
  - Target audience

- **Lịch sử thông báo:**
  - Danh sách đã gửi
  - Số người nhận
  - Tỷ lệ mở
  - Tỷ lệ click

**Input:** Notification content

**Output:**
- Gửi push notification
- Hiển thị banner/popup

**Priority:** P2

---

# 🚀 GIAI ĐOẠN 2 - MỞ RỘNG (THÁNG 4-6)

## 11. JOB SIMULATOR MODULE

### 11.1. Màn hình Danh sách Game Mô phỏng
**Mô tả:** Các mini game mô phỏng nghề nghiệp

**Đối tượng:** User Premium hoặc Free (giới hạn)

**Công việc:**
- Grid các game:
  - Card game:
    - Hình ảnh/Icon nghề
    - Tên game (VD: "Một ngày làm Designer")
    - Mô tả ngắn
    - Thời gian chơi (~5-10 phút)
    - Độ khó: Dễ/Trung bình/Khó
    - Badge "Mới" hoặc "Hot"
    - Lock icon nếu Premium
    - Nút "Chơi ngay"
- Filter theo ngành nghề
- Leaderboard (top players)

**Input:** User ID, Premium status

**Output:**
- Danh sách game
- Navigate đến Game Detail

**Priority:** P1

---

### 11.2. Màn hình Chi tiết Game
**Mô tả:** Giới thiệu game trước khi chơi

**Đối tượng:** User chọn game

**Công việc:**
- Header: Tên game, hình ảnh
- Mô tả game:
  - Bạn sẽ làm gì
  - Kỹ năng được đánh giá
  - Cách chơi
- Thông tin:
  - Thời gian
  - Điểm cao nhất của bạn
  - Top 3 leaderboard
- Preview screenshot
- Nút "Bắt đầu chơi"
- Nút "Xem kết quả cũ"

**Input:** Game ID

**Output:**
- Navigate đến Game Play
- Hoặc xem kết quả cũ

**Priority:** P1

---

### 11.3. Màn hình Chơi Game (Game Play)
**Mô tả:** Giao diện chơi mini game

**Đối tượng:** User đang chơi game

**Công việc:**
- Header:
  - Timer đếm ngược
  - Điểm hiện tại
  - Nút pause/exit

- Game content (tùy loại nghề):
  - **VD Game Designer:**
    - Chọn màu sắc phù hợp
    - Sắp xếp layout
    - Matching style
  - **VD Game Developer:**
    - Debug code đơn giản
    - Logic puzzle
    - Sequence matching
  - **VD Game Marketing:**
    - Chọn target audience
    - Tạo slogan
    - Budget allocation

- Feedback real-time:
  - Đúng/Sai
  - Điểm cộng
  - Combo streak

- Progress bar (level/stage)

**Input:** User actions trong game

**Output:**
- Tính điểm
- Đánh giá kỹ năng
- Chuyển đến màn hình Kết quả game

**Priority:** P1

---

### 11.4. Màn hình Kết quả Game
**Mô tả:** Hiển thị kết quả sau khi chơi

**Đối tượng:** User hoàn thành game

**Công việc:**
- Animation kết quả
- Điểm số:
  - Điểm của bạn
  - Điểm cao nhất
  - Xếp hạng (Top X%)
- Đánh giá kỹ năng:
  - Các kỹ năng được test
  - Điểm từng kỹ năng
  - Biểu đồ radar
- Nhận xét:
  - Điểm mạnh
  - Cần cải thiện
- Gợi ý:
  - "Bạn có tiềm năng với nghề X"
  - "Thử game Y để khám phá thêm"
- Nút "Chơi lại"
- Nút "Chia sẻ kết quả"
- Nút "Khám phá nghề này"

**Input:** Game result data

**Output:**
- Hiển thị kết quả
- Lưu vào lịch sử
- Share hoặc chơi lại

**Priority:** P1

---

## 12. MENTOR CONNECT MODULE

### 12.1. Màn hình Danh sách Mentor
**Mô tả:** Tìm và chọn mentor

**Đối tượng:** User Premium hoặc mua session

**Công việc:**
- Search bar: Tìm theo tên, ngành
- Filter:
  - Theo ngành nghề
  - Theo kinh nghiệm
  - Theo giá (thấp → cao)
  - Theo rating
  - Theo lịch trống

- Grid/List mentor:
  - Card mentor:
    - Ảnh đại diện
    - Tên mentor
    - Chức danh hiện tại
    - Công ty
    - Chuyên môn (tags)
    - Rating (⭐ 4.8/5)
    - Số review
    - Giá/session (VD: 200.000đ/60 phút)
    - Badge "Top Mentor" hoặc "Mới"
    - Nút "Xem hồ sơ"

- Sort: Phổ biến/Mới/Giá/Rating

**Input:** Search query, filters

**Output:**
- Danh sách mentor phù hợp
- Navigate đến Mentor Profile

**Priority:** P1

---

### 12.2. Màn hình Hồ sơ Mentor
**Mô tả:** Thông tin chi tiết về mentor

**Đối tượng:** User quan tâm đến mentor

**Công việc:**
- Header:
  - Ảnh đại diện lớn
  - Tên mentor
  - Chức danh & Công ty
  - Badge verified
  - Icon bookmark (lưu mentor)

- **Section 1: Giới thiệu**
  - Bio (2-3 đoạn)
  - Video giới thiệu (nếu có)

- **Section 2: Chuyên môn**
  - Lĩnh vực tư vấn
  - Kinh nghiệm (số năm)
  - Kỹ năng chính

- **Section 3: Thành tích**
  - Học vấn
  - Kinh nghiệm làm việc
  - Chứng chỉ
  - Dự án nổi bật

- **Section 4: Dịch vụ**
  - Các gói tư vấn:
    - Tư vấn định hướng (60 phút) - 200.000đ
    - Review CV (30 phút) - 100.000đ
    - Mock interview (45 phút) - 150.000đ
  - Nút "Đặt lịch" cho mỗi gói

- **Section 5: Đánh giá**
  - Rating tổng quan
  - Số lượng session đã tư vấn
  - Danh sách review:
    - Avatar user
    - Tên user
    - Rating
    - Nội dung review
    - Ngày
  - Nút "Xem thêm"

- **Section 6: Lịch trống**
  - Calendar view
  - Các slot còn trống

- CTA sticky bottom:
  - Nút "Đặt lịch tư vấn"

**Input:** Mentor ID

**Output:**
- Hiển thị thông tin mentor
- Navigate đến Booking

**Priority:** P1

---

### 12.3. Màn hình Đặt lịch Mentor
**Mô tả:** Chọn thời gian và thanh toán session

**Đối tượng:** User muốn đặt lịch

**Công việc:**
- **Step 1: Chọn dịch vụ**
  - Radio buttons các gói tư vấn
  - Hiển thị giá

- **Step 2: Chọn ngày & giờ**
  - Calendar picker
  - Hiển thị slot trống (màu xanh)
  - Slot đã đặt (màu xám)
  - Chọn khung giờ cụ thể

- **Step 3: Thông tin**
  - Họ tên (auto-fill)
  - Email (auto-fill)
  - Số điện thoại
  - Ghi chú cho mentor (optional)
  - Chủ đề muốn tư vấn

- **Step 4: Xác nhận**
  - Tóm tắt booking:
    - Mentor
    - Dịch vụ
    - Ngày giờ
    - Giá
  - Phương thức:
    - Video call (Google Meet/Zoom)
    - Voice call
  - Checkbox đồng ý điều khoản

- Nút "Thanh toán"

**Input:** Booking details

**Output:**
- Navigate đến Payment
- Tạo booking (pending)

**Priority:** P1

---

### 12.4. Màn hình Lịch hẹn của tôi (My Bookings)
**Mô tả:** Quản lý các buổi tư vấn

**Đối tượng:** User đã đặt lịch

**Công việc:**
- Tabs:
  - "Sắp tới"
  - "Đã hoàn thành"
  - "Đã hủy"

- Danh sách booking:
  - Card booking:
    - Ảnh mentor
    - Tên mentor
    - Dịch vụ
    - Ngày giờ
    - Trạng thái: Đã xác nhận/Chờ xác nhận/Hoàn thành/Đã hủy
    - Nút "Join" (nếu sắp tới, trong vòng 15 phút)
    - Nút "Hủy lịch" (nếu trước 24h)
    - Nút "Đánh giá" (nếu đã hoàn thành)
    - Nút "Đặt lại"

- Notification trước buổi hẹn (15 phút, 1 giờ, 1 ngày)

**Input:** User ID

**Output:**
- Danh sách booking
- Join video call
- Hủy/Đánh giá

**Priority:** P1

---

### 12.5. Màn hình Video Call với Mentor
**Mô tả:** Giao diện tư vấn trực tuyến

**Đối tượng:** User và Mentor trong session

**Công việc:**
- Video call interface:
  - Video mentor (lớn)
  - Video user (nhỏ, góc)
  - Nút mute/unmute
  - Nút camera on/off
  - Nút share screen
  - Chat box (sidebar)
  - Nút "Kết thúc cuộc gọi"

- Timer hiển thị thời gian còn lại

- Ghi chú trong cuộc gọi:
  - Notepad để ghi chép
  - Auto-save

- Thông báo khi còn 5 phút

**Input:** Booking ID

**Output:**
- Video call session
- Ghi chú được lưu
- Kết thúc → Màn hình Đánh giá

**Priority:** P1

---

### 12.6. Màn hình Đánh giá Mentor
**Mô tả:** Đánh giá sau buổi tư vấn

**Đối tượng:** User hoàn thành session

**Công việc:**
- Header: "Đánh giá buổi tư vấn"
- Thông tin session:
  - Mentor
  - Dịch vụ
  - Ngày giờ

- Form đánh giá:
  - Rating (1-5 sao)
  - Đánh giá chi tiết:
    - Chuyên môn (1-5 sao)
    - Thái độ (1-5 sao)
    - Hữu ích (1-5 sao)
  - Nội dung review (textarea)
  - Checkbox "Đăng công khai"

- Nút "Gửi đánh giá"
- Nút "Bỏ qua"

**Input:** Rating & review

**Output:**
- Lưu đánh giá
- Hiển thị trên profile mentor
- Quay về My Bookings

**Priority:** P2

---

## 13. AI CAREER COACH MODULE

### 13.1. Màn hình Chat với AI Coach
**Mô tả:** Chatbot tư vấn nghề nghiệp

**Đối tượng:** User Premium

**Công việc:**
- Header:
  - Avatar AI Coach
  - Tên: "Jobbie AI Coach"
  - Status: Online
  - Nút "Lịch sử chat"

- Chat interface:
  - Tin nhắn AI (bên trái):
    - Avatar
    - Nội dung
    - Thời gian
    - Quick replies (buttons)
  - Tin nhắn user (bên phải):
    - Nội dung
    - Thời gian

- Suggested questions (khi bắt đầu):
  - "Nghề nào phù hợp với tôi?"
  - "Làm sao để phát triển kỹ năng X?"
  - "Tôi nên học ngành gì?"
  - "Lộ trình để trở thành Y?"

- Input box:
  - Textarea
  - Nút gửi
  - Icon attach (gửi ảnh kết quả test)

- AI features:
  - Trả lời câu hỏi về nghề
  - Gợi ý lộ trình
  - Phân tích kết quả test
  - Đề xuất khóa học
  - Nhắc nhở mục tiêu

**Input:** User messages

**Output:**
- AI responses
- Lưu lịch sử chat
- Gợi ý hành động

**Priority:** P2

---

### 13.2. Màn hình Lịch sử Chat
**Mô tả:** Xem lại các cuộc trò chuyện

**Đối tượng:** User đã chat với AI

**Công việc:**
- Danh sách conversations:
  - Card conversation:
    - Tiêu đề (câu hỏi đầu tiên)
    - Preview tin nhắn cuối
    - Ngày
    - Nút "Tiếp tục"
    - Swipe to delete

- Search conversations
- Nút "Bắt đầu chat mới"

**Input:** User ID

**Output:**
- Danh sách chat
- Navigate đến conversation

**Priority:** P3

---

## 14. LEARNING PATH MODULE

### 14.1. Màn hình Lộ trình Học tập
**Mô tả:** Roadmap phát triển kỹ năng cá nhân hóa

**Đối tượng:** User Premium, đã làm test

**Công việc:**
- Header: "Lộ trình của bạn"
- Chọn mục tiêu:
  - Dropdown nghề mục tiêu
  - Thời gian (6 tháng/1 năm/2 năm)

- Timeline view:
  - **Phase 1: Nền tảng (Tháng 1-3)**
    - Kỹ năng cần học
    - Khóa học đề xuất
    - Sách/Tài liệu
    - Dự án thực hành
    - Checkbox hoàn thành

  - **Phase 2: Nâng cao (Tháng 4-6)**
    - Tương tự Phase 1

  - **Phase 3: Chuyên sâu (Tháng 7-12)**
    - Tương tự

- Progress bar tổng thể
- Milestone achievements

- Khóa học đề xuất:
  - Card khóa học:
    - Hình ảnh
    - Tên khóa học
    - Nền tảng (Coursera/Udemy...)
    - Giá
    - Rating
    - Thời lượng
    - Nút "Xem chi tiết"
    - Badge "Miễn phí" hoặc "Giảm giá"

**Input:** User goal, test results

**Output:**
- Lộ trình cá nhân hóa
- Danh sách khóa học
- Theo dõi tiến độ

**Priority:** P2

---

### 14.2. Màn hình Theo dõi Tiến độ
**Mô tả:** Quản lý quá trình học tập

**Đối tượng:** User đang theo lộ trình

**Công việc:**
- Overview:
  - % hoàn thành tổng thể
  - Số kỹ năng đã học
  - Số khóa học hoàn thành
  - Thời gian đã đầu tư

- Danh sách kỹ năng:
  - Tên kỹ năng
  - Progress bar
  - Trạng thái: Chưa bắt đầu/Đang học/Hoàn thành
  - Nút "Cập nhật tiến độ"

- Achievements:
  - Badges đã đạt được
  - Milestones

- Calendar view:
  - Lịch học
  - Deadline
  - Reminder

**Input:** User progress updates

**Output:**
- Hiển thị tiến độ
- Cập nhật trạng thái
- Nhắc nhở

**Priority:** P2

---

## 15. GAMIFICATION MODULE

### 15.1. Màn hình Điểm & Huy hiệu
**Mô tả:** Hệ thống tích điểm và thành tích

**Đối tượng:** Tất cả user

**Công việc:**
- Header:
  - Tổng điểm hiện tại
  - Level (VD: Level 5 - Explorer)
  - Progress bar đến level tiếp theo

- **Section 1: Nhiệm vụ hàng ngày**
  - Danh sách nhiệm vụ:
    - "Đăng nhập hàng ngày" (+10 điểm) ✓
    - "Làm 1 bài test" (+50 điểm)
    - "Khám phá 3 nghề mới" (+30 điểm)
    - "Chia sẻ kết quả" (+20 điểm)
  - Checkbox hoàn thành
  - Nút "Nhận thưởng"

- **Section 2: Nhiệm vụ tuần**
  - Tương tự nhiệm vụ ngày
  - Điểm thưởng cao hơn

- **Section 3: Huy hiệu**
  - Grid badges:
    - Badge đã đạt (màu)
    - Badge chưa đạt (xám)
    - Tên badge
    - Điều kiện đạt
  - VD badges:
    - "Người mới" (Hoàn thành profile)
    - "Khám phá" (Làm 3 bài test)
    - "Chuyên gia" (Làm tất cả test)
    - "Chia sẻ" (Share 5 lần)
    - "Premium" (Nâng cấp Premium)

- **Section 4: Bảng xếp hạng**
  - Tab: Tuần/Tháng/Tất cả
  - Top 10 users:
    - Rank
    - Avatar
    - Tên
    - Điểm
  - Vị trí của bạn (highlight)

- **Section 5: Đổi thưởng**
  - Danh sách quà:
    - Voucher giảm giá Premium
    - Free mentor session
    - Unlock tính năng đặc biệt
  - Số điểm cần
  - Nút "Đổi ngay"

**Input:** User ID, activities

**Output:**
- Hiển thị điểm & badges
- Đổi thưởng
- Leaderboard

**Priority:** P2

---

# 🚀 GIAI ĐOẠN 3 - HỆ SINH THÁI (THÁNG 7+)

## 16. COMMUNITY MODULE

### 16.1. Màn hình Cộng đồng (Feed)
**Mô tả:** Diễn đàn chia sẻ và thảo luận

**Đối tượng:** Tất cả user

**Công việc:**
- Tabs:
  - "Dành cho bạn" (personalized)
  - "Mới nhất"
  - "Phổ biến"
  - "Theo dõi"

- Feed posts:
  - Card post:
    - Avatar user
    - Tên user
    - Thời gian
    - Nội dung (text + hình ảnh)
    - Tags (ngành nghề)
    - Số like, comment, share
    - Nút like, comment, share, bookmark

- Floating button "Tạo bài viết"

- Filter theo topic:
  - Định hướng nghề
  - Kinh nghiệm học tập
  - Tư vấn
  - Chia sẻ kết quả test
  - Hỏi đáp

**Input:** User ID

**Output:**
- Feed cá nhân hóa
- Navigate đến Post Detail
- Tạo post mới

**Priority:** P2

---

### 16.2. Màn hình Tạo Bài viết
**Mô tả:** Đăng bài lên cộng đồng

**Đối tượng:** User đã đăng nhập

**Công việc:**
- Form:
  - Textarea nội dung
  - Upload hình ảnh (tối đa 5)
  - Chọn topic (dropdown)
  - Tags (multi-select)
  - Chọn quyền riêng tư:
    - Công khai
    - Chỉ Premium
    - Chỉ bạn bè

- Preview bài viết
- Nút "Đăng"

**Input:** Post content

**Output:**
- Tạo post mới
- Hiển thị trong Feed

**Priority:** P2

---

### 16.3. Màn hình Chi tiết Bài viết
**Mô tả:** Xem và tương tác với bài viết

**Đối tượng:** User xem post

**Công việc:**
- Header: Thông tin người đăng
- Nội dung bài viết đầy đủ
- Hình ảnh (swipeable)
- Tags

- **Section Comments:**
  - Danh sách comment:
    - Avatar
    - Tên user
    - Nội dung
    - Thời gian
    - Nút like, reply
  - Nested replies
  - Sort: Mới nhất/Phổ biến

- Input comment:
  - Textarea
  - Nút gửi

- Actions:
  - Like/Unlike
  - Share
  - Bookmark
  - Report (nếu vi phạm)

**Input:** Post ID

**Output:**
- Hiển thị post & comments
- Tương tác (like, comment)

**Priority:** P2

---

## 17. B2B - SCHOOL MODULE (Web-based)

### 17.1. Dashboard Trường học
**Mô tả:** Tổng quan cho giáo viên/quản lý trường

**Đối tượng:** Tài khoản trường học

**Công việc:**
- Thống kê:
  - Tổng số học sinh
  - Số học sinh đã làm test
  - Tỷ lệ hoàn thành
  - Xu hướng nghề phổ biến

- Biểu đồ:
  - Phân bố tính cách học sinh
  - Top nghề được quan tâm
  - Tiến độ làm test theo lớp

- Quick actions:
  - Thêm học sinh
  - Gán bài test
  - Tạo báo cáo
  - Tổ chức workshop

**Input:** School account

**Output:**
- Dashboard với metrics
- Navigate đến các chức năng

**Priority:** P2

---

### 17.2. Quản lý Học sinh
**Mô tả:** Thêm và quản lý học sinh

**Đối tượng:** Giáo viên, quản lý trường

**Công việc:**
- Danh sách học sinh:
  - Bảng:
    - Tên
    - Lớp
    - Email
    - Trạng thái test
    - Kết quả
    - Actions

- Thêm học sinh:
  - Thủ công (form)
  - Import Excel (template)
  - Gửi link đăng ký

- Gán bài test:
  - Chọn học sinh (multi-select)
  - Chọn bài test
  - Deadline
  - Gửi thông báo

- Export danh sách

**Input:** Student data

**Output:**
- Quản lý học sinh
- Gán test
- Theo dõi tiến độ

**Priority:** P2

---

### 17.3. Báo cáo Tổng hợp Lớp
**Mô tả:** Phân tích kết quả cả lớp

**Đối tượng:** Giáo viên

**Công việc:**
- Chọn lớp và bài test

- **Báo cáo bao gồm:**
  - Tỷ lệ hoàn thành
  - Phân bố tính cách (pie chart)
  - Top 10 nghề phổ biến
  - Phân tích kỹ năng chung
  - Điểm mạnh/yếu của lớp
  - Gợi ý định hướng cho từng nhóm

- So sánh giữa các lớp

- Export PDF/Excel

- Chia sẻ với phụ huynh (option)

**Input:** Class ID, Test ID

**Output:**
- Báo cáo tổng hợp
- File PDF/Excel

**Priority:** P2

---

## 18. ADDITIONAL SCREENS

### 18.1. Màn hình Sự kiện & Workshop
**Mô tả:** Danh sách sự kiện hướng nghiệp

**Đối tượng:** Tất cả user

**Công việc:**
- Tabs:
  - "Sắp diễn ra"
  - "Đang diễn ra"
  - "Đã kết thúc"

- Card sự kiện:
  - Hình ảnh banner
  - Tên sự kiện
  - Ngày giờ
  - Địa điểm (Online/Offline)
  - Diễn giả
  - Số chỗ còn lại
  - Giá (Free/Paid)
  - Nút "Đăng ký"

- Filter: Theo chủ đề, theo thời gian

**Input:** User ID

**Output:**
- Danh sách sự kiện
- Đăng ký tham gia

**Priority:** P3

---

### 18.2. Màn hình Giới thiệu Bạn bè (Referral)
**Mô tả:** Chương trình giới thiệu

**Đối tượng:** Tất cả user

**Công việc:**
- Header: "Mời bạn bè, nhận quà"

- Mã giới thiệu của bạn:
  - Mã code
  - Link giới thiệu
  - QR code
  - Nút copy, share

- Phần thưởng:
  - Bạn nhận: 50 điểm + 10% giảm giá Premium
  - Bạn bè nhận: 20% giảm giá lần đầu

- Thống kê:
  - Số bạn đã mời
  - Số bạn đã đăng ký
  - Tổng điểm nhận được

- Danh sách bạn bè đã mời:
  - Tên
  - Trạng thái (Đã đăng ký/Chưa)
  - Ngày

**Input:** User ID

**Output:**
- Mã giới thiệu
- Theo dõi referrals
- Nhận thưởng

**Priority:** P3

---

### 18.3. Màn hình Tìm kiếm Toàn cục
**Mô tả:** Tìm kiếm tất cả nội dung

**Đối tượng:** Tất cả user

**Công việc:**
- Search bar lớn
- Recent searches
- Trending searches

- Kết quả theo category:
  - Nghề nghiệp
  - Bài test
  - Mentor
  - Bài viết cộng đồng
  - Sự kiện
  - Khóa học

- Filter và sort

**Input:** Search query

**Output:**
- Kết quả tìm kiếm
- Navigate đến item

**Priority:** P2

---

# 📊 TỔNG KẾT

## Thống kê Màn hình theo Giai đoạn

### Giai đoạn 1 (MVP): **~40 màn hình**
- Authentication: 7 màn hình
- Home & Navigation: 2 màn hình
- Career Test: 4 màn hình
- Results & Reports: 3 màn hình
- Career Database: 3 màn hình
- User Profile: 4 màn hình
- Payment: 5 màn hình
- Notification: 1 màn hình
- Support: 2 màn hình
- Admin: 6 màn hình

### Giai đoạn 2 (Mở rộng): **+20 màn hình**
- Job Simulator: 4 màn hình
- Mentor Connect: 6 màn hình
- AI Career Coach: 2 màn hình
- Learning Path: 2 màn hình
- Gamification: 1 màn hình

### Giai đoạn 3 (Hệ sinh thái): **+10 màn hình**
- Community: 3 màn hình
- B2B School: 3 màn hình
- Additional: 3 màn hình

**Tổng cộng: ~70 màn hình**

---

## Ưu tiên Phát triển

### Phase 1.1 (Tháng 1) - Core MVP
- P0: Authentication (Login, Signup, OTP)
- P0: Home & Navigation
- P0: Career Test (3 tests)
- P0: Basic Results
- P0: Career Database (basic)
- P0: User Profile (basic)

### Phase 1.2 (Tháng 2) - Premium & Payment
- P0: Premium Report
- P0: Payment Integration
- P1: Admin Dashboard
- P1: Test Management

### Phase 1.3 (Tháng 3) - Polish & Optimize
- P1: Notifications
- P2: Gamification (basic)
- P2: Help & Support
- P2: Settings

### Phase 2 (Tháng 4-6) - Advanced Features
- P1: Job Simulator
- P1: Mentor Connect
- P2: AI Career Coach
- P2: Learning Path

### Phase 3 (Tháng 7+) - Ecosystem
- P2: Community
- P2: B2B School
- P3: Events & Referral

---

**Ghi chú:**
- Tài liệu này là bản chi tiết các màn hình, cần được review và điều chỉnh theo feedback thực tế
- Mỗi màn hình cần có wireframe/mockup riêng
- Cần xác định API endpoints cho từng màn hình
- Cần xác định database schema tương ứng
---

### 1.7. Màn hình Quên mật khẩu
**Mô tả:** Khôi phục mật khẩu qua email/phone

**Đối tượng:** Người dùng quên mật khẩu

**Công việc:**
- Input email hoặc số điện thoại
- Gửi link/OTP reset password
- Xác thực OTP
- Form nhập mật khẩu mới
- Xác nhận mật khẩu mới

**Input:** Email/Phone, OTP, Mật khẩu mới

**Output:** 
- Mật khẩu được đặt lại thành công
- Chuyển đến màn hình Đăng nhập

**Priority:** P1

---

## 2. HOME & NAVIGATION

### 2.1. Màn hình Home (Trang chủ)
**Mô tả:** Màn hình chính sau khi đăng nhập

**Đối tượng:** Người dùng đã đăng nhập

**Công việc:**
- Header: Avatar, tên user, notification icon
- Banner chào mừng/khuyến mãi
- Section "Bài test của bạn":
  - Danh sách 3 bài test chính
  - Hiển thị trạng thái: Chưa làm/Đang làm/Hoàn thành
  - Progress bar nếu đang làm dở
- Section "Nghề nghiệp phù hợp" (nếu đã có kết quả)
- Section "Khám phá nghề nghiệp"
- Bottom Navigation: Home, Test, Nghề nghiệp, Hồ sơ

**Input:** User ID, trạng thái test

**Output:** 
- Hiển thị dashboard cá nhân hóa
- Navigate đến các màn hình con

**Priority:** P0


