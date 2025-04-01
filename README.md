<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DGBVTL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 15px;
            text-decoration: none;
            position: relative;
        }
        nav a:hover {
            background-color: #555;
        }
        .dropdown {
            display: none;
            position: absolute;
            background-color: #666;
            min-width: 160px;
            z-index: 1;
        }
        nav a:hover .dropdown {
            display: block;
        }
        .dropdown a {
            padding: 12px 16px;
            display: block;
            color: white;
        }
        .dropdown a:hover {
            background-color: #777;
        }
        .banner {
            position: relative;
            height: 300px;
            overflow: hidden;
        }
        .banner img {
            width: 100%;
            height: auto;
            display: block;
        }
        .content {
            text-align: center;
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>DGBVTL</h1>
</header>

<nav>
    <a href="#introduction">Introduction</a>
    <a href="#literature-review">Literature Review
        <div class="dropdown">
            <a href="#attitudes">Attitudes</a>
            <a href="#factors">Factors</a>
            <a href="#impacts">Impacts</a>
            <a href="#strategies">Strategies</a>
        </div>
    </a>
    <a href="#research-methodology">Research Methodology
        <div class="dropdown">
            <a href="#context">Context</a>
            <a href="#design">Design</a>
        </div>
    </a>
    <a href="#findings">Findings
        <div class="dropdown">
            <a href="#attitudes">Attitudes</a>
            <a href="#factors">Factors</a>
            <a href="#impacts">Impacts</a>
            <a href="#strategies">Strategies</a>
        </div>
    </a>
    <a href="#conclusion">Conclusion</a>
    <a href="#resources">Resources
        <div class="dropdown">
            <a href="#scholarship">Scholarship</a>
            <a href="#websites">Websites</a>
        </div>
    </a>
</nav>

<div class="banner">
    <img src="your-image-url.jpg" alt="轮播图片">
</div>

<div class="content">
    <h2>Digital Game-Based Vocabulary Teaching and Learning</h2>
    <h3>From Teachers' Perspective</h3>
</div>

<footer>
    <p>© 2025 DGBVTL. 保留所有权利.</p>
</footer>

</body>
</html>
