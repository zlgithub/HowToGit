# HowToGit
學習如何使用git與github。
## 下載git
![image](https://github.com/zlgithub/HowToGit/blob/master/img/git.png)  
[連結](https://git-scm.com/ "https://git-scm.com/")  
下載時注意自己要不要git的桌面連結與右鍵功能。  
在 *Git Bash* 中使用指令   
## git的常用指令(變動值以中文顯示) 
### git設定
查看設定內容
```
git config --list
```
設定名稱
```
git config --global user.name 名稱
```
設定email
```
git config --global user.email 信箱
```
查看log
```
git log
```
### repo設定與建立
開啟需要git的位置:
```
cd 資料夾位置
```
建立repo，產生 *.git* 檔案(此為隱藏的項目):
```
git init
```
從網站複製
```
git clone 網址
```
### 使用git備份等功能
把所有檔案改動加入，準備commit:
```
git add -A
```
簡易commit(備份):
```
git commit -m "說明這次改動"
```
查看目前狀態(按 **q** 離開):
```
git status
```
把檔案改動回朔到上次commit:
```
git checkout 檔案名稱
```
把所有檔案改動回朔到上次commit:
```
git reset --hard
```
### 分支
查看branch(有 \* 即為目前所在分支):
```
git branch
```
內建的查看branch介面
```
gitk --all &
```
建立新分支
```
git branch 新分支名稱
```
轉換分支
```
git checkout 分支名稱
```
合併分支
```
git merge 分支名稱
```
