- 👋 Hi, I’m MOHAN KUMAR
- 👀 I’m interested in Computer technology as a whole and too curious to know what i find next.
- 🌱 I’m currently learning Distributed Systems with Golang,C++
- 💞️ I’m looking to collaborate on programming side
- 📫 To reach me : mohankumarr2407@gmail.com


# My Tech Stack

Here are some of the technologies I work with:

<div style="width: 100%; overflow: hidden;">
  <div style="display: flex; transition: transform 0.5s ease;">
    <div style="min-width: 150px; margin: 10px; text-align: center; background: #f0f0f0; padding: 20px; border-radius: 8px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript" width="60" />
      <h4>JavaScript</h4>
    </div>
    <div style="min-width: 150px; margin: 10px; text-align: center; background: #f0f0f0; padding: 20px; border-radius: 8px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub" width="60" />
      <h4>GitHub</h4>
    </div>
    <div style="min-width: 150px; margin: 10px; text-align: center; background: #f0f0f0; padding: 20px; border-radius: 8px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/63/React-icon.svg" alt="React" width="60" />
      <h4>React</h4>
    </div>
    <div style="min-width: 150px; margin: 10px; text-align: center; background: #f0f0f0; padding: 20px; border-radius: 8px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Node.js_logo.svg" alt="Node.js" width="60" />
      <h4>Node.js</h4>
    </div>
    <div style="min-width: 150px; margin: 10px; text-align: center; background: #f0f0f0; padding: 20px; border-radius: 8px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Logo-MySQL.svg" alt="MySQL" width="60" />
      <h4>MySQL</h4>
    </div>
  </div>
</div>

<div style="text-align: center; margin-top: 10px;">
  <button onclick="moveCarousel(-1)">&#10094; Prev</button>
  <button onclick="moveCarousel(1)">Next &#10095;</button>
</div>

<script>
  let currentIndex = 0;

  function moveCarousel(direction) {
    const carousel = document.querySelector('div > div');
    const items = carousel.children.length;
    currentIndex = (currentIndex + direction + items) % items;
    const offset = -currentIndex * (carousel.children[0].offsetWidth + 20);
    carousel.style.transform = `translateX(${offset}px)`;
  }
</script>
