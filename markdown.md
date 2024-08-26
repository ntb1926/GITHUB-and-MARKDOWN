# 1.Tiêu đề
Bạn có thể viết loại tiêu đề bằng cách thêm các dấu # tương ứng vào đầu dòng.
**Một** dấu **#** tương đương với **tiêu đề 1** , **hai** dấu **#** tương đương với **tiều đề 2**
**Cú pháp:**
```
# Tiêu đề loại 1
## Tiêu đề loại 2
### Tiêu đề loại 3
#### Tiêu đề loại 4
##### Tiêu đề loại 5
###### Tiêu đề loại 6
```
**Kết quả**
# Tiêu đề loại 1
## Tiêu đề loại 2
### Tiêu đề loại 3
#### Tiêu đề loại 4
##### Tiêu đề loại 5
###### Tiêu đề loại 6
# 2.Nhấn mạnh
## 2.1:Chữ in nghiêng
Để in nghiêng văn bản , thêm một dấu * hoặc dấu _ trước và sau từ cần in nghiêng.

**Cú pháp:**
```
*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_
```
**Kết quả**
*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_
## 2.2:Chữ in đậm
Để in đậm văn bản , thêm hai dấu * hoặc dấu _ trước và sau từ cần in đậm.

**Cú pháp**
```
**Từ cần in đậm 1**

__Từ cần in đậm 2__
```
**Kết quả**
**Từ cần in đậm 1**

__Từ cần in đậm 2__
## 2.3:In đậm và in nghiêng
 bạn chỉ cần ba dấu * hoặc dấu _ trước và sau từ đó.
 **Cú pháp:**
 ```
 ***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___
```
**Kết quả**
***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___
## 2.4:Gạch chữ
Để tạo chữ gạch giữa, thêm 2 dấu ~ trước và sau từ đó.

**Cú pháp:**
```
~~Khuyến mại~~
```

**Kết quả**
~~Khuyến mại~~
## 2.5:Code trong dòng - Inline Code
bạn dùng 2 dấu ` ở trước và sau từ đó.

**Cú pháp:**
```
`inline code`
```
**Kết quả**
`inline code`
# 3.Các khối    
## 3.1:Trích dẫn
Để tạo ta thêm dấu > vào trước mỗi dòng trích dẫn.

**Cú pháp:**
```
> Trích dẫn dòng 1
> Trích dẫn dòng 2
```
**Kết quả:**
> Trích dẫn dòng 1
> Trích dẫn dòng 2
## 3.2:Danh sách có thứ tự 
Để tạo danh sách, bạn chỉ cần thêm các số, dấu chấm trước nội dung (dùng tab để phân cấp)

**Cú pháp:**
```
1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba
```
**Kết quả**
1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba
## 3.3:Danh sách không có thứ tự
Để tạo danh sách, bạn chỉ cần thêm dấu * hoặc - hoặc + trước nội dung (dùng tab để phân cấp)

**Cú pháp:**
```
- Mục thứ nhất
- Mục thứ hai
- Mục thứ ba
```
**Kết quả:**
- Mục thứ nhất
- Mục thứ hai
- Mục thứ ba
## 3.4:Khối lệnh 
Để viết 1 đoạn, bạn dùng 3 dấu ` ở trước và sau đoạn đó (có thể thêm format ngôn ngữ đó).

**Cú pháp:**
![](https://user-images.githubusercontent.com/90561566/160242871-aad90ad1-bd8d-4e5c-9146-3349fb7c8c98.png)

Kết quả:
```python
print ("hello world")
```
## 3.5:Bảng
Để tạo bảng, bạn chỉ cần ngăn cách bởi dấu | và cách đầu bảng với thân bảng bằng :--- (số dấu - tuỳ ý)

**Cấu trúc:**
```
| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |
```
**Kết quả**
| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |
# 4.Đặc biệt
## 4.1:Đường kẻ ngang 
Để tạo đường kẻ ngang, sử dụng ba dấu * hoặc - hoặc _ trên một dòng.

**Cú pháp:**
```
---
***
___
```
---
***
___
## 4.2:Liên kết - Link
Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn liên kết `<a href="https://github.com">Github</a>`, bạn dùng `[text](link).`
Cú pháp:
```
Trực tiếp: https://github.com/lucthienphong1120

Gián tiếp: [Github](https://github.com)

```
**Kết quả:**
Trực tiếp: https://github.com/lucthienphong1120

Gián tiếp: [Github](https://github.com/lucthienphong1120)
## 4.3:Hình ảnh
Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn ảnh `<img src="https://avatars.githubusercontent.com/u/583231 alt="Github">`, bạn dùng `![text](link ảnh)`.

Hoặc `![](link ảnh)` nếu không cần chữ khi hover.

**Cú pháp:**
```
![](https://avatars.githubusercontent.com/u/583231)
```
**Kết quả**
![](https://avatars.githubusercontent.com/u/583231)
