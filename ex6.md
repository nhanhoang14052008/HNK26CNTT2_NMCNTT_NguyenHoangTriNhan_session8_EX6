# Phần 1. Phân tích tình huống của Nam

## 1. Những sai lầm trong tư duy

Sai lầm 1: Dùng Word (.docx) để lưu trữ tài liệu dự án trên GitHub.

-   `.docx` là định dạng Rich Text, chứa nội dung cùng thông tin định dạng và cấu trúc dữ liệu bên trong.
    
-   GitHub khó hiển thị trực tiếp nội dung Word như một tệp Markdown; thành viên thường phải tải xuống để đọc.
    
-   Markdown (`.md`) là văn bản thuần có cú pháp định dạng, nên GitHub có thể hiển thị trực tiếp dưới dạng tài liệu dễ đọc.
    

Sai lầm 2: Cho rằng Git có thể so sánh mọi định dạng tệp giống nhau.

-   Git xử lý tệp Word thường như dữ liệu nhị phân (binary), khiến việc xem khác biệt giữa các phiên bản khó khăn.
    
-   Markdown là văn bản thuần (plain text), nên Git Diff có thể chỉ ra chính xác dòng hoặc ký tự đã thay đổi, giúp nhóm xử lý xung đột thuận tiện hơn.## 2. Tại sao Markdown nhẹ và an toàn hơn?

Tiêu  chí

Word  (.docx)

Markdown  (.md)

Bản  chất

Gói  dữ  liệu  định  dạng,  thường  là  ZIP  chứa  XML  và  tài  nguyên

Văn  bản  thuần

Dung  lượng

Thường  lớn  hơn  do  định  dạng  và  tài  nguyên  nhúng

Thường  nhẹ  hơn

Git  Diff

Khó  so  sánh  trực  tiếp  nếu  không  có  công  cụ  hỗ  trợ

Dễ  xem  từng  dòng  thay  đổi

Hiển  thị  GitHub

Thường  cần  tải  xuống  hoặc  dùng  công  cụ  phù  hợp

Hiển  thị  trực  tiếp

Khả  năng  phục  hồi

Có  thể  bị  lỗi  cấu  trúc  khi  dữ  liệu  quan  trọng  bị  hỏng

Có  thể  đọc  và  cứu  phần  văn  bản  còn  nguyên  dễ  dàng  hơn

Bẫy dữ liệu — mất 1 byte: Không thể kết luận rằng mất một byte sẽ luôn làm hỏng hoàn toàn tệp Word. Tuy nhiên, nếu byte bị mất nằm trong phần cấu trúc quan trọng của gói `.docx`, tệp có thể không mở được. Markdown không có cấu trúc gói phức tạp như vậy; nếu mất một byte, thường chỉ một ký tự hoặc một phần văn bản bị ảnh hưởng, còn phần nội dung khác vẫn có thể đọc được.

Lưu ý, Markdown cũng không miễn nhiễm với mất dữ liệu. Ưu thế của nó là cấu trúc đơn giản, dễ kiểm tra, dễ phục hồi và phù hợp với hệ thống quản lý phiên bản Git.



# Phần 2. Hoàn thiện Sử dụng StackEdit để chuyển đổi đoạn giới thiệu từ Word sang Markdown (.md).




# GreenTech
#V 1. Giời thiệu
GreenTech là dự án hướng tới việc
ung dụng công nghệ dể báo vệ môi
trường, giúp cuộc sống xanh và bền vững.
#u 2. Mục tiêu
- Tạo ra giải pháp công nghệ xanh
- Năng cao ý thức cộng đồng
- Phát triển bền vừng
