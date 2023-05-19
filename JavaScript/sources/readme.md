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
### 3. Comments và cách sử dụng
  - #### Comments trong JavaScript và mục đích của chúng:
    Comments (ghi chú) là các đoạn mã trong JavaScript không được thực thi và chỉ có tác dụng giúp lập trình viên giải thích và ghi chú thông tin quan trọng trong code. Chúng có thể được sử dụng để mô tả chức năng của mã, cung cấp hướng dẫn cho những người đọc code, hoặc để tạm thời tắt một đoạn mã.
    - #### Cách sử dụng single-line và multi-line comments:
      - Single-line comments (Comments trên một dòng): 
      
        Single-line comments được sử dụng để ghi chú trên một dòng. Để tạo một single-line comment, sử dụng dấu hai dấu gạch chéo ngược `//` trước đoạn mã cần ghi chú.
        
        Ví dụ:
        ```javascript
        // Đây là một single-line comment
        let name = "John";
        // Ghi chú về mục đích của biến 
        let age = 25; // Biến age lưu trữ tuổi của người dùng
        ```
      - Multi-line comments (Comments trên nhiều dòng):

        Multi-line comments được sử dụng để ghi chú trên nhiều dòng. Để tạo một multi-line comment, sử dụng dấu gạch chéo ngược kết hợp với dấu sao `/*` để bắt đầu comment và sử dụng dấu sao kết hợp với dấu gạch chéo ngược `*/` để kết thúc comment.
        
        Ví dụ:
        ```javascript
        /*
        Đây là một multi-line comment.
        Nó có thể trải dài trên nhiều dòng.
        */ 
        /* Ghi chú về chức năng của đoạn mã:
         - Bước 1: Thực hiện A
         - Bước 2: Thực hiện B
         - Bước 3: Thực hiện C
        */
        ```
### 4. Các toán tử cơ bản
  
  - #### Toán tử trong JavaScript
    Trong JavaScript, có nhiều loại toán tử được sử dụng để thực hiện các phép tính và so sánh giữa các giá trị. Dưới đây là một số toán tử cơ bản:
    
    - Toán tử số học:
      - Toán tử cộng (`+`): Dùng để cộng hai giá trị.
      - Toán tử trừ (`-`): Dùng để trừ hai giá trị.
      - Toán tử nhân (`*`): Dùng để nhân hai giá trị.
      - Toán tử chia (`/`): Dùng để chia hai giá trị.
      - Toán tử chia lấy phần dư (`%`): Dùng để lấy phần dư của phép chia hai giá trị.
    - Toán tử gán:
      - Toán tử gán (`=`): Dùng để gán giá trị từ phía bên phải vào biến bên trái.
      - Toán tử cộng và gán (`+=`): Dùng để cộng giá trị từ phía bên phải với giá trị hiện tại của biến và gán kết quả vào biến.
      - Toán tử trừ và gán (`-=`): Dùng để trừ giá trị từ phía bên phải từ giá trị hiện tại của biến và gán kết quả vào biến.
      - Toán tử nhân và gán (`*=`): Dùng để nhân giá trị từ phía bên phải với giá trị hiện tại của biến và gán kết quả vào biến.
      - Toán tử chia và gán (`/=`): Dùng để chia giá trị từ phía bên phải cho giá trị hiện tại của biến và gán kết quả vào biến.
    - Toán tử logic:
      - Toán tử bằng (`==` hoặc `===`): Dùng để kiểm tra hai giá trị có bằng nhau hay không.
      - Toán tử không bằng (`!=` hoặc `!==`): Dùng để kiểm tra hai giá trị có khác nhau hay không.
      - Toán tử lớn hơn (`>`): Dùng để kiểm tra giá trị bên trái có lớn hơn giá trị bên phải hay không.
      - Toán tử nhỏ hơn (`<`): Dùng để kiểm tra giá trị bên trái có nhỏ hơn giá trị bên phải hay không.
      - Toán tử lớn hơn hoặc bằng (`>=`): Dùng để kiểm tra giá trị bên trái có lớn hơn hoặc bằng giá trị bên phải hay không.
      - Toán tử nhỏ hơn hoặc bằng (`<=`): Dùng để kiểm tra giá trị bên trái có nhỏ hơn hoặc bằng giá trị bên phải hay không.
      - Toán tử logic và (`&&`): Dùng để kiểm tra cả hai biểu thức đúng.
      - Toán tử logic hoặc (`||`): Dùng để kiểm tra ít nhất một trong hai biểu thức đúng.
      - Toán tử logic phủ định (`!`): Dùng để đảo ngược giá trị của biểu thức.
      - Ví dụ toán tử:
        ```javascript
        var x = 5;
        var y = 10;
    
        // Toán tử số học
        var sum = x + y; // sum = 15
        var difference = x - y; // difference = -5
        var product = x * y; // product = 50
        var quotient = x / y; // quotient = 0.5
        var remainder = x % y; // remainder = 5
      
        // Toán tử gán
        x += 5; // x = 10 (tương đương x = x + 5)
        y -= 3; // y = 7 (tương đương y = y - 3)
        x *= 2; // x = 20 (tương đương x = x * 2)
        y /= 2; // y = 3.5 (tương đương y = y / 2)
      
        // Toán tử so sánh
        var isEqual = x == y; // isEqual = false
        var isNotEqual = x != y; // isNotEqual = true
        var isGreater = x > y; // isGreater = true
        var isLess = x < y; // isLess = false
        var isGreaterOrEqual = x >= y; // isGreaterOrEqual = true
        var isLessOrEqual = x <= y; // isLessOrEqual = false
      
        // Toán tử logic
        var logicalAnd = (x > 0) && (y < 10); // logicalAnd = true
        var logicalOr = (x > 0) || (y > 10); // logicalOr = true
        var logicalNot = !(x > 0); // logicalNot = false
        ```
