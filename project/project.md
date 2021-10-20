#Project
1. 

先去自己找的網站上面找到圖片的網址跟複製全部的敘述

![](./1-1.png)
![](./1-2.png)
![](./1-3.png)
![](./1-4.png)
![](./1-5.png)


然後先做出一張CARD再把圖片跟敘述放進去

![](./2-1.png)

Html
```
<div class="card">
                <div class="url"
                    style="background-image: url(https://www.family.com.tw/Marketing/images/food/1006_1.jpg);">
                </div>
                <div class='article'>
                    <div class='name'>旨味柴魚干貝飯糰(區域限定)
                        <div class='price'>原價$38元</div>
                        <div class='describe'>
                            熱量163kcal / 個
                            以柴魚高湯及柴魚片拌炒杏鮑菇和干貝，鮮嫩旨味，讓人一口接著一口。
                        </div>
                    </div>
                </div>
            </div>
```

Scss
```
  .card {
    background: white;
    text-decoration: none;
    color: #444;
    display: flex;
    flex-direction: column;
    min-height: 100%;
    
    // sets up hover state
    position: relative;
    top: 0;
    
      
    
    article {
      padding: 15px;
      display: flex;
      flex-direction: column;
    }
    
    .name {
      font-size: 20px;
      margin: 0;
      color: #333;
    }

    .price{

      font-size: 15px;
      margin-top: 0.2rem;
      color: #333;
      
      }
    
    .describe{
      flex: 1;
      line-height: 1.4;
      font-size: 15px;
      color: #999;
    }
    
    .url {
      padding: 50%;
      background-size: cover;
      background-position: center center;
    }
  }
```
最後先簡單做出個Header 跟 Footer之後再看老師要求再做調整

![](./2.png)
![](./3.png)
---

2. component 還沒做但會盡快完成

---

3. 一開始忘記了要怎麼做出CARD，但是有回去看以前做過的文件，就有一點想起來了，但是要做出Header跟Footer有一點困難因為都看不懂裡面得東西是甚麼所以可能要用更多時間。