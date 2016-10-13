# Document

#ssh key 

- Bước 1: Kiểm tra xem máy bạn có ssh key nào chưa

Mở cửa sổ dòng lệnh (terminal) và chạy lệnh:
ls -al ~/.ssh

- Bước 2: Sinh một SSH key mới

Chạy lệnh sau trên terminal

ssh-keygen -t rsa -b 4096 -C "email_cua_ban@example.com"


 
