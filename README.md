
# Dunjarama - CourseModules for the C4L-Plugin 🎉

## 🎨 Moodle CSS Design for Course Components 🎨

![Title Image](https://assets.codepen.io/7398902/readme.png)

**Dunjarama** brings a variety of **visual components** to Moodle courses, designed to work seamlessly with the **C4L-Plugin**. This includes **color-coded boxes**, **interactive elements**, and **custom avatars** that add personality and clarity to course modules. 💡

---

## 🌟 What’s Inside?

**Avatars** are an essential part of making course components engaging and fun. They help categorize different **flavours** (themes) and bring visual recognition to various parts of your course. Avatars always come in **pairs**, serving as **moderators** that guide students through the course content. 

These pairs make the course feel more interactive and personalized, adding a unique touch to the learning experience.


### 🔧 How Avatars Work:

- **Categories define the general style** – each category has specific **CSS rules** that shape the overall look, such as borders, colors, and fonts.
- **Flavours** allow customization with different **avatars** and **design tweaks** for specific content.

---

## 🎭 **Avatar Usage and Customization**

### Example: **TechPals** Category (featuring **horst_cloud** and **robi_bot** avatars)

For the **TechPals** category, the avatars are placed either on the **left** or **right** of the box. Here’s how you can work with them:

1. **Category Styles**:
   - `.c4l-techpals-title-box` – Defines the look of the title box.
   - `.c4l-techpals-box` – The main container for each component.
   
2. **Avatar Placement**:
   - **Left-side avatars** use `.c4l_avatar1`.
   - **Right-side avatars** use `.c4l_avatar2`.

3. **Customizing Flavours**:
   - For the **horst_cloud** flavour:
     - `.c4l-techpals-box .c4l_avatar1 .c4l-horst-tip` (left avatar for tips)
     - `.c4l-techpals-box .c4l_avatar2 .c4l-horst-szenario` (right avatar for scenarios)
   - For the **robi_bot** flavour:
     - `.c4l-techpals-box .c4l_avatar1 .c4l-bot-tip` (left avatar for tip)
     - `.c4l-techpals-box .c4l_avatar2 .c4l-bot-szenario` (right avatar for szenario)

### 🛠️ **Easy to Customize**:

1. **Avatar Size and Placement**: Adjust the avatar size or switch sides easily with CSS.
2. **Flavours**: Assign different avatars to match the **flavour** of the content. Use pseudoelements (`::before`) to manage the avatar images dynamically.
3. **Additional Flavours**: As new content or themes are introduced, adding a new **flavour** with specific avatars is simple by extending the CSS.

---

## 💡 **Why Use Avatars?**

- **Engagement**: Avatars make the course visually appealing and easier to navigate.
- **Clarity**: Using avatars for different flavours helps learners identify content types at a glance.
- **Customization**: Each avatar can be customized per category, making your course unique and branded to its content.

---

## 🎨 **Flexible Design for Your Needs**

This system is built to be **flexible and scalable**, so you can update it quickly. Change avatars, tweak box types, or swap images easily within the CSS framework. Everything is designed for **quick updates** and **maximum control** over the look and feel of your course. ✨

---

## 🎮 Interactive Elements

**Dunjarama** also includes a range of **interactive elements** that help make your Moodle courses more engaging and intuitive. These elements are designed to enhance the learning experience, offering students more ways to interact with the content while keeping the course visually appealing.

### 🔥 **Key Interactive Features**:

1. **Flip Cards** 🃏  
   Flip Cards allow you to present information on both sides. The front side shows a question, term, or image, and flipping reveals the answer or additional details. This makes learning more interactive and helps break down content into manageable pieces.
   
   - **Use Case**: Great for flashcards, quizzes, or visual explanations.
   - **Customization**: You can easily change the content, design, and flip behavior to suit your needs.

2. **Juxtaposition** 🖼️  
   The Juxtaposition element is perfect for showing a **before-and-after** comparison. It features two images, one on the left and one on the right, with a slider to let students reveal the difference between the two.
   
   - **Use Case**: Ideal for comparing images, diagrams, or timelines.
   - **Customization**: Change the images and adjust the slider style to fit your course’s theme.

3. **Carousel** 🎠  
   The Carousel allows you to showcase multiple images or pieces of content that students can cycle through. It’s a great way to display image galleries or step-by-step content.

   - **Use Case**: Perfect for showing a series of steps, a collection of images, or rotating through key points.
   - **Customization**: Adjust the number of slides, navigation, and transition speed to match your content.

4. **Accordion Cards** 📚  
   Accordion Cards hide large amounts of information in collapsible sections. Students can click to reveal more details, making the content easier to digest.

   - **Use Case**: Useful for FAQ sections, definitions, or course module summaries.
   - **Customization**: Easily modify the content in each section and change the card design.

5. **Checklist** ✅  
   The Checklist allows students to keep track of their progress. As they complete tasks or modules, they can mark items as done. This is a simple, visual way to encourage progress and keep students engaged.

   - **Use Case**: Task lists, assignments, or progress tracking for longer projects.
   - **Customization**: Add or remove tasks, change the visual style, and even integrate it with course completion data.

---

## 🚀 **Why Use Interactive Elements?**

- **Boost Engagement**: Interactive elements help students stay focused and more actively involved in their learning process.
- **Enhance Understanding**: Breaking content into **manageable** and **interactive** pieces allows students to explore concepts at their own pace.
- **Customize and Personalize**: All interactive components can be **customized** to match the course design, providing a consistent, branded learning experience.

---

### 🎨 **Flexible Design for All Interactive Elements**

These elements are not only engaging but also **easy to customize**. You can quickly change their layout, content, and behavior, making them the perfect addition to any Moodle course.


