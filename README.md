# install erl
```sh
yum install -y which wget perl openssl-devel make automake autoconf ncurses-devel gcc // 安装依赖
curl -O http://erlang.org/download/otp_src_22.1.tar.gz
tar -zvxf otp_src_22.1.tar.gz 
cd otp_src_22.1
./otp_build autoconf
./configure && make && make install
```

# install rebar3
```sh
root用户根目录下
mkdir download
cd download
git clone https://github.com/erlang/rebar3.git
cd rebar3
./bootstrap
mv -f /root/download/rebar3 /usr/lib/
ln -s /usr/lib/rebar3/rebar3 /usr/local/bin/rebar3
```
