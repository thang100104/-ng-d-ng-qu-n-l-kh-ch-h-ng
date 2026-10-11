# Ứng dụng quản lý khách hàng

Repo bài tập Java Web.

## Bài tập đã thêm

### Ứng dụng Calculator

Mã nguồn nằm trong thư mục `calculator-app/`.

Chức năng:
- Nhập 2 toán hạng.
- Chọn phép toán cộng, trừ, nhân, chia.
- Xử lý bằng Servlet + lớp Calculator.
- Hiển thị kết quả bằng JSP.
- Bắt lỗi chia cho 0.

### Chạy bài Calculator

```bash
cd calculator-app
mvn clean package
```

Sau khi build thành công, deploy file:

`calculator-app/target/servlet-calculator.war`

lên Tomcat 10.1+.
