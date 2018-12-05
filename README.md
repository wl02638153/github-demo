# github-demo workflow
A simple demo repository to show the basic Git workflow.

# Workflow
1. 先在github 上新增專案
2. git clone +address 到本機
3. 將本機專案壓縮至 git專案下 unzip 檔案位址
4. 使用 git add . 將檔案更新至 staging area
5. 使用 git commit -m "Adding start text file" 將檔案更新至 Repository area
6. git push origin master 將檔案push to github

# Git 指令

### 將專案匯入電腦
git clone +address 
git clone https://github.com/wl02638153/github-demo.git

### 查看版本
git version

### 查看狀態
git status

### 建立.txt
echo "Test Git Quick Start Demo" >> start.txt

### 查看所在目錄下檔案
ls

### 查看檔案
cat +filename
cat start.txt

### 加入更新 to Staging Area
git add start.txt

### commit to Repository
git commit -m "Adding start text file"

### 將檔案更新至github to github
git push origin master
git push -f   (更新)  

### 更改檔案名稱
mv oldname newname
mv css web-project

### 刪除檔案
rm -rf filename
rm -rf github-demo

### 解壓縮

unzip 檔案位址 
unzip D:/bootstrap-4.1.1-dist.zip






