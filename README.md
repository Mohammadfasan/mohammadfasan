<!-- Animated Header -->
<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Hi+👋,+I'm+Mohammad+Fasan;Full+Stack+Developer;Android+%26+UI%2FUX+Designer;Welcome+to+my+GitHub+Profile!" alt="Typing SVG" />
  </a>
</h1>

<p align="center">
  <a href="https://github.com/Mohammadfasan">
    <img src="https://komarev.com/ghpvc/?username=Mohammadfasan&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="profile views" />
  </a>
</p>

---

### 💫 About Me  
🎓 B.ICT (Hons) Undergraduate | University of Colombo  
💻 Passionate about **Full-Stack Development** & **Android Apps**  
🌱 Currently learning **React Native** & **Cloud Hosting (Firebase + Vercel)**  
💬 Ask me about **React, Node.js, Express, MongoDB, Firebase, Tailwind CSS**  
📫 Reach me at **mohammedfasan617@gmail.com**  
🌐 Portfolio: [mohammadfasan.github.io/portfolio](https://mohammadfasan.github.io/portfolio)

---

### 🧩 Tech Stack
<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,express,mongodb,java,androidstudio,tailwind,firebase,figma,git,github,postman" />
</p>

---

### 🧠 Code Sample
Here’s a mini snippet that represents my coding style 👇  

```js
// Sample: Express route to fetch user data from MongoDB
import express from 'express';
import User from '../models/User.js';

const router = express.Router();

router.get('/users', async (req, res) => {
  try {
    const users = await User.find();
    res.status(200).json(users);
  } catch (err) {
    res.status(500).json({ message: 'Error fetching users', error: err });
  }
});

export default router;
