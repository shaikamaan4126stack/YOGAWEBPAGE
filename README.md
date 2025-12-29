<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PureYoga</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: Arial, sans-serif;
    background: linear-gradient(to bottom right, red, yellow, green);
}

/* HEADER */
.header{
    width:100%;
    height:70px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:0 20px;
    flex-wrap:wrap;
}

.pure-yoga{
    color:white;
    font-size:30px;
}

.links{
    display:flex;
    gap:15px;
    flex-wrap:wrap;
}

.menu-links{
    text-decoration:none;
    background:wheat;
    color:black;
    padding:6px 15px;
    border-radius:6px;
    font-size:16px;
}

/* HERO SECTION */
.section1{
    width:100%;
    min-height:70vh;
    background:url("kid's yoga.png") center/cover no-repeat;
    display:flex;
    justify-content:center;
    align-items:center;
}

.text{
    text-align:center;
    color:white;
    padding:20px;
}

.text h1{
    font-size:clamp(36px, 6vw, 60px);
    text-shadow:4px 4px 6px red;
}

.text p{
    font-size:clamp(16px, 3vw, 22px);
}

/* TITLES */
.benefits-title,
.classes-title,
.trainers-title{
    text-align:center;
    margin:40px 0 20px;
    font-size:28px;
    font-weight:bold;
}

.benefits-title{ color:yellow; }
.classes-title{ color:#d2691e; }
.trainers-title{ color:rgb(255,200,0); }

/* BENEFITS */
.benefits-section{
    display:flex;
    flex-wrap:wrap;
    gap:20px;
    justify-content:center;
    padding:20px;
}

.benefit-card{
    width:300px;
    background:white;
    border-radius:12px;
    padding:20px;
    box-shadow:2px 2px 10px rgba(0,0,0,0.2);
}

.benefit-title{
    text-align:center;
    color:#d48806;
}

.benefit-text{
    text-align:center;
    margin-top:10px;
}

/* CLASSES */
.classes-section{
    display:flex;
    flex-wrap:wrap;
    gap:20px;
    justify-content:center;
    padding:20px;
}

.class-card{
    width:280px;
    background:rgba(255,255,255,0.85);
    border-radius:15px;
    overflow:hidden;
    box-shadow:3px 3px 10px rgba(0,0,0,0.2);
}

.class-card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.class-name{
    padding:10px;
    font-size:18px;
    color:#e05a4f;
}

.class-desc{
    padding:0 10px 15px;
    font-size:14px;
}

/* TRAINERS */
.trainers-section{
    display:flex;
    flex-wrap:wrap;
    gap:20px;
    justify-content:center;
    padding:20px;
}

.trainer-card{
    width:280px;
    background:rgba(255,255,255,0.85);
    border-radius:15px;
    overflow:hidden;
    box-shadow:3px 3px 10px rgba(0,0,0,0.25);
}

.trainer-card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.trainer-name{
    padding:10px;
    color:rgb(255,140,80);
}

.trainer-role{
    padding:0 10px 15px;
    font-size:14px;
}

/* FOOTER */
.footer{
    background:darkcyan;
    height:50px;
    display:flex;
    justify-content:center;
    align-items:center;
    margin-top:40px;
}

.footer-para{
    font-size:16px;
}

/* MEDIA QUERIES */
@media(max-width:768px){
    .header{
        flex-direction:column;
        height:auto;
        padding:15px;
    }

    .links{
        justify-content:center;
    }
}

@media(max-width:480px){
    .menu-links{
        font-size:14px;
        padding:5px 10px;
    }
}
</style>
</head>

<body>

<header class="header">
    <h1 class="pure-yoga">PureYoga</h1>
    <div class="links">
        <a class="menu-links" href="#section1">Home</a>
        <a class="menu-links" href="#benefits-title">Benefits</a>
        <a class="menu-links" href="#classes-title">Classes</a>
        <a class="menu-links" href="#trainers-title">Trainers</a>
    </div>
</header>

<section class="section1">
    <div class="text">
        <h1>Find Your Balance</h1>
        <p>Fitness • Flexibility • Wellness</p>
    </div>
</section>

<h2 class="benefits-title">Yoga Benefits</h2>
<section class="benefits-section">
    <div class="benefit-card">
        <h3 class="benefit-title">Stress Relief</h3>
        <p class="benefit-text">Calm your mind and reduce anxiety.</p>
    </div>
    <div class="benefit-card">
        <h3 class="benefit-title">Flexibility</h3>
        <p class="benefit-text">Improve motion & body balance.</p>
    </div>
    <div class="benefit-card">
        <h3 class="benefit-title">Strength</h3>
        <p class="benefit-text">Build body strength naturally.</p>
    </div>
</section>

<h2 class="classes-title">Our Classes</h2>
<section class="classes-section">
    <div class="class-card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ_M7xeouaXzWPlnhyG0mRuLA_b_uCLHEn-Xw&s">
        <h3 class="class-name">Hatha Yoga</h3>
        <p class="class-desc">Balance & calm practice.</p>
    </div>
    <div class="class-card">
        <img src="https://i.ytimg.com/vi/1j9fh5hnXXI/maxresdefault.jpg">
        <h3 class="class-name">Meditation</h3>
        <p class="class-desc">Mind relaxation.</p>
    </div>
    <div class="class-card">
        <img src="https://img.freepik.com/free-photo/full-shot-kid-meditating-mat_23-2148872502.jpg">
        <h3 class="class-name">Power Yoga</h3>
        <p class="class-desc">Fast & strong workout.</p>
    </div>
</section>

<h2 class="trainers-title">Our Trainers</h2>
<section class="trainers-section">
    <div class="trainer-card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSN27MgoNm9moyn0kdFuq82J4oP8PN6-D8uWA&s">
        <h3 class="trainer-name">Abc</h3>
        <p class="trainer-role">Power Yoga Instructor</p>
    </div>
    <div class="trainer-card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQi6QR58o2uPrXM7KWoJljXypblnG0GOnNSZA&s">
        <h3 class="trainer-name">Def</h3>
        <p class="trainer-role">Meditation Expert</p>
    </div>
    <div class="trainer-card">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR9fIYuC8BV1VSUodhq0lCTMYwugXoLhIwlCg&s">
        <h3 class="trainer-name">Ghi</h3>
        <p class="trainer-role">Flexibility Trainer</p>
    </div>
</section>

<footer class="footer">
    <p class="footer-para">© 2025 PureYoga — Fitness & Wellness</p>
</footer>

</body>
</html>
