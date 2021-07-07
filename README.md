# AttackTest
脚本主要对一些常用漏洞和payload构造请求发送到指定目标，用于测试防火墙等安全设备对攻击的拦截与告警功能

## Usage
`python Main.py --url http://www.text.com --type dirscan --time 10`

```
Usage: Main.py [options] args

Options:
  -h, --help   show this help message and exit
  --url=URL    攻击对象，eg:http://192.168.111.1
  --time=TIME  攻击时间，单位：秒，默认180s
  --type=TYPE  攻击类型，可选参数：sqlinject（sql注入）、struts2、dirscan（目录扫描）、xss、weblogic、r
               ce（命令注入）、codeinject（代码注入）、info（信息泄露）、weakpasswd（弱口令与明文传输）、uploa
               d（文件上传）、XXE（XML实体注入）
```
