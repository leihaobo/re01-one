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
            <h1>你好，我是<span id="typing-text"></span></h1>
            <p>欢迎来到我的个人网站</p>
            <button id="cta-button">了解更多</button>
        </section>
        
        <section class="highlights">
            <div class="card" onmouseover="hoverCard(this)" onmouseout="unhoverCard(this)">
                <h3>我的技能</h3>
                <p>HTML, CSS, JavaScript, PHP, MySQL</p>
            </div>
            <div class="card" onmouseover="hoverCard(this)" onmouseout="unhoverCard(this)">
                <h3>我的教育</h3>
                <p>XX大学 计算机科学与技术专业</p>
            </div>
            <div class="card" onmouseover="hoverCard(this)" onmouseout="unhoverCard(this)">
                <h3>我的兴趣</h3>
                <p>编程、摄影、旅行、阅读</p>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 我的个人网站. 保留所有权利.</p>
    </footer>
    
    <script src="js/scripts.js"></script>
</body>
</html>
