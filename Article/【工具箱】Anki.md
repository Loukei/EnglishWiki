---
ID: 202203302049
create_date: 2022-03-30
tags: []	
aliases:
notetype: "Article"
publish: True
---

# 【工具箱】Anki

Anki是一款基於[SRS演算法](app://obsidian.md/SRS%E6%BC%94%E7%AE%97%E6%B3%95)所設計的[記憶閃卡](app://obsidian.md/%E8%A8%98%E6%86%B6%E9%96%83%E5%8D%A1)軟體。

[Spaced repetition](app://obsidian.md/Spaced%20repetition)

## 相關工具

-   [Awesome Anki](https://github.com/tianshanghong/awesome-anki) 收集了大量好用的ANKI工具
-   [mdanki](https://github.com/ashlinchak/mdanki):Converts Markdown file(s) to the Anki cards.
-   [anki-sync-server](https://github.com/ankicommunity/anki-sync-server)
-   [Chrome 插件：下載網路字典發音 / Anki 插入發音](https://blog.chunnorris.cc/2015/10/fetch-online-dictionary-audio.html)
-   [FastWordQuery Addon For Anki](https://github.com/sth2018/FastWordQuery)一款anki插件，可以自動查詢線上字典來填寫筆記的剩餘欄位
-   [Spreadsheet Import Plus](https://ankiweb.net/shared/info/716643677)
-   [Open linked pdf, docx, epub, audio/video, etc. in external Program](https://ankiweb.net/shared/info/879473266):This add-on converts file names (and page numbers) from separate fields in your note to a clickable hyperlink that opens this file in an external application you set.
-   [Ankieasy — 自動生成單字卡的好工具](https://medium.com/@yuhsienyeh/ankieasy-%E8%87%AA%E5%8B%95%E7%94%9F%E6%88%90%E5%96%AE%E5%AD%97%E5%8D%A1%E7%9A%84%E5%A5%BD%E5%B7%A5%E5%85%B7-2-3668421f64ca)

## Anki資料結構與演算法

-   [Anki Database Structure](https://github.com/ankidroid/Anki-Android/wiki/Database-Structure)
-   [ANKI SCRIPTING: AUTOMATE YOUR FLASHCARDS](https://www.juliensobczak.com/write/2016/12/26/anki-scripting.html)一篇對ANKI做逆向工程的文章
-   [Anki 高阶教程 核心设置算法研究与详解（四）记忆库（牌组）选项之失误次数](https://zhuanlan.zhihu.com/p/91627238)
-   [What spaced repetition algorithm does Anki use?](https://faqs.ankiweb.net/what-spaced-repetition-algorithm.html)
-   [从 Anki 算法说起，探索记忆的状态空间](https://zhuanlan.zhihu.com/p/344716900)
-   [Advanced Anki deck editing made simple (ish)](https://gist.github.com/androidfred/5562973ac1ae5ce58d305a2e81c0ebd1)有關同步mysql與anki的想法
-   [Guide to Anki Intervals and Learning Steps](https://www.youtube.com/watch?v=1XaJjbCSXT0)
    
    > 介紹anki演算法的影片
    

## 文章

-   [為ANKI單字卡增加線上字典連結](https://medium.com/@irenah/anki-dictionary-link-%E5%AD%97%E5%85%B8%E9%80%A3%E7%B5%90-828d224c906c)
-   [Writing Anki Add-ons](https://addon-docs.ankiweb.net/#/): 官方有關撰寫anki外掛的文件

## 心得

-   2021-12-07_上午:10:09
    -   問題:
        -   如何讓anki與(英文)資料庫同步
        -   了解anki的SM2演算法
        -   了解Anki的資料保存結構
-   (2021-12-20_下午:02:31)
    -   Anki本身的設計是用來保存閃卡的，也就是說所有的筆記是採取表格的形式儲存，儘管它可以有多種自訂義的筆記類型，你也能在筆記裡添加筆記id的欄位，但是無法當作一個[關聯式資料庫](app://obsidian.md/%E9%97%9C%E8%81%AF%E5%BC%8F%E8%B3%87%E6%96%99%E5%BA%AB)來使用，儘管你的牌組是由[SQLite](app://obsidian.md/SQLite)保存。
    -   Anki的每個筆記可以產生多種卡片，但是一個卡片只能由一種筆記來產生。
    -   Ref:[Idea for database for anki (warning: long post)](https://www.reddit.com/r/Anki/comments/be1nod/idea_for_database_for_anki_warning_long_post/)

## Reference

-   [Anki 手冊](https://docs.ankiweb.net/intro.html)
-   [醫學生的K書法：Anki使用心得（上）-基礎概念＆模版分享](https://medium.com/@yvonnejiu/%E9%86%AB%E5%AD%B8%E7%94%9F%E7%9A%84k%E6%9B%B8%E6%B3%95-anki%E4%BD%BF%E7%94%A8%E5%BF%83%E5%BE%97-%E4%B8%8A-%E5%9F%BA%E7%A4%8E%E6%A6%82%E5%BF%B5-%E6%A8%A1%E7%89%88%E5%88%86%E4%BA%AB-329defff54cc)
-   [「Leo的Anki系列」1000种Anki模板](https://zhuanlan.zhihu.com/p/38054064)
-   [How to Design Beautiful Anki Cards](https://medshamim.com/med/how-to-design-beautiful-anki-cards)
-   [Anki Cloze Deletion Cards 怎麼在克漏字卡片上輸入答案](https://irenah.medium.com/anki-cloze-deletion-cards-%E6%80%8E%E9%BA%BC%E5%9C%A8%E5%85%8B%E6%BC%8F%E5%AD%97%E5%8D%A1%E7%89%87%E4%B8%8A%E8%BC%B8%E5%85%A5%E7%AD%94%E6%A1%88-1ce66c56a38e)
-   [[暴民隨筆] 重新思索考試中遇到的困難：Anki的記憶功能可否代替理解-02 - 巴哈姆特](https://home.gamer.com.tw/creationDetail.php?sn=4896391)
-   [Anki Scripting: Automate your flashcards](https://www.juliensobczak.com/write/2016/12/26/anki-scripting.html)
-   [Advanced Anki deck editing made simple (ish)](https://gist.github.com/androidfred/5562973ac1ae5ce58d305a2e81c0ebd1)
-   [ankidroid/Anki-Android](https://github.com/ankidroid/Anki-Android/wiki/Database-Structure)