#### Các kiểu dữ liệu cơ bản trong JavaScript
  Trong JavaScript, kiểu dữ liệu được chia thành hai nhóm chính: kiểu nguyên thủy (primitive) và kiểu đối tượng (object).

- #### Kiểu nguyên thủy (Primitive Types):

  - Kiểu số (Number): Dùng để lưu trữ các giá trị số. 

  - Kiểu chuỗi (String): Dùng để lưu trữ các đoạn văn bản. 

  - Kiểu boolean (Boolean): Dùng để lưu trữ giá trị true (đúng) hoặc false (sai). 

  - Kiểu null (Null): Chỉ có một giá trị duy nhất là null, thường được sử dụng khi biến không có giá trị. 

  - Kiểu undefined (Undefined): Đại diện cho các biến chưa được khởi tạo giá trị. 
  
  - Ví dụ:
    ```javascript
    let age = 25;                 // Kiểu số
    let name = "John";            // Kiểu chuỗi
    let isLogged = true;          // Kiểu boolean
    let address = null;           // Kiểu null
    let phoneNumber;              // Kiểu undefined
    console.log(typeof age);      // Output: number
    console.log(typeof name);     // Output: string
    console.log(typeof isLogged); // Output: boolean
    console.log(typeof address);  // Output: object
    console.log(typeof phoneNumber); // Output: undefined
    ```
- #### Kiểu đối tượng (Object Types):

  - Kiểu đối tượng (Object): Dùng để lưu trữ một tập hợp các thuộc tính và phương thức. 
  - Ví dụ:
    ```javascript
    let person = {
        name: "John",
        age: 30,
        isStudent: false,
        address: {
        street: "123 Main St",
        city: "New York",
        country: "USA"
    },
        hobbies: ["reading", "traveling", "photography"]
    };
    console.log(person.name);            // Output: John
    console.log(person.age);             // Output: 30
    console.log(person.address.city);     // Output: New York
    console.log(person.hobbies[0]);       // Output: reading
    console.log(typeof person);           // Output: object
    ```
  