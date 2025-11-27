# sentiment-analysis-svm-distilbert

Dự án này xây dựng hệ thống phân tích cảm xúc (sentiment analysis) trên tập dữ liệu IMDb Movie Reviews, sử dụng hai hướng tiếp cận khác nhau:

1. Mô hình truyền thống dựa trên đặc trưng

TF-IDF vectorization

Support Vector Machine (SVM)

Đánh giá mô hình bằng Stratified K-Fold để đảm bảo tỉ lệ nhãn cân bằng và kết quả ổn định hơn

2. Mô hình học sâu hiện đại

Fine-tuning mô hình DistilBERT (phiên bản nhỏ gọn và nhanh hơn của BERT)

Mục tiêu của dự án là so sánh hiệu năng, độ chính xác và tốc độ của hai phương pháp, từ đó rút ra ưu – nhược điểm của từng mô hình.

📂 Dataset IMDb

IMDb Movie Reviews Dataset (50.000 review, 2 nhãn: positive/negative)
🔗 Tải dataset tại đây: https://ai.stanford.edu/~amaas/data/sentiment/

Hoặc bản HuggingFace:
🔗 https://huggingface.co/datasets/imdb