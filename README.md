<html lang="zh-CN">
<head>
  <meta charset="utf-8">
<meta name="viewport">
 </head>
<body>
<div style="
background-color: #flflfl;
text-text-align: center;
padding: 40px;
">
<img src='https://qiniucdn.production.cjuhe.com/profile_images/1713016193945' alt="陌生人" width="200px" height="200px">
</div>
<div style="
max-width: 900px;
margin: 40px auto;
padding: 40px;
line-height: 2.7;
color:red;
">
<p>我的网站↓</p>
<a href="https://link3.cc/lgdmsr">点击链接</a>
<p>抖音视频无水印解析下载-在线解析</p>
<a href="https://www.6qq.cn/">点击链接</a>
<p>酷我音乐。</p>
<a href="https://share.feijipan.com/s/HLUfkcjd">点击链接</a>
<p>无邪软件库</p>
<a href="https://yun.139.com/link/m/i?1B5C5ziEU6IvJ=">点击链接</a>
<p>帝落破解密码:0328</p>
<a href="https://share.feijipan.com/s/3uUWEAlB">点击链接</a>
<p>下次一定</p>
  <a 
   href="https://www.iiice.cn/#/
">点击链接</a>
</div>
<div style="
background-color: #flflfl;
text-align: center;
padding: 40px;
font-size: 30px;
">
<p>我的网盘</p>
<a href="https://www.123pan.com/s/ynz5Vv-AUI3d.html">123网盘</a>
</div>
</body>
</html>

    <!-- 时间/日期 -->
    <div class="box padbox">
        <form>
            <div id="time1"></div>
    </div>
    </form>
    <!-- 一言 -->
    <div class="box padbox">
        <form>
            <div id="cardContainer"></div>
        </form>
    </div>
    <div class="mx_container padbox">
        <div class="box mx_clock_div">
            <form class="mx_clock">
                <center>
                    <div class="clock">
                        <div class="hand hours"></div>
                        <div class="hand minutes"></div>
                        <div class="hand seconds"></div>
                        <div class="point"></div>
                        <div class="marker">
                            <span class="marker__1"></span>
                            <span class="marker__2"></span>
                            <span class="marker__3"></span>
                            <span class="marker__4"></span>
                        </div>
                    </div>
                </center>
            </form>
        </div>
        <!-- 信息 -->
        <div class="box mx_information_div">
            <form class="mx_information">
                <p id="greeting"></p>
                <p id="myIP"></p>
                <p id="browser"></p>
                <p id="os"></p>
            </form>
        </div>
    </div>
    <!-- 留言板 开始 -->
    <div class="liuyan">
        <div class="container">
            <p class="box_size">留言板</p>
            <form id="messageForm" action="message/save_message.php" method="POST">
                <textarea name="message" placeholder="请输入留言内容" class="input_input"></textarea>
                <button type="submit" class="button_tijiao">提交</button>
            </form>
        </div>
    </div>
    <!-- 留言板 结束 -->
    <div class="div_box">
        <p class="canyu">我的站点</p>
        <button onclick='location.href=("替换为你的网址")' class="button">暂无网站</button>
        <button onclick='location.href=("替换为你的网址")' class="button padbox">暂无网站</button>
        <button onclick='location.href=("替换为你的网址")' class="button padbox">暂无网站</button>
        <button onclick='location.href=("替换为你的网址")' class="button padbox">暂无网站</button><br>
    </div>
    <div class="box_img">
        <img src="https://www.loliapi.com/acg/pc/" class="img_box_meiri">
    </div>
    <!-- 页脚 -->
    <div class="footer">
        <p></p>
        <p>ICP备案: 已备案</p>
        <p>公安备案: 已备案</p>
        <span id="runtime_span"></span>
    </div>
    <!--底部波浪开始-->
    <div class="wiiuii_layout">
        <svg class="editorial" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 24 150 28" preserveAspectRatio="none">
            <defs>
                <path id="gentle-wave" d="M-160 44c30 0 
    58-18 88-18s
    58 18 88 18 
    58-18 88-18 
    58 18 88 18
    v44h-352z" />
            </defs>
            <g class="parallax">
                <use xlink:href="#gentle-wave" x="50" y="0" fill="#4579e2" />
                <use xlink:href="#gentle-wave" x="50" y="3" fill="#3461c1" />
                <use xlink:href="#gentle-wave" x="50" y="6" fill="#2d55aa" />
            </g>
        </svg>
    </div>
    <!--底部波浪结束-->
    </body>

    <script>
        function show_runtime() {
            window.setTimeout("show_runtime()", 1000);
            X = new
            Date("02/22/2024 15:10:00");
            Y = new Date();
            T = (Y.getTime() - X.getTime());
            M = 24 * 60 * 60 * 1000;
            a = T / M;
            A = Math.floor(a);
            b = (a - A) * 24;
            B = Math.floor(b);
            c = (b - B) * 60;
            C = Math.floor((b - B) * 60);
            D = Math.floor((c - C) * 60);
            runtime_span.innerHTML = "本站勉强运行: " + A + "天" + B + "小时" + C + "分" + D + "秒"
        }
        show_runtime();

        function generateQuotes() {
            const apiUrl = 'https://v1.hitokoto.cn/';

            return fetch(apiUrl)
                .then(response => response.json()
