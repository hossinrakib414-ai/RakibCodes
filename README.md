<p align="center">
  <img src="https://raw.githubusercontent.com/hossinrakib414-ai/hossinrakib414-ai/4150c35d3741d43f62d6e9b6256999ade7ac483f/ChatGPT%20Image%20Jun%2028%2C%202026%2C%2009_17_58%20PM.png" width="100%" alt="GitHub Banner">
</p>

<h1 align="center">Hi 👋, I'm Rakib Hossin</h1>
<h3 align="center">Learner AI Driven Full Stack Web Engineer</h3>

- 🔭 I’m currently working on **React Learning Projects**
- 🌱 I’m currently learning **React.js, TypeScript and Next.js**
- 👯 I’m looking to collaborate on **Frontend Web Development Projects**
- 🤝 I’m looking for help with **Advanced React and Next.js**
- 👨‍💻 All of my projects are available at [Coming Soon (Portfolio Website)](#)
- 📝 I regularly write articles on [Coming Soon](#)
- 💬 Ask me about **HTML, CSS, JavaScript and React Basics**
- 📫 How to reach me **hossinrakib414@gmail.com // rakibwork9@gmail.com**
- 📄 Know about my experiences [Coming Soon (Resume)](#)
- ⚡ Fun fact **I enjoy turning ideas into web applications. I love solving JavaScript problems. I learn by building real projects. Coffee + Coding = My favorite combo ☕**

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://linkedin.com/in/rakib-hossen-722b232a7/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="35" style="border-radius: 20px;" />
  </a>
  <a href="https://facebook.com/rj.rakib.rj.rakib.43516/" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" height="35" />
  </a>
  <a href="https://instagram.com/hossinrakib4141/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" height="35" />
  </a>
  <a href="https://discord.gg/mdrakibhossen0444" target="_blank">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35" />
  </a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,tailwind,nextjs,git,vscode&theme=dark" />
</p>


<-- new-->

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>GitHub Contribution Graph</title>
<style>
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    background: #fff;
    color: #24292f;
    padding: 20px;
  }
  .controls {
    max-width: 900px;
    display: flex;
    gap: 8px;
    margin-bottom: 16px;
  }
  .controls input {
    flex: 1;
    padding: 8px 10px;
    border: 1px solid #d0d7de;
    border-radius: 6px;
    font-size: 14px;
  }
  .controls button {
    padding: 8px 16px;
    border: 1px solid #1f883d;
    background: #2da44e;
    color: #fff;
    border-radius: 6px;
    font-size: 14px;
    cursor: pointer;
  }
  .controls button:hover { background: #2c974b; }
  .controls button:disabled { background: #94d3a2; border-color: #94d3a2; cursor: default; }

  .status {
    max-width: 900px;
    font-size: 13px;
    color: #57606a;
    margin-bottom: 10px;
    min-height: 16px;
  }
  .error { color: #cf222e; }

  .card {
    border: 1px solid #d0d7de;
    border-radius: 6px;
    padding: 16px;
    max-width: 900px;
    overflow-x: auto;
    display: none;
  }
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 12px;
    font-size: 14px;
  }
  .header h2 {
    font-size: 14px;
    font-weight: 600;
    margin: 0;
  }
  .header .settings {
    color: #57606a;
    font-size: 12px;
    cursor: pointer;
  }
  .months {
    display: flex;
    font-size: 11px;
    color: #57606a;
    margin-bottom: 4px;
    margin-left: 26px;
  }
  .month-label {
    width: 15.5px;
    white-space: nowrap;
  }
  .graph-wrapper {
    display: flex;
  }
  .day-labels {
    display: grid;
    grid-template-rows: repeat(7, 11px);
    row-gap: 3px;
    margin-right: 6px;
    font-size: 11px;
    color: #57606a;
    flex-shrink: 0;
  }
  .day-labels div {
    height: 11px;
    display: flex;
    align-items: center;
  }
  .weeks {
    display: grid;
    grid-auto-flow: column;
    grid-template-rows: repeat(7, 11px);
    row-gap: 3px;
    column-gap: 3px;
  }
  .day {
    width: 11px;
    height: 11px;
    border-radius: 2px;
    background: #ebedf0;
  }
  .l1 { background: #9be9a8; }
  .l2 { background: #40c463; }
  .l3 { background: #30a14e; }
  .l4 { background: #216e39; }

  .footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 10px;
    font-size: 11px;
    color: #57606a;
  }
  .legend {
    display: flex;
    align-items: center;
    gap: 3px;
  }
  .legend .day {
    width: 10px;
    height: 10px;
  }
  a {
    color: #57606a;
    text-decoration: none;
  }
</style>
</head>
<body>

<div class="controls">
  <input id="username" type="text" placeholder="Enter GitHub username (e.g. torvalds)" />
  <button id="loadBtn">Load</button>
</div>

<div class="status" id="status"></div>

<div class="card" id="card">
  <div class="header">
    <h2 id="total">Contributions</h2>
    <div class="settings">Contribution settings ▾</div>
  </div>

  <div class="months" id="months"></div>

  <div class="graph-wrapper">
    <div class="day-labels">
      <div></div>
      <div>Mon</div>
      <div></div>
      <div>Wed</div>
      <div></div>
      <div>Fri</div>
      <div></div>
    </div>
    <div class="weeks" id="weeks"></div>
  </div>

  <div class="footer">
    <a href="#">Learn how we count contributions</a>
    <div class="legend">
      Less
      <div class="day"></div>
      <div class="day l1"></div>
      <div class="day l2"></div>
      <div class="day l3"></div>
      <div class="day l4"></div>
      More
    </div>
  </div>
</div>

<script>
const usernameInput = document.getElementById('username');
const loadBtn = document.getElementById('loadBtn');
const statusEl = document.getElementById('status');
const card = document.getElementById('card');
const totalEl = document.getElementById('total');
const weeksContainer = document.getElementById('weeks');
const monthsContainer = document.getElementById('months');

function levelClass(level) {
  if (level === 1) return 'l1';
  if (level === 2) return 'l2';
  if (level === 3) return 'l3';
  if (level === 4) return 'l4';
  return '';
}

async function loadContributions() {
  const username = usernameInput.value.trim();
  if (!username) {
    statusEl.textContent = 'Please enter a GitHub username.';
    statusEl.className = 'status error';
    return;
  }

  statusEl.textContent = 'Loading contributions for "' + username + '"...';
  statusEl.className = 'status';
  loadBtn.disabled = true;
  card.style.display = 'none';

  try {
    const res = await fetch('https://github-contributions-api.jogruber.de/v4/' + encodeURIComponent(username) + '?y=last');
    if (!res.ok) {
      throw new Error(res.status === 404 ? 'User not found' : 'API error (' + res.status + ')');
    }
    const data = await res.json();

    if (!data.contributions || data.contributions.length === 0) {
      throw new Error('No contribution data returned');
    }

    const contributions = data.contributions;
    const totalCount = contributions.reduce((sum, d) => sum + d.count, 0);

    const map = {};
    contributions.forEach(d => { map[d.date] = d; });

    const dates = contributions.map(d => new Date(d.date));
    const minDate = new Date(Math.min(...dates));
    const maxDate = new Date(Math.max(...dates));

    const start = new Date(minDate);
    start.setDate(start.getDate() - start.getDay());

    weeksContainer.innerHTML = '';
    monthsContainer.innerHTML = '';
    totalEl.textContent = totalCount.toLocaleString() + ' contributions in the last year';

    let cursor = new Date(start);
    let lastMonth = -1;

    while (cursor <= maxDate) {
      const firstDayOfWeek = new Date(cursor);
      if (firstDayOfWeek.getMonth() !== lastMonth) {
        lastMonth = firstDayOfWeek.getMonth();
        const label = document.createElement('div');
        label.className = 'month-label';
        label.textContent = firstDayOfWeek.toLocaleString('en-US', { month: 'short' });
        monthsContainer.appendChild(label);
      } else {
        const spacer = document.createElement('div');
        spacer.className = 'month-label';
        monthsContainer.appendChild(spacer);
      }

      for (let d = 0; d < 7; d++) {
        const key = cursor.toISOString().slice(0, 10);
        const entry = map[key];
        const level = entry ? entry.level : 0;
        const dayEl = document.createElement('div');
        dayEl.className = 'day ' + levelClass(level);
        dayEl.title = key + ': ' + (entry ? entry.count : 0) + ' contributions';
        weeksContainer.appendChild(dayEl);
        cursor.setDate(cursor.getDate() + 1);
      }
    }

    card.style.display = 'block';
    statusEl.textContent = 'Loaded contributions for ' + username + '.';
  } catch (err) {
    statusEl.textContent = 'Error: ' + err.message;
    statusEl.className = 'status error';
  } finally {
    loadBtn.disabled = false;
  }
}

loadBtn.addEventListener('click', loadContributions);
usernameInput.addEventListener('keydown', (e) => {
  if (e.key === 'Enter') loadContributions();
});
</script>

</body>
</html>

  

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hossinrakib414-ai&theme=react&border_radius=15" alt="GitHub Streak" />
</p>
