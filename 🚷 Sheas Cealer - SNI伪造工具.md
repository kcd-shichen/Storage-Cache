
<h1 align="center"><img src="/files/f23328b5-b8f8-4643-b70c-5dc6886bf226/0.png" width="20%" alt="替代文字" /></h1>

<h3 align="center">**Sheas Cealer** <mark>**使用指南**</mark></h3>

<br></br>
 **chrome://flags/enable-command-line-on-non-rooted-devices**

- [x] **启用此项**


![1.jpg](/files/f23328b5-b8f8-4643-b70c-5dc6886bf226/1.jpg)

并在  /data/local/tmp/  目录下创建**空文件**：
### **chrome-command-line**
- [x] 文件权限 设为 **666**

</br>

---
## 命令行创建

### 手机端：( 去除原指令 " adb shell " 部分 )
`touch /data/local/tmp/chrome-command-line`
- [X] 创建空文件 chrome-command-line

`chmod 666 /data/local/tmp/chrome-command-line`
- [X] 设置权限 666


</br>

---
## 网站规则
# 1. HelloGithub.com

![2.jpg](/files/f23328b5-b8f8-4643-b70c-5dc6886bf226/2.jpg)
> ### HelloGithub.com是一开源项目推荐网站，其域名命中上游规则 *github.com

导致伪造后跳转至 github.com

解决方法：

```
[["*hellogithub.com"], "", "117.50.220.24"]
```
</br>

# 2. Hanime1.me

![Screenshot_2026-04-06-08-51-58-799_top.qwq2333.nullgram-edit.jpg](/files/f23328b5-b8f8-4643-b70c-5dc6886bf226/3.jpg)
这个要填第二个参数，解决方法：
```
[["*hanime1.me"],"hanime1.me","104.26.8.104"]
```
</br>

# 3.

<br></br>

# 总规则条目
</br>
[["*hellogithub.com"], "", "117.50.220.24"],
[["*hanime1.me"],"hanime1.me","104.26.8.104"],