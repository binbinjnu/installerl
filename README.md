# installerl

```sh
yum install -y which wget perl openssl-devel make automake autoconf ncurses-devel gcc // 安装依赖
curl -O http://erlang.org/download/otp_src_22.1.tar.gz
tar -zvxf otp_src_22.1.tar.gz 
cd otp_src_22.1
./otp_build autoconf
./configure && make && make install
```
