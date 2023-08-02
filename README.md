# Telnet Bruter

Công cụ này được sử dụng để tạo danh sách kết hợp telnet bằng cách sử dụng danh sách địa chỉ ip. Nó sẽ thử hàng chục mật khẩu mặc định và gửi cho bạn kết quả trong thiết bị xuất chuẩn và trong một tệp.

### Installation
Cài đặt ứng dụng trên máy chủ
```sh
git clone https://github.com/DauDau432/telnet-bruter.git
cd ./telnet-bruter/
gcc ./*.c -o telnet-bruter -pthread -std=c99 -fcommon
zmap -p 23 | ./telnet-bruter <threads>
```

![image](https://user-images.githubusercontent.com/69421356/192002873-c8f5fd0d-9866-43dc-a18a-59b9ddf051f3.png)

### Nguồn 
[https://github.com/Inplex-sys/telnet-bruter.git](https://github.com/Inplex-sys/telnet-bruter.git)
