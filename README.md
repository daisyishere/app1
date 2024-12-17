# app1
# 英语背单词系统 - Android 平台

本项目是一个面向 Android 平台的英语背单词系统，旨在帮助用户有效背诵单词并进行记忆训练。本文档将帮助您配置开发环境并启动项目。

## 环境要求

- **操作系统**: Windows
- **开发工具**: Android Studio
- **模拟器**: MuMu 模拟器
- **Java 开发工具包 (JDK)**

## 安装步骤

### 1. 安装必要的软件

- 安装 [Android Studio](https://developer.android.com/studio)。
- 安装 [MuMu 模拟器](https://www.mumu.163.com/)（用于模拟 Android 设备）。
- 安装 JDK（Java 开发工具包）。

### 2. 配置 MuMu 模拟器

1. 打开 MuMu 模拟器，并启动一个模拟的 Android 设备。
2. 记下模拟器的端口号，通常是 `127.0.0.1:7555`，它将用于连接 adb。

### 3. 克隆本项目

```bash
git clone https://github.com/你的用户名/项目名.git

4. 打开 Android Studio 并导入项目
打开 Android Studio。
选择 Open an existing project，然后选择刚才克隆下来的项目文件夹。

5. 配置 adb 连接
打开命令提示符（CMD），进入 platform-tools 目录。假设 Android SDK 安装在 E:\Android\Sdk，运行以下命令：
E:
cd Android
cd Sdk
cd platform-tools
adb connect 127.0.0.1:7555
执行完上述命令后，如果一切正常，您应该会看到类似于 connected to 127.0.0.1:7555 的提示。

6. 在 Android Studio 中运行项目
在 Android Studio 中点击 Run 按钮，选择连接到的模拟器设备。
稍等片刻，应用将会启动并在模拟器中运行。

7.项目结构
以下是根据你提供的结构对图中文件进行的整理：

### /app
 - **/src**
   - **/com (androidTest)**
   - **/com (test)**
     - test.txt
     - zhuan4.txt
     - 六级.txt
     - 四级.txt
     - 托福.txt
   - **/java (generated)**
   - **/assets**
   - **/res (generated)**
   - **/drawable**
   - **/layout**
   - **/mipmap**
   - **/values**
 - **/res**
 - **/manifests**
 - **/java**
   - **/com**
     - **/example**
       - **/myapplication**
         - **/Activity**
         - **/adapter**
         - **/Bean**
         - **/Calendar**
         - **/http**
         - **/SQL**
         - **/Utils**
         - **/Jui**
         - **/User**
         - **/Word**
         - **/WordInfo**
         - **/WordList**
         - **/WordMsg**
         - **/DakaActivity**
         - **/BuildPath**
         - **/GetBInfoAPI**
         - **/MySQLiteOpenHelper**
         - **/MyWordHelper**
         - **/UserHelper**
 - **/Gradle Scripts**
   - **/build.gradle**
   - **/settings.gradle**
