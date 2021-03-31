Flex Box

1. display: flex;
- Quy định tất cả các thẻ con nằm bên trong thẻ mang thuộc "display: flex;" sẽ nằm ngang hàng nhau

2. flex-direction
	Values:
		- column: Điều hướng theo trục y
		- column-reverse: Điều hướng theo trục y và đảo ngược các phần tử
		- row: Điều hướng theo trục x
		- row-reverse: Điều hướng theo trục x và đảo ngược các phần tử

- Điều hướng các thẻ bên trong thẻ cha theo các hướng
	- Chiều của trục x
	- Chiều của trục y

3. flex-flow: row wrap;
- Giúp điều hướng các thẻ ở bên trong, qui định các thẻ đó có fit với chiều rộng của thẻ cha hay không.

Values:
	- row
	- row-reverse
	- column
	- column-reverse

4. flex-grow
- Qui định độ rộng cho thẻ được set thuộc tính flex-grow. Chiều rộng sẽ tỷ lệ với độ rộng của thẻ trừ đi kích thước của các thẻ con còn lại. 
Lưu ý:
	flex-shrink càng lớn thì chiều rộng càng nhỏ và ngược lại


5. Flex Basic
- QUi định độ rộng cho các thẻ con
Đơn vị: ?px | auto | 0


6. justify-content
- Căn nội dung theo chiều ngang
	- Center 
	- flex-start (left)
	- flex-end (right)

7. align-item
- Căn nội dung theo chiều dọc
	- Center 
	- flex-start (top)
	- flex-end (bottom)