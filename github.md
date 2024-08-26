# GIT
# 1.Cài đặt
Dowload tại: [Git](https://git-scm.com/downloads)
Tiếp tục cài đặt bằng cách nhấn next đến cuối cùng và hoàn thành bằng finish

![](image.png)
# 2.Sử dụng Git
**click chuột phải vào bắt kì đâu trên màn hình và open Git Base here** 

![](image-1.png)
và hiện ra một cửa sổ 
![](image-2.png)
## 2.1:Những câu lệnh cơ bản trong Git
- Check version `git --version`
![](image-3.png)

- khai báo tên và địa chỉ email
`git config --global user.name "ntb1926"`
![](image-4.png)

`git config --global user.email "nguyenthanhbinh109206@gmail.com"`
![](image-5.png)

- Kiểm tra khai báo
`cat ~/.gitconfig`
![](image-6.png)

- Tạo local repositories
**Bước 1:Tạo Folder**

`mkdir myproject`

![](image-7.png)

**Bước 2:Truy cập vào bên trong Folder**
`cd myproject/`

![](image-9.png)

**Bước 3:Khởi tạo local repositories**
`git init`

![](image-10.png)

**Bước 4:Add 1 file bất kỳ vào repositories (ở đây mình sử dụng file ảnh)**
`git add anh.PNG`

![](image-11.png)

**Bước 5: Commit**
`git commit -m "upload image"`

![](image-12.png)
**Bước 6:Kiểm tra trạng thái hiện tại của repositories**
`git status`

![](image-13.png)
**Bước 7:Push lên**
`git push`

**Ngoài ra** còn có các lệnh
`git clone`:copy trên mạng về
`git pull`:đồng bộ từ mạng về máy

# GITHUB
# 1.REPO
Git và Github thường được dùng để lưu trữ các file cấu hình của mình, các script, viết các bài hướng dẫn, các bản nháp,... Các repo là những nơi phân loại, lưu trữ những thứ bên trên và nó được lưu cả ở máy trạm và ở server github. Để làm việc với repo thì bạn phải hiểu về nó. Một số điều bạn cần biết là:
**Ba trạng thái của một repo:**
![](https://camo.githubusercontent.com/54064db88d815a41d4993c6ec6f7bf6908b48f0ab76529ff6bb61fd44227825d/687474703a2f2f692e696d6775722e636f6d2f716b6d644a53522e706e67)

**Như hình trên bạn có thể thấy có 3 điểm cần lưu ý:**

- Working dir: đây là nơi bạn thực hiện các thao tác chỉnh sửa với file mã nguồn của mình, nó có thể là eclipse, netbean, notepad++,...

- Stagging area: những sự thay đổi của bạn với file mã nguồn được lưu lại, giống như bạn ấn Save trong một file notepad.

- Git directory: nơi lưu trữ mã nguồn của bạn (ở đây là github)

**Tương ứng với 3 vị trí này ta có các hành động:**
- Add: lưu file thay đổi (mang tính cục bộ) - tương ứng với câu lệnh `git add`

- Commit: Ghi lại trạng thái thay đổi tại máy local (ví dụ như bạn có thể ấn Save nhiều lần với file README.md nhưng chỉ khi commit thì trạng thái của lần ấn Save cuối cùng trước đó mới được lưu lại) - tương ứng với câu lệnh `git commit`

- Push: Đẩy những thay đổi từ máy trạm lên server - tương đương lệnh `git push`

- Pull: đồng bộ trạng thái từ server về máy trạm - tương đương lệnh `git pull`
# 2.Cài đặt trên Windows

**Download tại địa chỉ: [Github](https://windows.github.com/)**
Cài đặt bình thường, yêu cầu phải có .NET 4.5
Giao diện của chương trình:
![](https://camo.githubusercontent.com/384448f508a7d7a2570e987126a21fdcf81e15c3d107853af3b824a5d89249ba/687474703a2f2f692e696d6775722e636f6d2f45627836644a442e706e67)
**Thêm tài khoản Github:**

- Click vào tool and options (hình bánh răng cạnh biểu tượng Sync) chọn options, Add account. Khai báo username và password trên github.

- Tại mục Configure git thêm Tên và email của mình
![](https://camo.githubusercontent.com/e63f24336db7f19ca8fed1b6b37995479d2ff5d794bd5c76a5361b7e13a1b689/687474703a2f2f692e696d6775722e636f6d2f44534c503630692e706e67)

**Click Update**
# 2. Thao tác với Repo 
## 2.1:Tạo repository
![](image-15.png)
## 2.2:Làm việc trên visual code
`git init`:tạo repo trong máy
![](image-16.png)

`git status`:xem trạng thái cái file
![](image.png)

`git add`:cho file vô trong folder
![](image.png)

`git commit -m "tên bạn muốn nhập"`:commit lại file
![](image.png)

`git log`:Kiểm tra xem bạn đã commit chưa
![](image.png)

`git remote add origin https://github.com/ntb1926/Markdown-and-Github.git`:đồng bộ lên trên mạng
![](image.png)

`git push -u origin master`:push lên repo của github
![](image.png)

`git pull`:đồng bộ trên github về visual code.

`echo "github.md" >> README.md`:đổi file trên visual code sang file README.md trên github
