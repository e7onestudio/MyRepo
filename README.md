# 【MyRepo】
My First Repository
http://e7oneStudio.com

<img src="IMGobj_FuLuMonkey_20160215_c1-900.jpg" width="800">

---

# 【GitHub】

## WebSite
- https://github.com/
- https://github.com/samofor/

## About
- 線上資訊文件＂版本＂控管雲端網站
- 用＂儲存庫＂Repositoies名稱作專題式管理

# 【資料版本】

## 版本名稱
- 主版本名稱：統一為＂main＂；初始版本者
- 分支Branch版本名稱：可自定名稱；內容可從其它版本複製，或重新增添

## 版本的呈現
- 線上版本：非Merge版本；各版本累積存在；可切換版本瀏覽、取用資料
- 本地端版：為Merge版本，最終樣貌版本

# 【空間檔案限制】

## 空間限制
- 每個帳號的空間存量，限1GB
## 檔案限制
- 每個檔案大小限100MB
- 超過檔案大小或空間不足時，建議採用第三方的線上雲端空間作存放

# 【線上文件】
- 支援採用Markdown語法的文件資料，副檔名為MD者
- 文件目錄(Branch)，可被整批打包下載
- 文件權限～公開(Public)與私人(Private)

# 【資料異動】

## 資料異動
- Commit指令動作(按鈕)；所在裝置執行更新處理
## 資料推送
- Push上傳|Pull下載；接棒前述Commit指令動作後


# 【工具軟體】

## 桌面管理【GitHub Desktop】
- https://desktop.github.com/download/
- 屬獨立應用軟體介面
- 屬手動更新管理之工具

## 桌面管理【TortoiseGit】
- https://tortoisegit.org/download/
- 整合於檔案總管介面選項中；
- 屬手動更新管理之工具

# 【本地端版路徑】
- 預設：C:\Users\UserName\Documents\GitHub\Repositoies名稱
- GitHub Desktop：限特定指定路徑目錄
- TortoiseGit：限特定指定路徑目錄下，用檔案總管介面作操作


# 【常用指令】

# 指令0【Special Skill】
### 建立.gitignore檔 
- 把需要不被追蹤的檔名列於.gitignore檔中 
- 但.gitignore檔會被上傳露餡？
- 只要把 .gitignore 字樣也寫進 .gitignore 裡面，這個檔案也會被忽略

# 指令01【基本環境】
### git --version
### git config --list
### q .... 離開git環境
### git config user.name
### git config user.email
### git config --global user.name "samofor"
### git config --global user.email "smf1027@ms1.hinet.net"

# 指令02【建置遠端環境】
### gh repo create my-new-repo --public

git remote add origin https://github.com/your-username/my-new-repo.git
git push -u origin main


# 指令03【建置本地端環境】
### git init 
- 1.初始化所在工作資料夾，會產生".git"隱藏資料夾
- 依CMD所在目錄下的.git檔決定是否可Remote上傳

### git remote add origin MyGitHubURL 
- 2.初始化遠端掛勾用
- git remote add origin https://github.com/samofor/mystudy

### git clone MyGitHubURL 
- 3.將遠端資料複製一份到本地端
- git clone https://github.com/samofor/mystudy


# 指令04【準備環境】

### git branch -a 
- 列表查詢目前有哪些branch；會顯示目前是指定哪個branch為工作用

### git branch -M MyBranch 
- 指定MyBranch為工作用


# 指令05【更新環境】

### git status
- 查詢git環境

### git pull
- 線上的Commit會打包所有異動者，可一次全下載
- 線上端與本地端，資料更新順序要留意，不要互卡；
    - 本地端要更新資料前，最好先執行git pull動作。
    - 線上端更新資料後，本地端要跟著執行git pull動作。

# 指令06【更新準備】

### git add .
- 一次打包所有異動者

### git add MyFile
- git add .\MyFile.md

### git commit -m "MyNoteInfo" 
- 準備好更新訊息與commit預備動作

### git push -u origin MyBranch 
- 開始推播Push上傳更新，一定要指定MyBranch 


# 指令07【合併Branch】
