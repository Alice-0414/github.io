[index.html.txt](https://github.com/user-attachments/files/19621849/index.html.txt)# github.io# 在项目文件夹打开终端
git init
git add .
git commit -m "首次提交"
git branch -M main
git remote add origin [Uploading <!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人主页 | Your Name</title>
    <style>
        /* 基础样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, sans-serif;
        }

        body {
            background: #f8f9fa;
            color: #212529;
            line-height: 1.6;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem;
        }

        .container {
            max-width: 800px;
            width: 100%;
            text-align: center;
        }

        /* 头部内容 */
        .header {
            margin-bottom: 3rem;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #2d3436;
        }

        .bio {
            font-size: 1.1rem;
            color: #636e72;
            margin-bottom: 2rem;
        }

        /* 链接按钮 */
        .links {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            max-width: 300px;
            margin: 0 auto;
        }

        .link-button {
            padding: 1rem 2rem;
            background: #ffffff;
            border: 2px solid #ced4da;
            border-radius: 8px;
            text-decoration: none;
            color: #2d3436;
            font-weight: 500;
            transition: all 0.2s ease;
        }

        .link-button:hover {
            border-color: #74b9ff;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(116, 185, 255, 0.1);
        }

        /* 页脚 */
        footer {
            margin-top: auto;
            padding: 2rem 0;
            color: #636e72;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>你好，我是[阿漓/棍棍]</h1>
            <p class="bio">写手 | COSER | 创作者</p>
        </header>

        <div class="links">
            <a href="[GitHub链接]" class="link-button" target="_blank">GitHub</a>
            <a href="[https://weibo.com/u/6627325732]" class="link-button" target="_blank">棍的大眼</a>
            <a href="[作品集链接]" class="link-button" target="_blank">项目作品</a>
            <a href="mailto:[alice322680@gmail.com]" class="link-button">联系我</a>
        </div>

        <footer>
            <p>© 2023 [棍妳妹的幸福人生] - 因热爱而制作</p>
        </footer>
    </div>
</body>
</html>index.html.txt…]()

git push -u origin main
