+ DS105.M11
+ Dataset: World bank data country (tự thu thập)
+ Nguồn thu thập: https://databank.worldbank.org/home
+ Bố cục : 
1) Thu thập thêm dữ liệu (Mở rộng thêm các cột thuộc tính)
2) Tiền xử lý dữ liệu
3) EDA
4) ANOVA (???)
5) Lựa chọn và phát triển mô hình để dự đoán gdp của một nước
6) Đánh giá mô hình
7) Tổng kết và hướng phát triển tương lai

---------------------------------------------------------------
* Chú ý:
+ tidy data ban đầu được ghép từ 2 raw data lấy world bank: 4905ac00-6459-4b1c-93e1-d6fd396dc9ac.csv ghép với a6eaaef3-b1f9-4e97-b5af-f6cd8e8f924e_Data
+ 2 metadata của 2 file có ở thư mục metadata, m đọc file csv sẽ thấy thuộc tính được mô tả trong file đó. Tuy nhiên, t ko lấy tất cả feature từ raw data nên chịu khó dùng excel để tìm tên feature được mô tả dòng nào cho nhanh nhé mày.
+ 2 file code chú ý. File preprocessing không code vào trong nhé m, cái này để tạo ra tidy data thôi nhé. M làm EDA vào file GDP-predict. Chú ý tao chưa xử lý missing value m nhé, nếu m làm đc thì làm cho t luôn nhé, hướng xử lý là gom các nước trong 1 khu vực (Cùng giá trị trong cột Region) rồi tính mean từng khu vực, cứ quốc gia nào thiếu thì mình lấy mean của khu vực của quốc gia đó điền vào m nhé. M có thể làm theo cách khác hợp lý hơn cũng được.