前言

2016 年底, 看到 PTT Programming 版的一則[題目](https://www.ptt.cc/bbs/Programming/M.1478792208.A.EFC.html):

     作者  mikemagic88 (Mikemagic88)                            看板  Programming
     標題  [問題] 1-9位數不重複印出來
     時間  Thu Nov 10 23:36:45 2016
    ───────────────────────────────────────

    使用者輸入1  印1-9

    使用者輸入2  印1-98  (11, 22, 33等重複的不印)

    使用者輸入3  印1-987 (121, 988, 667等有重複的不印)

一時版上出現了用各種語言寫的解答, 簡直就像 [Rosseta Code](https://rosettacode.org/wiki/Category:J) 一樣.

我也忍不住趁機學了一下觀望已久但一直沒有動手的 J 語言. 幾天後勉強拼出個[版本](https://www.ptt.cc/bbs/Programming/M.1482166817.A.DC1.html):

    (*/@~:@":"0#[)}.i.10^3
    
這篇便是這段時間學習 J 的一些心得記錄.


歷史

J(1990) / K(1993) / Q(2003) 這幾個語言都是 APL(1964) 的後代, 也影響了一點 MATLAB / Wolfram Language / Go.

APL 的作者 Iverson 也因為開創了這個流派而得了 1979 年的 Turing Award.

APL 本來是 Iverson 1957 年創造來描寫數學運算的一套 notation (所以有很多符號). 1962 在 IBM 被拿來描述 [System/360](https://en.wikipedia.org/wiki/IBM_System/360) 硬體的行為, 後來這套 notation 才被實作在硬體上 (這個順序挺特別的).

APL 需要特別的鍵盤/印表機支援:
!(keyboard)[https://upload.wikimedia.org/wikipedia/commons/9/9f/APL-keybd2.svg]

又讓我驚訝的是: 那個年代的 programmer 居然是對著 printer 而不是對著 monitor 工作的!
https://youtu.be/_DTpQ4Kk2wA?t=5m25s

這系列的語言[還被用在](https://en.wikipedia.org/wiki/APL_(programming_language)#Use) 數學/金融等領域.

https://www.youtube.com/watch?v=a9xAKttWgP4
