## Demo-first_created

---

### steps on how to creat one's first repository

: 

1. download "git for windows and install it.

> ps: *You can search for the [download URL compiled by others](https://github.com/waylau/git-for-win) in the GitHub search bar,select the corresponding version and download it directly.* :stuck_out_tongue_closed_eyes:
or you can register and download it on the official website :smile:

2. On the top right corner of the GitHub homepage, click the "+" symbol and select "New repository" and confirm.

![示例~1~](.\pics\where to creat.png "where to click")

3. Create a new folder to store local-related files. Use git for windows to clone the link of the new repository to this folder.

4. Then just push new files into this repository.
> ps: when you push you might meet the following fault.

![error1](.\pics\error1.png)

> you can manage it with the following codes.(with bash)

```bash

# 设置邮箱（替换成你的真实邮箱）
git config --global user.email "you@example.com"

# 设置用户名（替换成你的名字）
git config --global user.name "Your Name"

```

:cry:

> you can exam if it succed to run by...(with bash)

```bash

# 检查全局配置
git config --global --get user.email
git config --global --get user.name

# 或检查当前仓库配置
git config --get user.email
git config --get user.name

```

==Thats all,thanks!==

---

