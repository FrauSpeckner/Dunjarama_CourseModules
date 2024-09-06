# Dunjarama - CourseModules for the C4L-Plugin 🎉
# 🎨 Moodle CSS Design for Course Components 🎨

![Title Image](https://assets.codepen.io/7398902/readme.png)

This project includes various design elements for Moodle course components, organized into **Categories**, **Flavours**, and **Components**. Additionally, the necessary HTML code is provided to make the implementation as smooth as possible. With this structure, you can easily and quickly change or customize anything you need. 🛠️

---

## 🌟 **Category: Base Design (General Styles)** 🌟

The **Base Design** category contains the essential CSS rules that applys to all containers and boxes in this category. These styles include general settings like border, colors, font, and layout – everything you need to give the design a consistent, polished look! ✨

### Example:
```css
.c4l-box {
  border-radius: 15px;
  border: 4px solid black;
  padding: 20px;
  margin: 40px 0;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  font-family: "mebisDruckschrift", Arial;
  font-size: 24px;
}

## 🐶🐱**Flavour: Horst and Wolke** ☁️

**Flavours** are special designs that change the look of each component depending on the avatar, colors, and images. In this section, you can find the specific styles for our adorable Flavours: like Horst and Wolke! 🌈

### **Horst** (c4l-vatar1)) 
- **Avatar:** Horst ist the star here 
- **Images:** Depending on the component type (like Tip or Feedback), Horst shows different fun expressions! 😎

.c4l-avatar1.c4l-tip::before {
    background-image: url('https://assets.codepen.io/7398902/mDS_Horst_peace.png');
}

### **Wolke** (c4l_avatar2)

- **Avatar:**  Wolke is here to brighten your day! ☁️
- **Images:** Wolke’s images change according to the content of the box. 😊

.c4l-avatar2.c4l-feedback::before {
    background-image: url('https://assets.codepen.io/7398902/Wolke-Feedback.svg');
}

##**📦 Components: Different Box Types 📦**

Each **component** represents a different type of content you can use in your Moodle course! 💬 Whether you’re giving feedback or sharing tips, these boxes are easily customizable. 🎉

### **Example:**

- **Tip Box** (.c4l-tip): Contains helful tips to make things clearer. 💡

.c4l-box.c4l-tip {
  background-color: #FFEECC;
}

- **Feedback Box** (.c4l-feedback): Shows feedback in a colorful and fun way! 🌟

.c4l-box.c4l-feedback {
  background-color: #E7FAC3;
}

## **📝 HTML Code 📝**

Here’s where the magic happens! ✨ In this section, you’ll find the HTML code for the different boxes. 🥳

**Example HTML:**

<div class="c4l-box c4l-avatar1 c4l-tip">
  <p>Tip from Horst: [PLACEHOLDER FOR TEXT]</p>
</div>

<div class="c4l-box c4l-avatar2 c4l-feedback">
  <p>Feedback from Wolke: [PLACEHOLDER FOR TEXT]</p>
</div>


You can easily swap out the avatars or change the box types to fit your course.  🚀


##**🎨 Customization 🎨**

This design is made to be super flexible so you can customize it quickly! 😘 Change the Flavour, update the box types, or swap out images. Everything is designed to be simple and fast to update, giving you maximum control over the look. ✨
