# OOP

<details>
<summary>Tính đóng gói (encapsulation)</summary>
  
- Dữ liệu và các hành động liên quan tới dữ liệu của class nào thì gói gọn bên trong class đó.
- - Các thuộc tính của lớp để là ``` private ```
- - Chỉ có thể truy cập trực tiếp tới thuộc tính private từ bên trong class chứa nó.
    
- => Muốn truy cập đến thuộc tính ``` private ``` của class phải qua các ``` public ``` getter/setter.
> Bảo mật và bảo vệ dữ liệu không bị truy cập trái phép.
</details>

<details>
<summary>Tính kế thừa (inheritance)</summary>
  
- Thừa hưởng các đặc trưng và hành động từ 1 class khác.
  
-  Biểu hiện : class con ``` extends ``` lớp cha , lớp A ``` implements ``` C giúp ta tái sử dụng code đã có nhưng vẫn đảm bảo, duy trì 1 hệ thống phân cấp duy nhất.
- Lớp cha sẽ tổng quát hơn , simple hơn lớp con. Lớp con ( super ) cụ thể và đa dạng hơn lớp cha.
</details>

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

<details>
<summary>Tính trừu tượng (abstract)</summary>
  
- Là tính chất trong đó chỉ tiết lộ những thành phần thiết yếu với người dùng và ẩn giấu đi những thông tin không cần thiết.
- Thể hiện qua abstract class và interface.
- Thường chỉ nêu lên nhiệm vụ nhưng không nói cụ thể cách thức triển khai.
- Sử dụng tính trừu tượng giúp giảm sự phức tạp và ẩn giấu các triển khai quan trọng khỏi thế giới bên ngoài.



<details>
<summary>Khi nào sử dụng abstract class?</summary>
  
- Khi bạn có một nhóm các lớp liên quan cần share chung 1 đoạn code hay tính năng nào đó. Bạn đưa các thành phần dùng chung vào lớp abstract và các lớp con liên quan sẽ kế thừa lớp cha abstract này.
- Khi bạn mong muốn rằng các lớp kế thừa lớp abstract có chung nhiều trường, phương thức hoặc muốn dùng chung cả các access modifier khác chứ không chỉ là access modifier ``` public ```.
__Bạn muốn khai báo các trường non-static , non-final. Nhờ đó bạn có thể định nghĩa các phương thức có thể truy cập và sửa đổi trạng thái của từng đối tượng.__

</details>


<details>
<summary>Khi nào sử dụng interface?</summary>
  
- Đạt được tính trừu tượng hòan toàn. Tất cả các method được nêu ra trong interface chưa có phần thân triển khai chi tiết và cần được triển khai cụ thể trong các lớp con implements interface đó.
- Muốn đạt được tính đa kế thừa.
- Muốn cho các lớp không liên quan gì đến nhau cũng có thể sử dụng chức năng của interface.
- Muốn chỉ định các hành vi cần thực hiện nhưng không quan tâm các hành vi đó được thực hiện bởi ai, thực hiện như thế nào.

</details>

</details>
