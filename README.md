# how-to-acquire-a-phd-degree

## Intro

先說在前頭，我並不是一個博士生、短期也沒有打算追求博士學位，所以這份guide只是我自己的觀察，尚未經過驗證，如果你覺得值得參考，那很好，不過不要把單純地去follow這個guide的方法，因為每個人的方法未必相同。

## What you should bear in mind

博士基本的定義就是完全精通某一個領域，所謂精通包含兩個層面:

- 通盤了解這個領域的歷史發展、重要技術、頂尖專家
- 能夠在這個領域做出貢獻(等於是推進人類"已知"的範疇)

我們平常著眼的通常在於第二點，因為他有具體的衡量指標-你是否發得出論文，而且這件事跟畢業是綁在一起的，這一點沒有不好，可惜之處在於，第一點常常被忽略。但如果我們仔細思考，會發現第一點是第二點的重要基礎。

再說得明白一點，如果你對一個領域很有興趣，你會想去大量的吸收這個領域的一切，不管是發展脈絡、現在有哪些厲害的人在這個領域貢獻(有沒有哪個人是我學習的模板)、怎麼成為他們的一員、怎麼應用自己所學幫助世界等等，如果這些問題你都非常了解、並身體力行，你在這個領域的長進一定很快。而你的好奇和熱情所帶給自己的成長恰好是是支撐你發論文的基礎。所以survey有兩種，一種是你想到某個題目之後、才去survey相關的研究(這就是典型地只在意畢業會引伸出的做法)；第二種是你平常就一直在survey，因為這個領域的高手你都有在follow，所以你知道他們在做什麼、各自擅長的方法是什麼、最新的研究到哪裡，兩者一比較高下立判。

總結的概念就是，PhD就真的只是一個學位，重點在於你在某個領域的累積夠深了，足以作出貢獻了，就會拿到的學位(這也是為什麼有些人不必念就可以拿到榮譽博士學位)。所以你應該著眼的問題永遠是-"我為什麼還不是這個領域的專家?我還有哪邊不足?"。

精神先說到這，如果有需要再補充，接下來是大致的方法。

## Preparation

這邊有一個假設:你的基礎能力足夠(透過修課等等)，至少你有能力看懂論文。

#### Literature Survey

