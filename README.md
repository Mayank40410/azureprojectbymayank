# Resume Website for GitHub Pages

Create these files in a GitHub repository and enable GitHub Pages to host your resume website.

---

## 1. index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mayank Kumar | Resume</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Mayank Kumar</h1>
      <p>B.Tech IT Student | Web Developer | Tech Enthusiast</p>
      <div class="links">
        <a href="mailto:yourmail@gmail.com">Email</a>
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
      </div>
    </div>
  </header>

  <section class="about container">
    <h2>About Me</h2>
    <p>
      I am an Information Technology student passionate about web development,
      software engineering, and AI technologies. I enjoy building modern and
      responsive applications.
    </p>
  </section>

  <section class="skills container">
    <h2>Skills</h2>
    <div class="skill-grid">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>React</span>
      <span>Python</span>
      <span>Java</span>
      <span>SQL</span>
      <span>Git & GitHub</span>
    </div>
  </section>

  <section class="education container">
    <h2>Education</h2>
    <div class="card">
      <h3>Rungta College of Engineering and Technology</h3>
      <p>B.Tech in Information Technology</p>
      <p>2023 - 2027</p>
    </div>
  </section>

  <section class="projects container">
    <h2>Projects</h2>

    <div class="card">
      <h3>Portfolio Website</h3>
      <p>
        Developed a responsive personal portfolio using HTML, CSS, and JavaScript.
      </p>
    </div>

    <div class="card">
      <h3>Authentication System</h3>
      <p>
        Created a secure login and registration system using FastAPI and PostgreSQL.
      </p>
    </div>
  </section>

  <section class="contact container">
    <h2>Contact</h2>
    <p>Email: yourmail@gmail.com</p>
    <p>Phone: +91 XXXXX XXXXX</p>
    <p>Location: Jamshedpur, India</p>
  </section>

  <footer>
    <p>© 2026 Mayank Kumar. All Rights Reserved.</p>
  </footer>
</body>
</html>
```

---

## 2. style.css

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #0f172a;
  color: white;
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 40px 0;
}

header {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(135deg, #2563eb, #7c3aed);
}

header h1 {
  font-size: 3rem;
}

header p {
  margin-top: 10px;
  font-size: 1.2rem;
}

.links {
  margin-top: 20px;
}

.links a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
  border: 1px solid white;
  padding: 10px 18px;
  border-radius: 8px;
  transition: 0.3s;
}

.links a:hover {
  background: white;
  color: #111827;
}

section h2 {
  margin-bottom: 20px;
  font-size: 2rem;
  color: #60a5fa;
}

.card {
  background: #1e293b;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 12px;
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.skill-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.skill-grid span {
  background: #2563eb;
  padding: 10px 18px;
  border-radius: 8px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #020617;
}
```

---

## 3. How to Host on GitHub Pages

### Step 1: Create a GitHub Repository

* Open GitHub
* Click **New Repository**
* Repository name example:

```text
resume-website
```

---

### Step 2: Upload Files

Upload these files:

* index.html
* style.css

---

### Step 3: Enable GitHub Pages

1. Open repository
2. Go to **Settings**
3. Click **Pages**
4. Under **Branch**, select:

```text
main
```

5. Click **Save**

---

### Step 4: Your Website Link

After a few minutes your resume website will be live at:

```text
https://yourusername.github.io/resume-website
```

---

## Optional Improvements

You can also add:

* Download Resume PDF button
* Dark/Light mode
* Project screenshots
* Contact form
* Animations
* React version
* Tailwind CSS version
* Custom domain
