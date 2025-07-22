# 一些入门的视频
- [『教程』一看就懂！Github基础教程](https://www.bilibili.com/video/BV1hS4y1S7wL?vd_source=4fd6c4265e65c0785c912874692a3971)
- [【教程】使用GitHub Desktop管理你的项目】](https://www.bilibili.com/video/BV13W411U7HY?vd_source=4fd6c4265e65c0785c912874692a3971)
- [【大学生扫盲课】1 Git、GitHub 和 Gitee 完整讲解：从基础到进阶功能](https://www.bilibili.com/video/BV1G8CFYvEjt?vd_source=4fd6c4265e65c0785c912874692a3971)

---

# 遇到的一些问题
- [【Github的2FA验证问题的丝滑解决方案 ||（Verify your two-factor authentication (2FA) settings）】](https://www.bilibili.com/video/BV1sj411e7wH?vd_source=4fd6c4265e65c0785c912874692a3971)

---

# 一些小技巧
- 一个github使用小技巧，在看项目的时候，在项目链接中的github后加个1s后回车，即可快速查看。
- 在修改文件和文件夹的目录时，直接进入编辑界面，如下图。
<img width="1371" height="109" alt="Screenshot 2025-07-23 at 00 36 21" src="https://github.com/user-attachments/assets/8e102fac-fb78-43e7-aa79-0abe13da2517" />
- 如果添加上级目录直接打出上级目录名称（无论之前是否存在），例如
```bash
  Markdown-dailyrecords/test/github_using.md
```
点击回车，commit changes即可，实现了将md文件移动到test文件夹下的操作，删除上级目录同理


---

# Github repository 协议选择
GitHub 有许多开源的协议，刚开始使用时不知道选择哪些协议，今天我们就一起科普一下 GitHub 中的协议吧！

## 一、协议介绍

1. **None / No License**  
   默认情况下，如果未在仓库中选择协议，则为 No License，表示不允许他人复制、分发、使用和修改。但在 GitHub 上，仍可查看（view）源码和 Fork。

2. **Apache License 2.0**  
   来自 Apache 基金会，允许个人使用、商业使用、复制、分发、修改，作者免责。需保留版权信息、声明变更，并对贡献者提供快速专利授予。

3. **MIT License**  
   与 BSD 同为宽松协议，只需在发行版中包含原许可协议声明。允许任何人个人/商业使用、复制、分发、修改，唯一限制是保留版权信息。

4. **GNU GPLv3**  
   允许个人/商业使用、专利授权、复制、分发、修改，作者免责。但要求：
   - 必须开源：所有修改后的源代码必须开源。  
   - 保留协议和版权：保留原协议和版权声明。  
   - 不允许更换协议：衍生代码必须继续使用 GPL。  
   - 声明变更：需有文档说明改动。

5. **BSD 2-Clause “Simplified” License**  
   允许个人/商业使用、复制、分发、修改，需保留作者版权和免责声明，免除作者责任。

6. **BSD 3-Clause “New” or “Revised” License**  
   在 BSD 2-Clause 基础上，增加“未经特别许可，不得使用作者或贡献者姓名推广衍生产品”。

7. **Eclipse Public License 2.0**  
   商业友好，允许个人/商业使用、专利授权、复制、分发、修改，作者免责。需保留版权、开源、不允许更换协议，对专利授权免版税。

8. **GNU Affero GPL v3.0**  
   类似 GPLv3，但如果通过网络提供服务，必须公开修改过的完整源代码。

9. **GNU GPLv2**  
   与 GPLv3 相比，不包含专利授予条款。

10. **Mozilla Public License 2.0**  
    BSD 和 GPL 的折中，允许个人/商业使用、专利授权、复制、分发、修改，作者免责。需保留版权、开源，不允许更换协议（但可换为某些 GNU 协议），不允许使用商标。

11. **The Unlicense**  
    完全无约束，作者放弃所有权利，任何人可为任何目的使用，无需保留信息，作者免责。

## 二、特性总结

（此处可根据需求列出各协议的核心对比表或要点汇总）

## 三、使用推荐

1. **普通开发者**  
   推荐 MIT License，保留版权信息，又允许他人修改。

2. **使用了 GNU 库的开发者**  
   由于“传染性”，需选择 GNU 相关协议。

3. **开源库开发者**  
   推荐使用 GNU LGPL 系列协议。

4. **无私奉献者**  
   选择 The Unlicense。

5. **不确定如何选择**  
   默认 None 保留全部权利，后续再决定。

> 版权声明：本文为博主原创文章，遵循 CC 4.0 BY‑SA 版权协议，转载请附上原文出处链接和本声明  
原文链接：https://blog.csdn.net/qq_42768234/article/details/104193778
---

# 未添加协议的repository后期添加协议的方法
https://zhuoqianmingyue.blog.csdn.net/article/details/88819606?fromshare=blogdetail&sharetype=blogdetail&sharerId=88819606&sharerefer=PC&sharesource=Carter_Yin&sharefrom=from_link
