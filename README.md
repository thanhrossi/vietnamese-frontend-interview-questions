# Tuyển tập câu hỏi phỏng vấn Front-end

Mục đích của trang là tổng hợp lại danh sách các câu hỏi tham khảo phỏng vấn cho vị trí lập trình viên Front-end. 

Với mong muốn giúp những ai đang sắp được phỏng vấn chuẩn bị tốt hơn, đồng thời
giúp ôn lại các kiến thức về front-end một cách vững chắc nhất. 

Mình tha thiết mong muốn mọi người cùng đóng góp nội dung, [tại đây](#how-to-contribute).

![](http://i.imgur.com/qJhyreL.jpg)

# Table of Contents

1. [Hỏi chung](#hỏi-chung)
2. [Hỏi về HTML](#hỏi-về-html)
3. [Hỏi về CSS](#hỏi-về-css)
4. [Hỏi về Javascript](#hỏi-về-javascript)
5. [Hỏi về Testing](#hỏi-về-testing)
6. [Hỏi về Performance](#hỏi-về-performance)
7. [Hỏi về Network](#hỏi-về-network)
8. [Hỏi về Coding](#hỏi-về-coding)
9. [Hỏi chơi cho vui](#hỏi-chơi-cho-vui)

# Getting Involved

1. [Contributors](#contributors)
2. [How to Contribute](#how-to-contribute)
3. [License](https://github.com/duyetdev/frontend-interview-questions-vietnamese/blob/master/LICENSE)

------------------------------------------

## Hỏi chung

* Những điểm nào mà bạn thích, hoặc không thích về lập trình?
* Khác nhau giữa UI và UX?
* Nói về môi trường làm việc mà bạn mong muốn?
* Ba cách để giảm dung lượng tải trang?
* CORS?
* Bla bla ...

## Hỏi về HTML

* Tác dụng của `doctype`?
* Khác nhau giữa HTML và XHTML là gì?
* Có vấn đề gì không nếu lưu trang MIME dạng `application/xhtml+xml`?
* Điều gì mà bạn cần phải chú ý nếu xây dựng và phát triển các trang web đa ngôn ngữ?
* Thuộc tính `data-` dùng để làm gì?
* Nếu HTML5 là nguồn mở, thẻ HTML nào mà bạn sẽ phát triển thêm?
* Khác nhau giữa `cookie`, `sessionStorage` và `localStorage`.
* Khác nhau giữa `<script>`, `<script async>` và `<script defer>`.
* Tại sao nên đặt `<link>` trong thẻ `<head></head>` và đặt `<script>` sau thẻ `</body>`. Ngoại lệ khi nào?
* HTML processor là gì, bạn biết những HTML processor nào ?
* Sematic HTML là gì?
* Sự khác nhau giữa SVG và canvas?

## Hỏi về CSS

* CSS framework là gì?
* Có mấy cách để sử dụng CSS trên trang web?
* Lợi / hại của việc sử dụng External Style Sheets?
* Giải thích Ruleset là gì?
* **Case-sensitivity** - ngôn ngữ css có phân biệt hoa thường khi nào? 
* Khác nhau giữa Class selector và Id selector?
* Pseudo-elements là gì?
* Cách nào đổi khôi phục thuộc tính mặc định của một đối tượng? 
 * Ex: thẻ `<a class="color1 color2">` có màu đỏ, sau đó bị class `color2` đè lên thành màu xanh. Cú pháp nào để khôi phục lại thành màu trước đó?
* `z-index` dùng để làm gì?
* Tại sao `@import` chỉ có thể sử dụng ở đầu file?
* CSS processor là gì, ưu và nhược điểm?
* BEM, SMACSS, OOCSS là gì?
* Bạn hãy cho biết các thành phần của box model trong css
* Transition và animation khác nhau như thế nào ? Hãy cho một ví dụ
* Cách để căn giữa các phần tử theo chiều dọc, chiều ngang, độ dài và rộng cố định hoặc không xác định
* Các phương pháp để cross browser
* Perfect pixel là gì ? làm thế nào để thực hiện nó
* Sự khác nhau giữa display: none , visibility hidden và opacity: 0?
* Có bao nhiêu loại màu trong CSS, hãy liệt kê nó
* * { box-sizing: border-box; }  có nghĩa là gì ? Hãy giải thích 

*(Coming soon)*

## Hỏi về Javascript

* Ý nghĩa của biến `this`.
* Sử dụng **AMD** và **CommonJS** có tốt hay không? Tại sao tốt hoặc không tốt?
* Nếu viết theo kiểu IIFE, tại sao đoạn mã sau bị lỗi? `function foo(){ }();`
  * Sửa lại
* Khác nhau giữa `null`, `undefined` hoặc chưa khai báo?
  * Cách kiểm tra từng trường hợp trên.
* Khác nhau giữa **host objects** và **native objects** là gì?
* Javascript closure là gì?
* `ES6` Yeild là gì? [giải thích](https://blog.duyetdev.com/2016/02/generator-function-javascript.html)
* `ES6` Function* là gì? [giải thích](https://blog.duyetdev.com/2016/02/generator-function-javascript.html)

## Hỏi về Testing 

* Có nên sử dụng các công cụ Lint Style hay không? Tại sao?

## Hỏi về Performance

* Bạn hay xài công cụ nào để kiểm tra lỗi về hiệu suất tải trên trình duyệt? 
* Giải thích sự khác nhau giữa layout, painting và compositing.

## Hỏi về Network

* Tại sao lưu resource (js/css/...) trên nhiều domain sẽ tốt hơn? 
* Sự khác nhau giữa Long-Polling, Websockets và Server-Sent?
* Giải thích ý nghĩa của mấy cái HTTP Header sau:
  * Diff. between Expires, Date, Age and If-Modified-...
  * Do Not Track
  * Cache-Control
  * Transfer-Encoding
  * ETag
  * X-Frame-Options
* HTTP action là gì?

## Hỏi về Coding
**Hỏi:** `foo` có giá trị là bao nhiêu?
```js
var foo = 10 + '20';
```

**Hỏi:** Viết hàm `add` để thực hiện được câu lệnh sau:
```js
add(2, 5); // 7
add(2)(5); // 7
```

**Hỏi:** Kết quả trả về của hàm lệnh sau là gì?
```js
"i'm a developer".split("").reverse().join("");
```

**Hỏi:** Giá trị của `window.foo` là gì?
```js
( window.foo || ( window.foo = "bar" ) );
```

**Hỏi:** Kết quả của 2 lệnh `alert` là gì?
```js
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

**Hỏi:** Giá trị của `foo.length` trong trường hợp sau?
```js
var foo = [];
foo.push(1);
foo.push(2);
```

**Hỏi:** Giá trị của `foo.x` trong trường hợp sau?
```js
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

**Hỏi:** Các lệnh sau sẽ in ra console cái gì?
```js
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```


## Hỏi chơi cho vui 

* Những dữ án nào mà bạn cho là thú vụ đã từng làm qua?
* Bạn hay sử dụng các công cụ (tools) nào? 
* Bạn thích tính năng nào của Internet Explorer nhất?
* Hãy giải thích một cách đơn giản nhất cho người không biết gì về công nghệ có thể hiểu được công việc của một FE dev

------------------------------------------

# Contributors
* 15/12/2015, dự án được khởi động bởi [@duyetdev](https://github.com/duyetdev)

# How to Contribute
Trang được xây dựng bởi cộng đồng. Để đóng góp vào danh sách câu hỏi, vui lòng: 

1. Fork repo tại Github: [https://github.com/duyetdev/frontend-interview-questions-vietnamese](https://github.com/duyetdev/frontend-interview-questions-vietnamese)
2. Commit câu hỏi trực tiếp vào file README.md, nhánh master.
3. Tạo Pull Request.
