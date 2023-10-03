# OOP

<details>
<summary>Tính đóng gói (encapsulation)</summary>
  
- Dữ liệu và các hành động liên quan tới dữ liệu của class nào thì gói gọn bên trong class đó.
- - Các thuộc tính của lớp để là ``` private```
- - Chỉ có thể truy cập trực tiếp tới thuộc tính private từ bên trong class chứa nó
=> Muốn truy cập đến thuộc tính ``` private ``` của class phải qua các ``` public ``` getter/setter.
> Bảo mật và bảo vệ dữ liệu không bị truy cập trái phép.
</details>

tính kế thừa (inheritance)
Thừa hưởng các đặc trưng và hành động từ 1 class khác
Biểu hiện : class con ``` extends ``` lớp cha , lớp A ``` implements``` C
giúp ta tái sử dụng code đã có nhưng vẫn đảm bảo, duy trì 1 hệ thống phân cấp duy nhất.
Lớp cha sẽ tổng quát hơn , simple hơn lớp con. Lớp con ( super ) cụ thể và đa dạng hơn lớp cha.

<details>
<summary>Tính đa hình (Polymorphism)</summary>

- Là một đối tượng có nhiều vai trò, hình dạng tùy thuộc các ngữ cảnh khác nhau.
- Biểu hiện : overriding (ghi đè) và overloading (nạp chồng).

_Nạp chồng_ : thể hiện tính đa hình tại thời điểm biên dịch chương trình ( compile time polymorphism ).

_Ghi đè_ : thể hiện tính đa hình tại thời điểm chạy chương trình ( runtime polymorphism ).

> Tính đa hình cho phép các đối tượng khác nhau sử dụng chung một giao diện ( interface ).

>> Note : 

```
nạp chồng : hàm cùng tên / lớp + kiểu dữ liệu và tham số 
ghi đè : cùng tên , cùng kiểu + khác lớp
```

</details>
