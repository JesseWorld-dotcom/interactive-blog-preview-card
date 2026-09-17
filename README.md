# 🧠 QuizBlog

> **Answer some questions. Question your intelligence. Unlock a blog.**
> A quiz app where your brain gets tested before you're allowed to read the good stuff. 😭

Welcome to **QuizBlog**, a fun interactive quiz experience built with **HTML, CSS and JavaScript**.

The idea is simple:

**Take the quiz → Survive the questions → Get your score → Unlock your blog preview.**

No account. No database. No complicated setup. Just vibes, questions, and the occasional feeling that JavaScript personally hates you.

---

## ✨ Features

### 🧠 Multiple Categories

Choose what kind of brain damage you'd like today:

* 🌍 General Knowledge
* 🌐 HTML
* 🎨 CSS
* ⚡ JavaScript
* 🧠 Mixed Mode

---

### 🎚️ Difficulty Levels

You choose how much suffering you want.

| Level     | Time | Description               |
| --------- | ---: | ------------------------- |
| 😌 Easy   |  20s | Brain is still loading    |
| 🧠 Medium |  15s | Okay, now think           |
| 💀 Hard   |  10s | Your keyboard is sweating |

The difficulty actually changes the questions and timer.

---

### 🎯 Randomized Answers

The correct answer isn't permanently hiding behind **A** anymore.

Every question shuffles its answers, so:

> A → B → C → D

can become:

> C → A → D → B

No more exploiting the ancient **"just click A"** strategy. 😂

---

### ⏱️ Question Timer

Every question has a countdown.

If you take too long:

**💀 TIME'S UP**

The quiz doesn't care about your excuses.

---

### 🔥 Streak System

Get consecutive questions correct and build your streak.

```text
🔥 1
🔥 2
🔥 3
🔥 4
🔥 5
```

Then one question comes along and says:

> "Choose wisely."

And suddenly the streak is gone.

---

### 📊 Results Dashboard

After finishing, you get:

* Total score
* Correct answers
* Wrong answers
* Accuracy
* Best streak
* Performance message

Because apparently knowing that you got **7/10** isn't enough. We need statistics. 📈

---

## 🔓 The Main Feature

### Blog Preview Unlock

The whole point of the app:

**You don't get the blog preview until you finish the quiz.**

Your performance determines the blog content you unlock.

For example:

### 🏆 90%+

> **"Your brain just speed-ran that quiz."**

You unlock:

**The Developer Brain: How to Think Through Problems Instead of Panic-Searching**

---

### 🥈 70–89%

> **"Pretty solid. The bugs are nervous."**

You unlock:

**7 Frontend Habits That Make You a Better Developer**

---

### 🥉 50–69%

> **"The brain has entered beta testing."**

You unlock:

**The Frontend Concepts You Should Actually Understand**

---

### 💀 Below 50%

> **"The compiler would like a word."**

You unlock:

**Frontend Mistakes Everyone Makes Before They Get Good**

Even failure comes with reading material. 😭

---

## 🌗 Dark & Light Mode

Because sometimes your eyes want:

☀️ **Light mode**

and sometimes your inner developer says:

🌙 **"Turn off the lights."**

The theme can be switched instantly using the button in the top-right corner.

---

## 📱 Responsive Design

QuizBlog works across:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📟 Small screens

The layout adapts automatically so your quiz doesn't look like it was designed by a calculator.

---

## 🛠️ Built With

No frameworks.

No libraries.

No 47,000-node `node_modules` folder.

Just:

```text
HTML
CSS
JavaScript
```

### HTML

Handles the structure and content.

### CSS

Handles:

* Layout
* Responsive design
* Animations
* Cards
* Buttons
* Dark mode
* Progress bars
* Styling

### JavaScript

Handles:

* Quiz logic
* Question selection
* Difficulty
* Random answers
* Timer
* Score
* Streaks
* Results
* Blog unlocking
* Theme switching

---

## 🚀 Getting Started

### 1. Clone the project

```bash
git clone https://github.com/yourusername/quizblog.git
```

### 2. Open the folder

```bash
cd quizblog
```

### 3. Open the HTML file

You can simply open:

```text
index.html
```

in your browser.

That's it.

No `npm install`.

No `npm run build`.

No sacrificing your laptop to the JavaScript gods. 🙏

---

## 📂 Project Structure

The current version can live entirely inside one file:

```text
quizblog/
│
└── index.html
```

The HTML contains:

```text
HTML
├── Quiz structure
├── Result screen
└── Blog preview

CSS
├── Light theme
├── Dark theme
├── Responsive layout
└── UI animations

JavaScript
├── Questions
├── Quiz engine
├── Timer
├── Score system
├── Streak system
└── Blog unlock system
```

---

## 🎮 How It Works

```text
        START
          │
          ▼
   Choose Category
          │
          ▼
   Choose Difficulty
          │
          ▼
     Take Quiz
          │
          ▼
   Answer Questions
          │
          ▼
     Calculate Score
          │
          ▼
   ┌───────────────┐
   │   How did you │
   │     do? 🤔    │
   └───────┬───────┘
           │
           ▼
      Show Results
           │
           ▼
    🔓 Unlock Blog
```

---

## 🧩 Customizing Questions

Questions are stored inside the JavaScript object:

```js
const questionBank = {
  general: [],
  html: [],
  css: [],
  javascript: []
};
```

To add a question:

```js
{
  level: "medium",

  q: "What does CSS stand for?",

  a: [
    "Cascading Style Sheets",
    "Creative Style System",
    "Computer Style Sheets",
    "Colorful Style Syntax"
  ],

  correct: 0,

  explanation:
    "CSS stands for Cascading Style Sheets."
}
```

Just remember:

```js
correct: 0
```

means the first answer is correct.

The app will shuffle the answers automatically.

---

## 💡 Future Ideas

Things that could make QuizBlog even more ridiculous:

* 🏆 Leaderboard
* 👤 User profiles
* 💾 Save quiz history
* 🎵 Sound effects
* 🔊 Correct/wrong sounds
* 🎉 Confetti for high scores
* 🏅 Achievements
* 📚 Full blog article pages
* ❤️ Lives system
* 🧩 Daily quiz
* 🔥 Daily streak
* ⏱️ Speed-run mode
* 🎲 Completely random questions
* 🤖 AI-generated questions
* 📈 Detailed performance analytics

And possibly a mode where the quiz insults you after three wrong answers.

**Respectfully, of course.** 😭

---

## 🤝 Contributing

Want to improve QuizBlog?

Fork it.

Break it.

Fix it.

Make a pull request.

If you somehow make the quiz harder than Hard mode, we may need to have a meeting.

---

## 📜 License

This project is almost free to use, modify and learn from.
for advanced modification $1.99
Go build something cool. 🚀

---

## ⭐ Final Words

QuizBlog started with one very important question:

> **"What if I had to prove I was smart before reading a blog?"**

And somehow we ended up here.

**Quiz first. Blog later.**

Good luck.

Your brain has been notified. 🧠⚡
