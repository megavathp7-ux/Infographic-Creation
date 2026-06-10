<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Infographic Design</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f5f7fa;
    padding:30px;
}

.container{
    max-width:1000px;
    margin:auto;
}

.header{
    text-align:center;
    margin-bottom:40px;
}

.header h1{
    color:#2c3e50;
    font-size:42px;
}

.header p{
    color:#666;
    margin-top:10px;
}

.infographic{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    text-align:center;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.icon{
    font-size:50px;
    margin-bottom:15px;
}

.card h2{
    color:#34495e;
    margin-bottom:10px;
}

.card p{
    color:#777;
    line-height:1.5;
}

.stat{
    font-size:40px;
    color:#3498db;
    font-weight:bold;
    margin:10px 0;
}
</style>
</head>
<body>

<div class="container">

    <div class="header">
        <h1>Digital Marketing Infographic</h1>
        <p>Key Statistics and Insights for 2026</p>
    </div>

    <div class="infographic">

        <div class="card">
            <div class="icon">📈</div>
            <div class="stat">85%</div>
            <h2>Growth Rate</h2>
            <p>Businesses increased online engagement through digital campaigns.</p>
        </div>

        <div class="card">
            <div class="icon">📱</div>
            <div class="stat">70%</div>
            <h2>Mobile Users</h2>
            <p>Most website traffic now comes from smartphones and tablets.</p>
        </div>

        <div class="card">
            <div class="icon">🎯</div>
            <div class="stat">92%</div>
            <h2>Target Reach</h2>
            <p>Personalized marketing improves customer engagement significantly.</p>
        </div>

        <div class="card">
            <div class="icon">💰</div>
            <div class="stat">4.5x</div>
            <h2>ROI</h2>
            <p>Average return on investment from successful digital campaigns.</p>
        </div>

    </div>

</div>

</body>
</html>
