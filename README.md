- 👋 Hi, I’m @duckswift
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
duckswift/duckswift is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        h1, p {
            text-align: center;
        }
    </style>
</head>
<body>
    
    <p>就知道你有这个大愿望</p>
</body>
</html>
"""

# 将HTML内容写入文件
with open('write1.html', 'w', encoding='utf-8') as f:
    f.write(html_content)
