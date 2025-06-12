# demo-gitflow
# GIT là gì ?
Git la he thong quan ly phien ban phan tan
- Theo dõi lịch sử thay đổi của dự án ( mã code, ... )
Quản lý nhiều nhánh phát triền song song
- Cho phép nhiều người cùng làm việc tre một dự an ma không bị xung đột (conflict)
# Các khái niệm cơ bản trong GIT
## Repository
-kho chứa mã nguồn dự án, chứa local hoặc remote (sever)
## commit
ghi lại trạng thái mã nguồn
## branch
nhánh phát chuyển riêng biệt
## merge
gộp branch vào 1 nhánh khác
## Clone
tải repo từ máy chủ về mày 
## pull
đẩy code mới nhất từ trên nhánh sever về local
## pushh
đẩy code commit từ local lên nhánh sever
## 1 số lệnh cơ bản
-git init : khai báo 1 dự án bắt đầu sữ dụng git
- git status: kiểm tra thay đổi trong 1 file dự án
-git add + file_name:xách nhận thêm file thay đổi vào repo của local
-git add .: xác nhận thêm tất cả file thay đổi vào repo local (sẵn sàng cho commit)
-git commit -m "your comment" đẩy các file thay đổi vào store local sẵn sàng cho push code lên sever và đồng thời thêm comment
-git push orgigin your_branch: đẩy code từ local vào nhánh your_branh trên server
-git checkout -b branch_name : tạo 1 nhánh mới tên là branch name đồng thời di chuyển sang nhánh đó
