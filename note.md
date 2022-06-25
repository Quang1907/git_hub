# Config

- tên : git config -g user.name "name"
- email : git config -g user.email "email"
- kiem tra ten : git config user.name

# Terms

Repository (Repo)
Branch
Conflict <!-- Xung dot-->
Local
Remote

# Commands

- git init <!-- tao git repository -->
- git status <!-- xem trang thai du an thay doi-->
- git add <!-- Chuan bi luu  lai du an-->
- git reset <!-- xoa tat ca nhung thu muc da chon-->
- git commit -m "note" <!--Ghi chu truoc khi luu-->
- git log <!-- Xem cac phien ban commit từ mới đến cũ-->
- git log --reverse <!-- Nguoc lai-->
- git log --oneline <!-- Cac commit dau tien o tren cung -->
- git checkout {id commit} <!-- Quay tro lai commit-->
- git checkout master <!-- Quay tro lai phien ban moi nhat-->
- git branch <!-- Cành mặt định là master -->
- git checkout -b {branch name} <!-- Tao branch mới -->
- git merge {branch name} <!-- Tong hop cac branch-->
- git branch -d {branch name} <!-- Xoa branch-->
- git push <!-- Day tu local len remote-->
- git fetch origin {branch name}
- git pull {repo url}
- git checkout -b {branch name} origin/{branch name}
