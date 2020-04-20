<!-- <h1 align="center">
<img width="1792" alt="Cover" src="https://user-images.githubusercontent.com/4281887/76942900-0c5da880-6931-11ea-98ad-67aa53604024.png">
</h1> -->

ในคอร์สนี้ผู้เรียนจะได้ทำ 21 โปรเจคที่ครอบคลุมเนื้อหาในหลากหลายด้านของภาษาจาวาสคริปต์ โดยโปรเจคทั้งหมดมีดังต่อไปนี้

1. Falling Snow

   - IIFE เพื่อสร้าง Lexical scope ป้องกันการเกิด pullution ใน Global variable

   ```javascript
   (() => {
     // เริ่มเขียนโค้ด
   })();
   ```

   - Canvas

   ```javascript
   const canvas = document.getElementById('falling-snow-canvas'); //อ้างถึง canvas ใน HTML
   canvas.width = window.innerWidth; // กำหนดขนาดความกว้าง canvas ให้เท่ากับขนาด window
   canvas.height = window.innerHeight; // กำหนดขนาดความสูง canvas ให้เท่ากับขนาด window
   canvasContext = canvas.getContext('2d'); // อ้างถึง Canvas Context แบบ 2d

   // วาดวงกลม
   canvasContext.beginPath(); // เริ่มวาด
   canvasContext.arc(snowBall.x, snowBall.y, snowBall.radius, 0, Math.PI * 2); // สร้างวงกลม ที่คำแหน่ง x, ตำแหน่ง y, รัศมี, รอบวง (2 pi)
   canvasContext.fillStyle = `rgba(255,255,255, ${snowBall.opacity})`; // เตืมสีขาว
   canvasContext.fill(); // วาด
   ```

   ***

1. Countdown Timer
1. Async Await
1. Eye Rolling
1. Watercolor Painting
1. Duck Hunt
1. Konami Code
1. What is "this"?
1. Parallax Scrolling
1. Kanban Board
1. Text Reveal
1. Air Quality Visualizer
1. JavaScript Weird Parts
1. Carousel
1. Music Player
1. Text to Speech
1. Speech to Text
1. What is "prototype"?
1. Autocomplete
1. Form Validation
1. Infinite Scroll Gallery

## เครดิต

สร้างด้วย ♥ โดย [วรายุทธ เลิศกัลยาณวัตร](https://github.com/lvarayut)
