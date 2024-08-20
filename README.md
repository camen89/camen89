- 👋 Hi, I’m @camen89. Other name is Iwamoto
- 👀 I’m interested in interaction design
- 🌱 I’m currently learning python
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ my icon's code
```js
//p5js
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(0);
  
  for(let i = 0; i < 10; i += 0.02){
    noFill();
    stroke(255 % i * 30, 255 % i * 30, 255 % i * 30);
    ellipse(width / 2, height / 2, width / i, height - height / i);
    ellipse(width / 2, height / 2, width - width / i, height / i);
  }
}   
```
  

<!---
camen89/camen89 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
