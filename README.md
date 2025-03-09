# Titanic-Data-Exploration-and-ML

## Mô Tả
Repository này chứa bài phân tích và xử lý dữ liệu Titanic, bao gồm việc xử lý dữ liệu thiếu và áp dụng các mô hình học máy như KNN và Logistic Regression, Linear Regression. Mục tiêu của bài tập là so sánh các phương pháp xử lý dữ liệu thiếu khác nhau và đánh giá hiệu quả của chúng thông qua các chỉ số như Accuracy, F1-Score và RMSE.

## Các Bước Thực Hiện
1. **Phân Tích Dữ Liệu Thiếu**
   - Tìm và phân tích các giá trị thiếu trong dataset.
   - Tính toán tỷ lệ phần trăm dữ liệu thiếu ở mỗi cột.

2. **Trực Quan Hóa Dữ Liệu Thiếu**
   - Vẽ heatmap để hiển thị vị trí của dữ liệu thiếu trong dataset.

3. **Xử Lý Dữ Liệu Thiếu**
   - **Phương pháp 1**: Loại bỏ các dòng có dữ liệu thiếu.
   - **Phương pháp 2**: Thay thế các giá trị thiếu bằng giá trị trung bình hoặc trung vị.
   - **Phương pháp 3**: Sử dụng các kỹ thuật nâng cao như KNN Imputation.

4. **Xây Dựng Mô Hình Học Máy**
   - Sử dụng KNN và Logistic Regression, Linear Regression để xây dựng mô hình dự đoán.
   - Đánh giá mô hình với các chỉ số Accuracy, F1-Score và RMSE.

5. **Đánh Giá và Kết Luận**
   - So sánh hiệu quả của các phương pháp xử lý dữ liệu thiếu.
   - Đưa ra kết luận về phương pháp nào cho kết quả tốt nhất và liệu việc loại bỏ dữ liệu có gây mất mát thông tin quan trọng hay không.

## Các Thư Viện Cần Cài Đặt
Để chạy mã nguồn trong repository này, bạn cần cài đặt các thư viện sau:
- pandas
- seaborn
- matplotlib
- scikit-learn
