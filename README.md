# IMAGEGALLERYUSINGFLEXBOX
# 🎨 Image Gallery Project

This is a simple and elegant **Image Gallery** project built using **HTML and CSS**. The gallery displays **9 images** arranged in a **3x3 grid**. By default, the images are in **black and white**, and when you hover over any image, it turns into **full color**, creating a visually appealing interactive effect.

---

## 📸 Features

- 🖼️ 3x3 responsive image grid layout
- ⚫➡️🔴 Black-and-white to color hover effect using pure CSS
- 💡 Simple and clean design using modern CSS techniques
- 🎯 Cross-browser compatible

---

## 🚀 Technologies Used

- HTML5
- CSS3 (Flexbox or Grid layout)

---

## 📂 Folder Structure

image-gallery/
│
├── index.html # Main HTML file
├── style.css # Styling file
└── images/ # Folder containing 9 image files
├── image1.jpg
├── image2.jpg
└── ... up to image15.jpg


---

## 🛠️ How It Works

1. **Grid Layout**: The images are arranged using either **CSS Flexbox** or **CSS Grid** in 3 rows and 3 columns.
2. **Black & White Effect**: All images use the CSS `filter: grayscale(100%)`.
3. **Hover Effect**: On hovering an image, the grayscale filter is removed using `:hover { filter: none; }` or `grayscale(0%)`.

---

## 🖥️ Live Demo

https://chimerical-daffodil-93355d.netlify.app/

---

## 🧾 Code Snippet

```css
img {
  width: 100%;
  filter: grayscale(100%);
  transition: 0.3s ease;
}

img:hover {
  filter: grayscale(0%);
}

📌 Usage
Download or clone the repository.
Replace the images in the images/ folder with your own if needed.
Open index.html in your browser to see the gallery.

🙌 Author
Made with ❤️ by [YASH AGARWAL]
