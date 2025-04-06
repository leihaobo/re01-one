<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>欢迎来到我的个人网站</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html" class="active">首页</a></li>
                <li><a href="about.html">关于我</a></li>
                <li><a href="projects.html">项目展示</a></li>
                <li><a href="contact.html">联系我</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="hero">
            <h1>你好，我是环科2403班雷淏博<span id="typing-text"></span></h1>
            <p>欢迎来到我的个人网站</p>
            <button id="cta-button">了解更多</button>
        </section>
        
        <section class="highlights">
            <div class="card" onmouseover="hoverCard(this)" onmouseout="unhoverCard(this)">
                <h3>我的技能</h3>
                <p>做饭等</p>
            </div>
            <div class="card" onmouseover="hoverCard(this)" onmouseout="unhoverCard(this)">
                <h3>我的教育</h3>
                <p>华中科技大学 环境科学与工程专业</p>
            </div>
            <div class="card" onmouseover="hoverCard(this)" onmouseout="unhoverCard(this)">
                <h3>我的兴趣</h3>
                <p>看小说，羽毛球</p>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 我的个人网站.</p>
    </footer>
    
    <script src="js/scripts.js"></script>
</body>
</html>
