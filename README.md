# Driver03

driver được phát triển trên hệ điều hành ubuntu phiên bản 20.04.3-desktop-amd64
link download: https://old-releases.ubuntu.com/releases/20.04.3/

sau khi cài đặt ubuntu thành công, thực hiện cập nhật bằng câu lệnh: $ sudo apt update

cài đặt build-essential: $ sudo apt instal build-esential
cài đặt git: $ sudo apt install git

thực hiện clone project: git clone 'repo...'

mở thư mục project vừa clone, di chuyển đến thư mục encrypt_module, click chuột phải, Open in Terminal

thực hiện make file bằng câu lệnh: $ make

Sau khi make file thành công, thực hiện install: $ make install
Install xong, thoát Terminal, tại thư mục 'driver03' mở Open in Terminal 3tabs

- Tab1: dùng cho hiển thị thông tin server: $ ./server

- Tab2: dùng cho hiển thị client1: 
  $ sudo ./client
  (đặt tên cho client) VD: client1 

- Tab3: dùng cho hiển thị client2: 
  $ sudo ./client
  (đặt tên cho client) VD: client2

Sau khi đặt tên xong, server đã hiển thị nhận được 2 client, lúc này client có thể chat với nhau
