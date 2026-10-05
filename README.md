<div align="center">

# 🎂 Something Unique For My Cutie

### *A little birthday experience made to feel personal. 💗*

<br>

<a href="https://something-unique-for-my-cutie.vercel.app">
  <img src="https://img.shields.io/badge/🌐%20Live%20Website-Open%20Gift-ff69b4?style=for-the-badge" alt="Live Website">
</a>
&nbsp;
<a href="https://github.com/Hidden-Rhythm/something-unique-for-my-cutie">
  <img src="https://img.shields.io/badge/💻%20Source-GitHub-black?style=for-the-badge&logo=github" alt="GitHub">
</a>

</div>

---

## 💌 What Is This?

**Something Unique For My Cutie** is a small interactive birthday experience built with **HTML, CSS, and JavaScript**.

Instead of showing a fixed birthday message, the visitor first enters a few personal details:

* 👤 Name
* 🎂 Age
* 📅 Date of birth
* 📸 A personal picture

After submitting, the form disappears and the birthday experience is revealed.

The result is a simple personalized page with music, reactions, GIFs, and a few playful surprises.

---

## ✨ Features

| Feature                    | Description                                           |
| -------------------------- | ----------------------------------------------------- |
| 🎂 Birthday Form           | Collects name, age and date of birth                  |
| 📸 Personal Photo          | Displays the uploaded image directly in the browser   |
| 🎉 Dynamic Birthday Header | Generates a birthday message from the entered details |
| 🎁 Interactive Gifts       | Hover over each gift to reveal its content            |
| 😂 Reaction GIFs           | Multiple animated reactions and visual surprises      |
| 🎵 Birthday Music          | Includes a local `happybirthday.mp3` track            |
| 💗 Personalized Experience | Uses the visitor's own information                    |
| 🌙 Dark Birthday Theme     | Red-to-black gradient background                      |
| 🐵 Happy Monkey Font       | Uses the playful `Happy Monkey` Google Font           |
| ⚡ Lightweight              | No framework or backend required                      |

---

## 🧭 How It Works

```text
             ┌──────────────────────┐
             │   Birthday Form 🎂   │
             └──────────┬───────────┘
                        │
             ┌──────────▼───────────┐
             │ Enter Personal Info  │
             │                      │
             │ Name                 │
             │ Age                  │
             │ Date of Birth        │
             │ Upload Picture       │
             └──────────┬───────────┘
                        │
                      SUBMIT
                        │
             ┌──────────▼───────────┐
             │  Birthday Revealed 🎉│
             │                      │
             │ Name + Age + DOB     │
             │ Personal Photo       │
             └──────────┬───────────┘
                        │
             ┌──────────▼───────────┐
             │   Interactive Gifts  │
             │                      │
             │   🎁 → GIF           │
             │   🎁 → GIF           │
             │   🎁 → GIF           │
             │   🎁 → GIF           │
             └──────────┬───────────┘
                        │
             ┌──────────▼───────────┐
             │   🎵 Birthday Music  │
             └──────────────────────┘
```

---

## 🎁 The Gift Experience

The page contains several interactive sections that reveal different visuals when hovered.

### 🥳 Birthday Celebration

> **Here's how happy I am for you today 🥳**

Hover over the gift to reveal the associated image.

### 😍 Room Reaction

> **How people react when you enter the room 😍**

A reaction GIF appears when the gift is hovered.

### 🧠 One-Word Description

> **If I had to describe you with ONE word 👇**

Another personalized visual surprise is revealed.

### 💪 The Comparison

> **The only person as same as you 💪**

Hovering reveals another animated GIF.

### 👊 Keep Moving Forward

> **This one's for you, my love, keep moving forward 👊**

The final gift reveals a cheering animation.

---

## 📸 Personalization

The experience doesn't use a predefined birthday identity.

The visitor supplies their own information:

```text
Name
Age
Date of Birth
Picture
```

JavaScript then dynamically creates:

```text
Today is [Name]'s Birthday

[Age] years old

[Formatted Date]
```

The uploaded picture is also displayed immediately using the browser's `FileReader` API.

**No image upload server is required.**

---

## 🎵 Birthday Music

The project includes a local birthday track:

```text
happybirthday.mp3
```

Once the birthday form is submitted, JavaScript attempts to start the audio automatically.

```text
Form Submit
     │
     ▼
Birthday Experience
     │
     ▼
happybirthday.mp3
```

---

## 🖼️ Visual Assets

The project keeps its visual assets locally inside the `images/` directory.

```text
images/
├── OtherYou.webp
├── You.webp
├── cheers.gif
├── darkness.gif
├── gift-cover.avif
└── respect.gif
```

The `gift-cover.avif` image acts as the default gift cover.

Hovering over each gift swaps the background to its corresponding image or GIF.

---

## 🗂️ Project Structure

```text
something-unique-for-my-cutie/
│
├── index.html
├── script.js
├── styles.css
├── happybirthday.mp3
│
└── images/
    ├── OtherYou.webp
    ├── You.webp
    ├── cheers.gif
    ├── darkness.gif
    ├── gift-cover.avif
    └── respect.gif
```

---

## 🛠️ Built With

| Technology        | Purpose                              |
| ----------------- | ------------------------------------ |
| HTML5             | Page structure and form              |
| CSS3              | Layout, theme and hover interactions |
| JavaScript        | Personalization and dynamic content  |
| FileReader API    | Local image preview                  |
| Google Fonts      | Happy Monkey typography              |
| GIF / WebP / AVIF | Interactive visual assets            |
| MP3               | Birthday soundtrack                  |

**No framework. No backend. No database.**

Just a lightweight static experience. ⚡

---

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/Hidden-Rhythm/something-unique-for-my-cutie.git
cd something-unique-for-my-cutie
```

Then open:

```text
index.html
```

directly in your browser.

Or run a local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 🎨 Customization

You can easily personalize the experience by changing:

* 🎂 Birthday messages
* 🎁 Gift section titles
* 🎞️ GIFs and images
* 🎨 Background colors
* ✨ Typography
* 🎵 Birthday music
* 💬 Footer text
* 📸 Default visual assets

Most of the experience is controlled by `index.html`, `styles.css`, and `script.js`.

---

## 🌐 Live Website

### **Something Unique For My Cutie**

<a href="https://something-unique-for-my-cutie.vercel.app">
  https://something-unique-for-my-cutie.vercel.app
</a>

---

## 💻 Source Code

**Hidden-Rhythm / something-unique-for-my-cutie**

<a href="https://github.com/Hidden-Rhythm/something-unique-for-my-cutie">
  View the source on GitHub →
</a>

---

<div align="center">

### Made with code, GIFs, music & a little bit of love. 💗

**Hidden-Rhythm**

</div>