之前修[AMMAI](http://www.csie.ntu.edu.tw/~winston/courses/ammai/)的經驗給我的啟發是，[每周看論文寫摘要](https://pojenlai.wordpress.com/category/ammai/page/2/)是可行的，而且對某個領域的領悟會進步神速。

這邊有許多東西可以學習，但我列出最重要的三點:

- 認識什麼算是好的論文(Novelty高不高、實驗設計是否合理、論文架構好不好)
- 開始構想自己的演算法(你看的論文可能都還不完美，透過反思，有些點子可能就這麼跑出來了)
- 怎麼快速跟上一個領域的最新發展

經過這邊的訓練，一方面是增進自己對此領域的了解、另一重點就是知道什麼是好的論文，這對於自己要寫出好論文有很大的幫助。

#### Implementation

只看論文通常還無法真正理解背後的細節，而且對自己做出研究的能力幫助也有限，所以我會選擇一篇state-of-the-art的論文來進行實作，但做法通常不是直接去實作這篇論文，而是先建構一個比較簡單的系統、然後一步步往state-of-the-art靠近。

有一個簡單的範例，是我之前想學雙眼立體視覺所開的[repo](https://github.com/Po-Jen/stereo_learning)。裡面就分成幾個小步驟，從使用現有的工具、自己實作簡單的演算法、到自己實作論文的演算法，這其實只是一種循序漸進的過程，而且讓你在過程中一直有成就感。

#### Helping others

除了自己持續學習之外，讓別人來幫助你學習也是很有幫助一件事。這有幾種具體的做法:

- 分享自己的理解，作成[投影片](http://www.slideshare.net/ssuser54fe9a/large-scale-object-recognition-ammai-presentation)
- 上網解答別人的疑惑，例如[Quora](http://www.quora.com/Po-Jen-Lai/answers)
- 寫[部落格](https://pojenlai.wordpress.com/2012/12/14/ros%E6%95%99%E5%AD%B8%E7%B3%BB%E5%88%97%E6%96%87%E6%95%B4%E7%90%86/)分享自己所學

這些事情在一開始可能不會有具體成效，但經過一段時間，會有人開始寄信問你問題，他們的問題都會讓你對這個領域變得更加精通，更具意義的是，你已經開始踏上成為專家的道路了(你可以把自己抽出來變成第三者，當你看到一個人可以分享高質量的投影片、可以回答別人的疑惑、可以寫部落格分享專業知識，你是不是也會覺得他應該是一個專家?)

當然，要強調的是，做這些事不代表你已經是專家，但至少你已經啟程了。

## Conducting your own research

#### Implement & Conduct Experiment

基本上，如果前一階段的survey做得好，你應該會有一堆點子；如果前一階段的實作做得好，你應該有能力實作並驗證自己的點子。

當然，這整個過程是動態而且交織的，它不是一個瀑布式的流程，你在做自己的實驗時可能會卡關、可能會需要再多看其他人的論文、可能會需要實作某些論文等等，上一個階段的方法只是讓你在開始做自己的研究時有更堅實的基礎。但如果發現不夠，那就再補起來就好。

#### Publication

要寫出一篇好的論文有兩個重點:

- 成果確實具有突破性(頂級食材是作出頂級美食的第一步)
- 論文寫法夠專業(別人才會接受你的論文)

基本上這兩點的判斷依據你應該都已經會了，因為你已經看過很多頂級的論文，所以你會知道自己跟他們還差在哪邊。

不過為了更清楚，還是應該將論文的突破性敘述清楚。基本上，一篇論文有沒有contribution有三個要素：

- 新穎性
- 進步性
- 難以想到的特性

新穎性指的是你論文中的方法是不是從來沒有人提出，雖然其中也有程度之分，不過只要沒有人用類似的方法解決你的論文想解決的問題，你的論文就具有新穎性。

進步性稍微難一些，因為你必須證明自己提出的方法達到的結果是目前已知的方法都達不到的，這一點只用說的沒有用，必須由合理而嚴謹的實驗來證明。

最難的是難以想到的特性，當一篇論文具備了讓別人覺得"天啊～他怎麼想得到要這樣做"或是"對耶～這樣做很合理，我怎麼沒想到"的感覺時，這篇論文就具有難以想到的特性，其貢獻通常也是最大的。

仔細想一下會發現，新穎性其實相對容易做到，因為把幾個演算法兜在一起可能就是新東西，但問題是，你這麼做有沒有滿足進步性或難以想到的特性。換句話說，實驗設計就是一個關鍵的因素，它其實是一件非常不容易的事情，比較一下就會發現，物體辨識之所以可以進展迅速就是因為有現成且公認的資料庫（ImageNet等等）方便做實驗，做出來辨識率比較高就有進步性，非常容易判斷跟改進。所以在發表論文上，怎麼為自己的演算法設計適合的實驗來驗證跟比較前人的方法就很重要。這件事情當然不容易，所以我們可以看看related work是怎麼驗證演算法的，學習他們設計實驗的觀念，會比較容易上手。

## Writing Dissertation

理論上，如果前面的步驟都做得很好，寫博士論文不會是問題，因為它只是一個完整的整理而已。

## 資源整理

- [research-advice](https://github.com/smilli/research-advice)
- [awesome-thesis](https://github.com/Po-Jen/awesome-thesis)
- [How to write a good CVPR submission](https://billf.mit.edu/sites/default/files/documents/cvprPapers.pdf)
- [How to Get Your CVPR Paper Rejected：Prof. Ming Hsuan Yang](https://www.youtube.com/watch?v=jp_TGMU4ASI)
  - [slides](http://faculty.ucmerced.edu/mhyang/course/eecs286-2016/lectures/How%20to%20get%20your%20CVPR%20paper%20rejected.pptx)
- [頂尖AI實驗室建立經驗分享：孫民] (https://www.youtube.com/watch?v=51Nw2eHR48c)
