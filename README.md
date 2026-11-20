<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8"> 
    <title>我的個人介紹首頁</title> 
    <style>
        /* 任務 1：修改整個網頁 */
        body {
            color: #2c3e50;
            background-color: #eef5f9;
        }

        /* 任務 2：修改主標題 */
        h1 {
            color: #154360;
            font-size: 36px;
            font-weight: bold;
            text-align: center;
        }

        /* 任務 3：使用 class */
        .notice {
            color: #1f618d;
            background-color: #d6eaf8;
            font-weight: bold;
        }

        /* 任務 4：自由增加一項 CSS */
        p {
            line-height: 1.8;
        }

        ul {
            list-style-type: square;
        }

        nav a {
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>我的個人介紹</h1> 
        <nav>
            <a href="index.html">首頁</a> |
            <a href="course.html">課程介紹頁面</a> <!-- 延伸練習：互相連結 -->
        </nav>
    </header>
	
    <main>
        <div>
            <h2>自我介紹</h2> 
            <p>
                大家好，我是海事資訊系的。我的興趣是看小說尤其是科幻類型的，平時也會打打遊戲。之所以會讀這科系，是因為分數剛好到這，也<strong>對海洋有點興趣而且高中是電子科也算有點基礎</strong>，<span class="notice">請大家再多多指教</span>。
            </p>
        </div>
        <div>
            <h2>興趣與目標</h2> 
            <h3>興趣</h3>
            <ul>
                <li>閱讀科幻小說</li>
                <li>聆聽各種類型的音樂</li>
                <li>玩電腦遊戲</li>
            </ul>
            <h3>本學期想完成的三件事情</h3>
            <ol>
                <li>拿到全部學分</li>
                <li>看完一套小說</li>
                <li>存一些錢</li>
            </ol>
        </div>
        <div>
            <h2>聯絡資訊</h2>
            <p>
                國立高雄科技大學 旗津校區<br>
                地址：高雄市旗津區慈愛里中洲三路482號<br>
                電話：0928281101
            </p>
            <p>
                相關連結：
                <a href="https://www.google.com" target="_blank">造訪外部搜尋引擎網站</a> | 
                <a href="mailto:example@student.edu.tw">傳送 Email 給我</a>
            </p>
        </div>
    </main>
    <footer>
        <p>姓名：林思佑 | 學號：C114181133 | 聯絡方式：0928281101 </p>
    </footer>

</body>
</html>
