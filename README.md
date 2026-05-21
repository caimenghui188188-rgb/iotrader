[index.html](https://github.com/user-attachments/files/28118852/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IOTrader | IOI 代币官网</title>
    <meta name="description" content="IOTrader 预测市场 + 杠杆交易平台 | IOI 代币合约地址 0xba2ae424d960c26247dd6c32edc70b295c744c43 | 2026年5月23日18:00北京时间上市">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Microsoft YaHei', Arial, sans-serif;
            background: #0a0a0f;
            color: #e0e0e0;
        }
        .hero {
            background: linear-gradient(135deg, #0f1629 0%, #1a0f2e 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
        }
        h1 {
            font-size: 4.5rem;
            background: linear-gradient(90deg, #00ff9d, #00ccff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .contract {
            background: rgba(0,255,157,0.08);
            border: 2px solid #00ff9d;
            padding: 1.5rem;
            border-radius: 16px;
            font-family: monospace;
            margin: 2rem 0;
        }
        .btn {
            padding: 16px 40px;
            font-size: 1.2rem;
            border-radius: 50px;
            text-decoration: none;
            margin: 10px 10px 10px 0;
            font-weight: bold;
        }
        .btn-primary {
            background: linear-gradient(45deg, #00ff9d, #00ccff);
            color: #000;
        }
    </style>
</head>
<body>
    <section class="hero">
        <div style="max-width:1200px; margin:0 auto; padding:0 20px; text-align:center;">
            <h1>IOTrader</h1>
            <p style="font-size:1.8rem; margin:20px 0;">预测市场 × 杠杆交易</p>
            
            <div class="contract">
                <strong>IOI 代币合约地址：</strong><br>
                <span style="color:#00ff9d; font-size:1.3rem;">0xba2ae424d960c26247dd6c32edc70b295c744c43</span>
            </div>

            <p style="font-size:1.5rem; margin:20px 0;">
                <strong>2026年5月23日 北京时间 18:00 正式上市</strong>
            </p>

            <div>
                <a href="#" onclick="copyAddress()" class="btn btn-primary">复制合约地址</a>
                <a href="#" onclick="alert('请打开 TP 钱包，切换到对应链后添加合约地址购买')" class="btn" style="background:#333;color:white;">TP钱包购买</a>
            </div>
        </div>
    </section>

    <script>
        function copyAddress() {
            navigator.clipboard.writeText("0xba2ae424d960c26247dd6c32edc70b295c744c43");
            alert("✅ 合约地址已复制！");
        }
    </script>
</body>
</html>
