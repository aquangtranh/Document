## Document

#ssh key 

- Bước 1: Kiểm tra xem máy bạn có ssh key nào chưa

Mở cửa sổ dòng lệnh (terminal) và chạy lệnh:

ls -al ~/.ssh

- Bước 2: Sinh một SSH key mới

Chạy lệnh sau trên terminal

ssh-keygen -t rsa -b 4096 -C "email_cua_ban@example.com"

- Bước 3 Add ssh key vào github 

 + Copy ssh key :
 
pbcopy < ~/.ssh/id_rsa.pub

 + Add vào github

https://github.com/settings/keys

- Bước 4: Kiếm tra lại xem mọi thứ đã OK chưa:

ssh -T git@bitbucket.org
or
ssh -T git@github.com

#Cài đặt môi trường PHP
 
 1. Virtual box 
 
https://www.virtualbox.org/wiki/Downloads
 
 2. Vagrant 
 
https://www.vagrantup.com/downloads.html
 
 3. Sublime text 3
 
https://www.sublimetext.com/3
 
 4. Terminal 
 
 - for Mac : iTerm
 
https://www.iterm2.com/
 
 5. Homestead
 
 - Setup virtual box and vagrant first
 - Add homestead box (in cd~)
 
vagrant box add laravel/homestead

- Install Homestead

cd ~

git clone https://github.com/laravel/homestead.git Homestead

- Next step

cd Homestead/

bash init.sh

- Extra config reference :

https://laravel.com/docs/5.3/homestead
 
 
 
