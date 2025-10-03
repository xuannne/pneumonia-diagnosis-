📌 Giới thiệu

Đề tài tập trung vào việc xây dựng mô hình học sâu nhằm hỗ trợ chẩn đoán bệnh viêm phổi dựa trên ảnh X-quang ngực. Bằng cách áp dụng mạng CNN (Convolutional Neural Network), hệ thống có khả năng tự động phát hiện dấu hiệu bất thường trong phổi và đưa ra dự đoán chính xác.

Ngoài ra, nhóm cũng so sánh hiệu quả giữa CNN và các mô hình truyền thống như SVM và KNN, đồng thời áp dụng Grad-CAM để trực quan hóa vùng ảnh mà mô hình tập trung, giúp tăng độ tin cậy và khả năng giải thích của hệ thống.

🎯 Mục tiêu

Xây dựng mô hình CNN để chẩn đoán viêm phổi từ ảnh X-quang.

So sánh hiệu quả giữa CNN, SVM và KNN.

Đánh giá mô hình qua các chỉ số: Accuracy, Sensitivity, Specificity.

Ứng dụng Grad-CAM để giải thích kết quả dự đoán.

Đề xuất hướng ứng dụng thực tiễn trong y tế.

🗂️ Dữ liệu

Bộ dữ liệu: Chest X-Ray Images (Pneumonia) (Kaggle).

Gồm 2 lớp:

Normal: Phổi bình thường.

Pneumonia: Bệnh nhân viêm phổi.

Link dataset: Kaggle - Chest X-Ray Pneumonia

⚙️ Phương pháp

Tiền xử lý dữ liệu:

Resize ảnh về kích thước cố định (224×224).

Chuẩn hóa giá trị pixel [0,1].

Augmentation: xoay, lật, dịch chuyển.

Các mô hình áp dụng:

SVM và KNN: dùng đặc trưng trích xuất từ ảnh.

CNN: huấn luyện trực tiếp trên ảnh, tự động trích xuất đặc trưng.

Đánh giá mô hình:

Accuracy (Độ chính xác).

Sensitivity (Độ nhạy).

Specificity (Độ đặc hiệu).

Giải thích mô hình với Grad-CAM:

Sinh heatmap làm nổi bật vùng phổi bất thường.

Giúp bác sĩ kiểm chứng dự đoán.
