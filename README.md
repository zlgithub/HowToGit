# HowToGit
學習如何使用git與github。

## 注意!整篇文章正在製作中  

## 下載git
![image](https://github.com/zlgithub/HowToGit/blob/master/img/git.png)  
[連結](https://git-scm.com/ "https://git-scm.com/")  
下載時注意自己要不要git的桌面連結與右鍵功能。  
## 把git當作備份使用的常用指令(變動值以中文顯示) 
###git設定等
開啟需要git的位置:
```
cd 資料夾位置
```
建立 *.git* 檔案(此為隱藏的項目):
```
git init
```
內建的查看branch介面
```
gitk --all &
```
查看設定內容
```
git config --list
```
### 使用git
把所有檔案加入準備commit:
```
git add -A
```
簡易commit(備份):
```
git commit -m "說明這次改動"
```
查看目前狀態:
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
