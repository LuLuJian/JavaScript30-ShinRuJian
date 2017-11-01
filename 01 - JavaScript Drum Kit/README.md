## Drum kit
### 效果介紹 
 
點擊鍵盤上的字母，發出不同聲音，被點擊的按鈕呈現動畫。

### 重點語法

1.透過鍵盤監聽事件addEventListener函式，使用querySelector方法來取得DOM中的.data-key及audio的編號。

- currentTime設置時間。 

2.鍵盤監聽事件中當按下鍵盤audio標籤使用paly()來播放音樂，並加入點擊的動畫樣式 classList.add 。


3.避免點擊後樣式一直存在，按鈕使用 forEach 跑transitionend監聽事件的function，來將被點擊的動畫做classList.remove移除。

[監聽事件](http://www.jstips.co/zh_tw/javascript/DOM-event-listening-made-easy/)

[transitionend監聽事件](http://www.runoob.com/jsref/event-transitionend.html)

[currentTime](https://www.w3schools.com/tags/av_prop_currenttime.asp)

### 長知識



