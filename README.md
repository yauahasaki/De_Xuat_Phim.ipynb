# Movie Recommendation System

## 1. Giới thiệu
Đề tài xây dựng hệ thống gợi ý phim sử dụng hai thuật toán Machine Learning: **Singular Value Decomposition (SVD)** và **K-Means Clustering**.

Mục tiêu là phân tích dữ liệu đánh giá phim và đề xuất những bộ phim phù hợp với sở thích người dùng.

## 2. Công nghệ sử dụng
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Surprise (nếu sử dụng thư viện này để triển khai SVD)

## 3. Dữ liệu
Sử dụng bộ dữ liệu MovieLens, bao gồm:
- `ratings.csv`: thông tin đánh giá phim của người dùng.
- `movies.csv`: thông tin và thể loại phim.

## 4. Phương pháp
### SVD
Phân rã ma trận người dùng – phim để dự đoán mức độ yêu thích của người dùng đối với những bộ phim chưa đánh giá.

### K-Means
Phân cụm người dùng dựa trên đặc điểm đánh giá phim, từ đó hỗ trợ tìm kiếm và đề xuất phim phù hợp với nhóm người dùng tương đồng.

## 5. Cài đặt
Cài đặt các thư viện cần thiết:

```bash
pip install -r requirements.txt
```

## 6. Cách chạy
Chạy chương trình chính:

```bash
python src/main.py
```

Lưu ý: Điều chỉnh lệnh chạy theo đúng tên file và cấu trúc mã nguồn thực tế của dự án.

## 7. Kết quả
Hệ thống thực hiện dự đoán mức độ yêu thích phim bằng SVD và phân nhóm người dùng bằng K-Means. Kết quả đánh giá và hình minh họa được lưu trong thư mục `results/`.

## 8. Nhóm thực hiện
- Tên đề tài: Movie Recommendation System
- Học phần: CMP169 – Trí tuệ nhân tạo
- Trường: HUTECH
-Thành viên: Võ Hoàng Đăng Khoa, Châu Trung Hậu, Nhị Anh Hào
