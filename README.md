# SSL-Cert
HTTPS自签名证书生成脚本

## 用法

1. 打开`cert_config.conf`文件，设置相关配置。比如DNS
2. 运行`gencert.sh`脚本，依次输入国家代码，省份，城市，组织名称，常用名称，邮箱地址。
3. `output`文件夹下面将生成`cert.key`和`cert.pem`文件。其中`cert.key`为私钥。