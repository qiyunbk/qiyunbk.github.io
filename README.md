<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>淇云博客安全中心</title>
    <style>
        /* 基础样式 */
        html, body {
            height: 100%;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f4f8;
            color: #333;
        }

        body {
            display: flex;
            flex-direction: column;
        }

        /* 顶部Header */
        .header {
            background-color: white;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .logo {
            display: inline-block;
            width: 200px;
            height: 50px;
            background: url('https://tc.pengqi.club/img/2023/01/17/CnoO.png') no-repeat center;
            background-size: contain;
        }

        /* 中间内容区域 */
        .content {
            flex: 1;
            min-height: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: linear-gradient(to bottom, #5b9bd5, #2f5bb7);
            color: white;
            padding: 0 20px;
            text-align: center;
        }

        .content h2 {
            margin: 0 0 45px;
            font-size: 25px;
        }

        .warning-box {
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
            padding: 15px 20px;
            margin: 15px auto;
            max-width: 90%;
            font-size: 30px;
            line-height: 1.5;
        }

        .warning-text {
            color: red;
            font-weight: bold;
        }

        .content p {
            margin-top: 45px;
            font-size: 25px;
        }

        /* 底部Footer */
        .footer {
            background-color: white;
            text-align: center;
            padding: 10px 0 20px;
            font-size: 14px;
            color: #666;
            margin-top: auto;
        }

        .footer hr {
            margin: 10px 0;
            border: none;
            height: 1px;
            background-color: #ddd;
        }

        /* 响应式适配 */
        @media (max-width: 600px) {
            .warning-box {
                max-width: 95%;
                padding: 10px 15px;
                font-size: 25px;
            }
            .content {
                padding: 10px 15px;
            }
        }
    </style>
</head>
<body>
    <!-- 顶部区域 -->
    <div class="header">
        <div class="logo"></div>
    </div>

    <!-- 主体内容 -->
    <div class="content">
        <h2>淇云博客安全中心温馨提示您</h2>
        <div class="warning-box">
            您正在通过<span class="warning-text">非中国大陆境内IP地址</span>访问本站，请立即停止访问。
        </div>
        <p>请关闭网络代理后，再次对本站发起网络请求！</p>
    </div>

    <!-- 底部区域 -->
    <div class="footer">
        淇云博客安全中心
        <hr>
        Copyright © 2025 淇云博客 版权所有<br>
        蜀ICP备17017481号-1. 川公网安备51010002000024号.
    </div>
</body>
</html>
