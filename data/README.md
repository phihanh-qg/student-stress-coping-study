# TÀI LIỆU HƯỚNG DẪN DỮ LIỆU NGHIÊN CỨU (DATA CODEBOOK)

## 1. Tổng quan bộ dữ liệu
Bộ dữ liệu phản ánh kết quả khảo sát định lượng thu thập từ 770 học sinh trung học phổ thông tại huyện Ea H’leo, tỉnh Đắk Lắk trong khuôn khổ Dự án nghiên cứu khoa học kỹ thuật dành cho học sinh trung học năm học 2023 - 2024.

Mẫu khảo sát được thu thập từ ba trường THPT:
1. Trường THPT Ea H’leo: n = 346 học sinh (44.94%).
2. Trường THPT Phan Chu Trinh: n = 222 học sinh (28.83%).
3. Trường THPT Võ Văn Kiệt: n = 202 học sinh (26.23%).
Tổng quy mô mẫu: N = 770 học sinh.

## 2. Cấu trúc các tệp dữ liệu

### 2.1. survey_distribution.csv
Bảng phân bố tần suất đối mặt với căng thẳng và cảm xúc tiêu cực theo từng trường THPT.
Các trường dữ liệu:
- school_name: Tên đơn vị trường THPT.
- sample_size: Tổng số học sinh tham gia khảo sát tại trường.
- frequent_count: Số lượng học sinh thường xuyên đối mặt với căng thẳng.
- frequent_percentage: Tỷ lệ phần trăm học sinh thường xuyên đối mặt với căng thẳng (%).
- occasional_count: Số lượng học sinh thỉnh thoảng đối mặt với căng thẳng.
- occasional_percentage: Tỷ lệ phần trăm học sinh thỉnh thoảng đối mặt với căng thẳng (%).
- rare_or_never_count: Số lượng học sinh hiếm khi hoặc chưa bao giờ đối mặt với căng thẳng.
- rare_or_never_percentage: Tỷ lệ phần trăm học sinh hiếm khi hoặc chưa bao giờ đối mặt với căng thẳng (%).

### 2.2. stress_factors.csv
Bảng phân loại cơ cấu các nguồn tác nhân gây áp lực tâm lý cho học sinh.
Các trường dữ liệu:
- stressor_id: Mã định danh nhóm tác nhân.
- stressor_category_vi: Tên nhóm tác nhân (tiếng Việt).
- stressor_category_en: Tên nhóm tác nhân (tiếng Anh).
- stressor_description_vi: Mô tả chi tiết các yếu tố thành phần.
- count_n: Số lượng học sinh lựa chọn (n).
- percentage: Tỷ lệ cơ cấu phần trăm (%).

### 2.3. coping_strategies.csv
Bảng thống kê các phương thức và hành vi ứng phó khi học sinh đối mặt với trạng thái căng thẳng.
Các trường dữ liệu:
- strategy_id: Mã định danh phương thức ứng phó.
- strategy_name_vi: Tên phương thức ứng phó (tiếng Việt).
- strategy_name_en: Tên phương thức ứng phó (tiếng Anh).
- behavior_classification: Phân loại tính chất hành vi tâm lý.
- count_n: Số lượng học sinh lựa chọn (n).
- percentage: Tỷ lệ phần trăm (%).

### 2.4. peer_support.csv
Bảng thống kê phản ứng và thái độ của học sinh khi chứng kiến bạn bè cùng lớp rơi vào hoàn cảnh căng thẳng hoặc có cảm xúc tiêu cực.
Các trường dữ liệu:
- response_id: Mã định danh loại phản ứng.
- reaction_type_vi: Mô tả hành động ứng xử đối với bạn bè (tiếng Việt).
- reaction_type_en: Mô tả hành động ứng xử đối với bạn bè (tiếng Anh).
- count_n: Số lượng học sinh lựa chọn (n).
- percentage: Tỷ lệ phần trăm (%).

## 3. Quy chuẩn đạo đức nghiên cứu và bảo mật thông tin
Quá trình thu thập dữ liệu tuân thủ nghiêm ngặt các nguyên tắc đạo đức trong nghiên cứu khoa học hành vi đối với đối tượng vị thành niên:
1. Thu thập dữ liệu trên tinh thần tự nguyện hoàn toàn của học sinh.
2. Ẩn danh tuyệt đối thông tin danh tính cá nhân (không lưu trữ họ tên, địa chỉ email, số điện thoại hay số thứ tự lớp học).
3. Dữ liệu chỉ phục vụ mục đích phân tích thống kê học thuật và xây dựng giải pháp hỗ trợ tâm lý học đường.
