# NSUedu
成都东软学院||东软智慧教学重制版：快捷手势、扫码签到

# 使用方法
下载apk程序
1. 登录账号
2. 选择科目
3. 一键签到

# 演示
![IMG_20241111_214103](https://github.com/user-attachments/assets/8619ba99-16f3-44de-bf78-792e5147cf35)

# 信息
- 本项目使用 `iapp` 开发
- 本项目不会记录个人信息
- 签到下方会有`手势/二维码`其他人可扫 ~独乐乐不如众乐乐~

# (登录选项)高级模式：
- 有token直接使用token登录 *(速度最快)*
- 没有token使用学号+密文登录
- 普通模式下使用学号+密码生成密文登录 *(速度最慢)*

# 其他
密文是如何生成的 ~(分析了半天)~
1. aes ecb padding 128位加密 *(密钥：757da2be61249c18)*
2. base64编码
3. 得到密文

*made by 24级新生*
