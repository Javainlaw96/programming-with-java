# Bài 1 
**Xét từng câu lệnh khai báo biến như sau**:
-  `bool kiemTra;` : Lệnh này **bị lỗi biên dịch** bởi trong Java 'bool' không phải một keyword đại diện cho một kiểu dữ liệu để khai báo biến.
- `short a; short b; short c;`: Lệnh này **bị lỗi biên dịch** vì sai cú pháp khi khai báo nhiều biến cùng một lúc. (Sửa lại thành: `short a, b, c`)
- `double 1000;` : Lệnh này **bị lỗi biên dịch** vì sau keyword kiểu dữ liệu không được bắt đầu bằng chữ số.
- `char 1kitu;` : Lệnh này **bị lỗi biên dịch** vì sau keyword kiểu dữ liệu không được bắt đầu bằng chữ số.
- `int soThu1, soThu2, soThu3;`: Không bị lỗi biên dịch.
- `float a, b , c,` : Lệnh này **bị lỗi biên dịch** do kết thúc câu lệnh bằng ',' (Sửa lại thành: `float a, b , c;`).
- `long ten_bien_raaaaaaaaaaaaaaaaaaaaat_dai;`: Lệnh này không bị lỗi biên dịch, tuy nhiên cần lưu ý không nên đặt tên biến quá dài.
- `char ki-tu;`: Lệnh này **bị lỗi biên dịch** vì chứa ký tự đặc biệt '-' không được phép sử dụng khi khai báo biến.
- `int public;`: Lệnh này **bị lỗi biên dịch** do tên biến trùng với từ khóa ('public').
- `short a; byte a;` :  Lệnh này **bị lỗi biên dịch** vì mỗi câu lệnh chỉ được dùng một từ khóa để  khai báo biến. Ở lệnh này, chỉ có một kiểu dữ liệu được khai báo là `short`, tuy nhiên việc khai báo biến cho kiểu dữ liệu `short` trong câu lệnh này cũng đã sai cú pháp về khai báo nhiều biến cùng lúc va tên biến có dấu cách).
# Bài 2 
Kiểu dữ liệu `char` chiếm 2 byte trong bộ nhớ và là kiểu dữ liệu chỉ lưu được một ký tự duy nhất. Tuy nhiên, việc dùng kiểu dữ liệu `char` sẽ lưu được bao nhiêu ký tự khác nhau sẽ phụ thuộc vào bộ nhớ của máy tính. Mình có thể đặt nhiều lệnh khai báo biến mà, mỗi lệnh lưu được 1 ký tự. 
