JSP CURRENCY CONVERTER
=======================

Cấu trúc:
- pom.xml
- src/main/webapp/index.jsp
- src/main/webapp/converter.jsp
- src/main/webapp/WEB-INF/web.xml

Yêu cầu:
- JDK 17+
- Maven
- Apache Tomcat 10.1+

Chạy:
1. Mở terminal tại thư mục dự án.
2. Chạy: mvn clean package
3. File WAR được tạo tại:
   target/jsp-currency-converter.war
4. Deploy WAR vào Tomcat 10.1+.
5. Truy cập:
   http://localhost:8080/jsp-currency-converter/

Chức năng:
Nhập tỉ giá và số USD, sau đó converter.jsp dùng JSP Scriptlet
để tính VND = USD * Rate và hiển thị kết quả bằng Expression.
