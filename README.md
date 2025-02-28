# 🎨 CSS Cat Painting  

## 📌 Description  
**CSS Cat Painting** is a project designed to explore CSS positioning concepts by creating a stylized cat illustration. This project helps to learn and master:  

- **Absolute positioning**  
- The **z-index** property  
- The **transform** property  

This project is perfect for those who want to improve their CSS skills while working on a fun and visual exercise.  

---  

## 🛠️ Technologies Used  
- **HTML5**  
- **CSS3**  

---  

## 📂 Project Structure  

```
/css-cat-painting
│── index.html
│── styles.css
└── README.md
```

### 📜 Files  
1️⃣ **index.html**: The HTML structure of the project  
2️⃣ **styles.css**: CSS styles to create the cat illustration  

---  

## 🚀 Installation & Execution  

### 1️⃣ Clone the project  
```sh
git clone https://github.com/your-github-profile/css-cat-painting.git
cd css-cat-painting
```

### 2️⃣ Open the file  
- Open **index.html** in a browser to see the rendering.  

---  

## 🎯 Features  

- A complete cat illustration using pure CSS  
- Advanced use of absolute positioning  
- Layer management with `z-index`  
- Shape manipulation with `border` and `transform`  

---  

## 📌 Project Preview  

![Project Preview](./image.png)  

---  

## 🔗 Code Example  

**HTML:**  
```html
<div class="cat-head">
  <div class="cat-ears">
    <div class="cat-left-ear">
      <div class="cat-left-inner-ear"></div>
    </div>
    <div class="cat-right-ear">
      <div class="cat-right-inner-ear"></div>
    </div>
  </div>
</div>
```

**CSS:**  
```css
.cat-head {
  position: absolute;
  right: 0;
  left: 0;
  top: 0;
  bottom: 0;
  margin: auto;
  background: linear-gradient(#5e5e5e 85%, #45454f 100%);
  width: 205px;
  height: 180px;
  border: 1px solid #000;
  border-radius: 46%;
}
```

---  

## 📈 Possible Improvements  
- Add CSS animations (e.g., blinking eyes, whisker movement)  
- Enable color customization via an interactive interface  
- Convert the project into a React component  

---  

## 📝 Author  
📝 **Gabriel Ralph Christian**  
Developer passionate about programming, artificial intelligence, and user interfaces.  

---  

## 📜 License  
📜 This project is under the **MIT license** – you are free to use, modify, and share it.
