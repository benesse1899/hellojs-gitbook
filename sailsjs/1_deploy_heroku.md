how to deploy to heroku
https://www.heroku.com/

(申請github帳號)
https://github.com/

進入 koding.com
https://koding.com

```
sudo npm i sails -g
sails new firstApp
cd firstApp
```

https://github.com/new

create a new repository, 輸入 firstApp

回到 KODING.COM 輸入

``` 
git init

底下這段是從 github respository 裡面複製出來的指令
git remote add origin https://github.com/xxxxx/firstApp.git
```

push to github

回到 KODING.COM 輸入
```
以下這兩行只有第一次需要設定
git config --global user.email "--- 你自己的 EMAIL"
git config --global user.name "--- github username"

git add .
git commit -m 'update files'
git push origin master
 接下來就要輸入 GITHUB 帳號密碼
```

切換到 HEROKU APP 上面進行更新
建立一個 HEROKU APP (新增按鈕為畫面右上角)

按下中間 github 帳號進行設定 (connect) github
設定 github respository ，目前設定範例為 firstApp
設定完成之後，畫面拉到最下方，按下  DEPLOY BRANCH 進行程式更新到 HEROKU


繼續更新程式

回到 KODING.COM 修改檔案
修改程式之後就可以輸入以下指令

git add .
git commit -m 'update files'
git push origin master



2015/12/08 

希望同學能夠將以下資料先看過 

教學影片 

https://www.youtube.com/playlist?list=PLf8i4fc0zJBzLhOe6FwHpGhBDgqwInJWZ 

教學文件 

http://irlnathan.github.io/sailscasts/blog/archives/ 

如果同學有任何不清之處歡迎他們來信，或者 

https://www.facebook.com/clonncd 

facebook 與我聯絡， 