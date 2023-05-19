# JavaScript

## JavaScript Roadmap

### 1. Giới thiệu về JavaScript
-  JavaScript là gì?
  JavaScript là một ngôn ngữ lập trình phía máy khách (client-side) mạnh mẽ và phổ biến được sử dụng để tạo ra các ứng dụng web tương tác. Dưới đây là những điểm cần lưu ý về giới thiệu JavaScript:
- #### Tại sao học JavaScript?
  JavaScript là một trong những ngôn ngữ lập trình quan trọng nhất cho phát triển web. Nó cho phép bạn tạo ra các ứng dụng web động, tương tác và phức tạp. Học JavaScript giúp bạn có khả năng điều khiển và thay đổi các phần tử HTML, xử lý sự kiện, gửi và nhận dữ liệu từ máy chủ, và nhiều hơn nữa.
- #### Lịch sử và phiên bản của JavaScript:
  JavaScript được tạo ra vào năm 1995 bởi Brendan Eich tại Netscape. Ban đầu, nó được phát triển như một ngôn ngữ kịch bản đơn giản cho trang web, nhưng sau đó đã phát triển thành một ngôn ngữ lập trình phía máy khách mạnh mẽ và linh hoạt. JavaScript có nhiều phiên bản và tiêu chuẩn, với phiên bản mới nhất là ECMAScript 2022 (ES2022).
- #### Cách sử dụng JavaScript trong trình duyệt và ngoài trình duyệt:
  Trình duyệt web là một môi trường chính để chạy JavaScript. Bạn có thể nhúng mã JavaScript vào trang HTML bằng cách sử dụng các thẻ `<script>`.
  Ngoài ra, JavaScript cũng có thể được sử dụng trên máy chủ thông qua các môi trường như Node.js để phát triển các ứng dụng web phía máy chủ.
- #### Cú pháp JavaScript cơ bản
  Cú pháp JavaScript bao gồm việc khai báo biến, sử dụng toán tử và kiểu dữ liệu, định nghĩa và gọi hàm, làm việc với chuỗi, số, mảng và đối tượng, và sử dụng các lệnh rẽ nhánh và vòng lặp. Bạn cũng có thể sử dụng các thư viện và khung công việc (framework) JavaScript để tăng cường khả năng phát triển.
### 2. Biến và khai báo biến
- #### Khái niệm về biến:
  Trong JavaScript, biến là một vùng bộ nhớ được dùng để lưu trữ giá trị. Mỗi biến có một tên duy nhất để xác định và truy cập vào nó.
- #### Cách khai báo biến trong JavaScript:
  Để khai báo biến trong JavaScript, chúng ta sử dụng từ khóa `var`, `let`, hoặc `const`, sau đó là tên biến và có thể gán giá trị cho biến đó.
    * `var`: Sử dụng var cho các biến có phạm vi chức năng (function scope) hoặc biến toàn cục (global scope).
    * `let`: Sử dụng let cho các biến có phạm vi khối (block scope) và cần thay đổi giá trị.
    * `const`: Sử dụng const cho các hằng số (constant) không thay đổi giá trị.
  
  Ví dụ:
  ```javascript
    // Sử dụng var
    var name = "John";
    console.log(name); // => John
  
    // Sử dụng let
    let age = 30; 
    console.log(age); // => 30
  
    // Sử dụng const
    const PI = 3.14;
    console.log(PI); // => 3.14
  ```
- #### Quy tắc đặt tên biến:

  - Tên biến có thể chứa các ký tự chữ cái (a-z, A-Z), chữ số (0-9), dấu gạch dưới (_) và dấu đôi chấm (:) (trong một số trường hợp).
  - Tên biến không được bắt đầu bằng số.
  - Tên biến phân biệt chữ hoa và chữ thường (case-sensitive).
  - Tên biến không được trùng với các từ khóa có sẵn trong ngôn ngữ.
  
  - #### Cách sử dụng biến trong các phép toán và câu lệnh
    - Sử dụng biến trong các phép toán
      ```javascript
      let a = 5;
      let b = 3;
      
      let sum = a + b;
      console.log(sum); // Output: 8
    
      let product = a * b;
      console.log(product); // Output: 15
      ```
    - Sử dụng biến trong câu lệnh điều kiện
      ```javascript
      let temperature = 25;
      
      if (temperature > 30) {
      console.log("Nhiệt độ cao");
      } else if (temperature <= 30 && temperature >= 20) {
      console.log("Nhiệt độ trong khoảng bình thường");
      } else {
      console.log("Nhiệt độ thấp");
      } // Output: Nhiệt độ thấp
      ```
    -  Sử dụng biến trong vòng lặp
       ```javascript
       for (let i = 1; i <= 5; i++) {
       console.log("Giá trị của i là: " + i);
       }
       for (let number of numbers) {
       console.log(number);
       } // Output: 1, 2, 3, 4, 5
       ```
    
    

  
