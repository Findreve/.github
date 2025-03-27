<h1 align="center">
  <br>
  <a href="https://find.yxqi.cn" alt="logo" ><img src="../Findreve.png" width="150"/></a>
  <br>
  Findreve
  <br>
</h1>
<h4 align="center">Track, Tag, and Retrieve – Simplifying Item Recovery.</h4>

<p align="center">
  <a href="https://www.yxqi.cn">Homepage</a> •
  <a href="https://find.yxqi.cn">Demo</a> •
  <a href="https://findreve.yxqi.cn">Documents</a> •
  <a href="https://github.com/Findreve/Findreve/releases">Download</a> •
  <a href="#License">License</a> •
  <a href="https://auth.yxqi.cn/product/5">Pricing</a>
</p>

## 介绍 Introduction
Findreve 是一款强大且直观的解决方案，旨在帮助您管理个人物品，并确保丢失后能够安全找回。
每个物品都会被分配一个 `唯一 ID` ，并生成一个 `安全链接` ，可轻松嵌入到 `二维码` 或 `NFC 标签` 中。
当扫描该代码时，会将拾得者引导至一个专门的网页，上面显示物品详情和您的联系信息，既保障隐私又便于沟通。
无论您是在管理个人物品还是专业资产，Findreve 都能以高效、简便的方式弥合丢失与找回之间的距离。

Findreve is a powerful yet intuitive solution designed to help you manage your belongings
and ensure their safe return if lost. Each item is assigned a `unique ID` and generates a
`secure link`, easily embedded into a `QR code` or `NFC tag`. When scanned, the code directs
finders to a dedicated webpage displaying item details and your contact information, 
ensuring privacy and ease of communication. Whether you’re managing personal belongings
or professional assets, Findreve bridges the gap between lost and found with efficiency
and simplicity.

## 安装 Install
你需要安装 Python 3.8 以上的版本(但我推荐 3.12.2 )。然后，clone 本仓库到您的服务器并解压，然后安装下面的依赖：

Findreve is a Python-based application. You need to have Python 3.8 or higher installed on
your server. Then, clone this repository to your server and install the required
dependencies:

- **NiceGUI**: `pip install nicegui==2.13.0` if Windows else `pip3 install nicegui==2.13.0`
- **aiosqlite**: `pip install aiosqlite` if Windows else `pip3 install aiosqlite`
- **QRCode**: `pip install QRCode` if Windows else `pip3 install QRCode`

## 启动 Launch
使用下面的命令来启动 Findreve:
Run the following command to start Findreve:
> Python main.py

启动后， Findreve 会在程序的根目录自动创建 SQLite 数据库，并在
终端显示管理员账号密码。请注意，账号密码仅显示一次，请注意保管。

Upon launch, Findreve will create a SQLite database in the project's root directory and
display the administrator's account and password in the console.

## Stacks
- Nicegui + FastAPI
- JWT (since V1.2.0)

## 许可证 License
此仓库的 Findreve 是社区版，完全免费，基于 GPLv3 协议。

Open Source Free Version: Licensed under the `GPLv3`.

基于赞助的专业版：基于您的赞助，您可获得附加功能和源代码的版本，允许进一步开发用于个人或内部使用。然而，不允许重新分发修改后的或原始的源代码。

Donation-Based Premium Version: By making a donation, you can access a version with additional features and source code, which allows further development for personal or internal use. However, redistribution of the modified or original source code is not permitted.
