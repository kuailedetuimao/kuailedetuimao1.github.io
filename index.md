<!DOCTYPE html>
<html lang="zh - CN">

<head>
  <meta charset="UTF - 8">
  <meta name="viewport" content="width=device-width, initial - scale=1.0">
  <title>Personal Page</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box - sizing: border - box;
    }

    body {
      font - family: Arial, sans - serif;
      background: linear - gradient(to right, #9796f0, #fbc7d4);
      color: white;
    }

    .container {
      width: 80%;
      margin: 0 auto;
      padding: 50px 0;
    }

    .header {
      display: flex;
      justify - content: space - between;
      align - items: center;
      margin - bottom: 50px;
    }

    .header h1 {
      font - size: 48px;
    }

    .header p {
      font - size: 18px;
      margin - top: 10px;
    }

    .profile - img {
      width: 150px;
      height: 150px;
      border - radius: 50%;
      overflow: hidden;
    }

    .profile - img img {
      width: 100%;
      height: 100%;
      object - fit: cover;
    }

    .btn {
      display: inline - block;
      background - color: white;
      color: #9796f0;
      padding: 10px 20px;
      border - radius: 25px;
      text - decoration: none;
      margin - top: 20px;
    }

    .skills {
      text - align: center;
      margin - bottom: 50px;
    }

    .skills h2 {
      font - size: 36px;
      margin - bottom: 30px;
    }

    .skill - items {
      display: flex;
      justify - content: space - around;
    }

    .skill - item {
      width: 22%;
      background - color: rgba(255, 255, 255, 0.2);
      padding: 20px;
      border - radius: 10px;
    }

    .skill - item i {
      font - size: 36px;
      margin - bottom: 20px;
      display: block;
    }

    .skill - item h3 {
      font - size: 24px;
      margin - bottom: 10px;
    }

    .skill - item p {
      font - size: 14px;
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font - awesome/5.15.4/css/all.min.css">
</head>

<body>
  <div class="container">
    <div class="header">
      <div>
        <h1>lettery</h1>
        <p>Idealist & AI Superindividual</p>
        <p>做一个真诚、靠谱、可爱的人</p>
        <a href="#" class="btn">Get in Touch</a>
      </div>
      <div class="profile - img">
        <img src="your - image - url.jpg" alt="Profile Image"> 
      </div>
    </div>
    <div class="skills">
      <h2>My Skills</h2>
      <div class="skill - items">
        <div class="skill - item">
          <i class="fas fa - code"></i> 
          <h3>Web Development</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="skill - item">
          <i class="fas fa - paint - brush"></i> 
          <h3>UI/UX Design</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="skill - item">
          <i class="fas fa - globe"></i> 
          <h3>SEO Optimization</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        <div class="skill - item">
          <i class="fas fa - bolt"></i> 
          <h3>Performance Tuning</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      </div>
    </div>
  </div>
</body>

</html>
