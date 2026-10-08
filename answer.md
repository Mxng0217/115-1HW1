# 第1次作業題目-隨堂-HW1
>
>學號：113111117
><br />
>姓名：官益正
><br />
>作業撰寫時間：170分鐘
><br />
>最後撰寫文件日期：2026/10/08
>

1. 請參閱Topic 0的git clone 該⾴(P. 12)中，看完fork內容後，請完成⽼師倉庫的fork，截圖並說明如何完成。

Ans:![alt text](image.png)
點選fork後按cteate。

2. 請研究markdown基本寫作⽅法，並請對常⾒語法進⾏介紹後，請給個例⼦。

Ans:清單 (Lists)
• 無序清單：使用星號 *、加號 + 或減號 - 開頭，後方空一格。
• 有序清單：使用數字加上英文句點 1.、2. 開頭，後方空一格。
• 任務清單 (Todo)：使用 - [ ] 代表未勾選，- [x] 代表已勾選。

粗體

**bold**

3. 請在你的專案中完成下⾯的操作，最後把結果推上
 GitHub
，並截圖
 git graph 
說
明你的做法。步驟如下：
i
ii
建⽴新分⽀
從
main 
分⽀建⽴⼀條新分⽀，名稱⾃訂（例如
 feature
你的學號），並切換
到這條新分⽀。
在新分⽀上新增檔案並寫⼊內容
在新分⽀上新增⼀個檔案（例如
 hello.txt
），內容⾄少包含：
1
第1次作業題⽬-作業-HW1
Hello Git!
姓名：（你的姓名）
學號：（你的學號）
iii
提交（
commit
）
把新增的檔案加⼊暫存區，再進⾏
 commit
，
commit 
訊息要能說明這次做了
什麼（例如「新增
 hello.txt
」）。
iv
合併（
merge
）
切回
 main 
分⽀，把剛剛的新分⽀合併進
 main


Ans:![alt text](image-1.png)
1. 建立並切換新分支：執行 git checkout -b feature-113111117 從 main 分支出發建立獨立開發線。
2. 撰寫與提交內容：在新分支中建立 hello.txt，寫入作業規定的時間、姓名與學號，並使用 git add hello.txt 與 git commit 完成本地儲存。
3. 合併分支：切回 main 分支後，執行 git merge feature-113111117，透過 Fast-forward (快進模式) 將新分支的成果完美合併進 main。
4. 推上 GitHub 遠端：依序執行 git push origin main 與 git push origin feature-113111117，將本地的所有分支與提交歷史完整同步至 GitHub 遠端倉庫。

4. 請於「點我」找到⾃⼰的名字後，並於對應的「github帳號位址[請撰寫]」欄位中，貼上網址，其網址規則要貼的內容為：

Ans:![alt text](image-2.png)

## 其他

心得：那個指令真的有夠繞來繞去的很討厭，我一開始為是雲端，跟雲端差很多，而且比雲端還複雜，一整個很難，但好在有同學會做。

