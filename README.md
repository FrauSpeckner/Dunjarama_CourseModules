# Dunjarama - CourseModules for the C4L-Plugin 🎉

## 🎨 Moodle CSS Design for Course Components 🎨

![Title Image](https://assets.codepen.io/7398902/readme.png)

This project includes various design elements for Moodle course components, organized into **Categories**, **Flavours**, and **Components**. Additionally, the necessary HTML code is provided to make the implementation as smooth as possible. With this structure, you can easily and quickly change or customize anything you need. These Components work with the C4L-Plugin für Moodle.  🛠️

---

### 📂 The Components are divided in different categorys:
Here are the categorys I already made, there are ALOT more to come. 

- [**TechPals**](#category-techpals) – Contains specialized components designed.


---

## 🌟 **How does it work? Categorys define the general style** 🌟
### Here for the category techpals that includes right now horst_cloud and robi_bot

The **category** defines the essential CSS rules that apply to all containers and boxes in this category. These styles include general settings like borders, colors, fonts, and layouts – everything you need to give your design a consistent, polished look! ✨

## CSS-Classes Example

### for categroys:
Here you see all css-classes, that define that look of the components in this category

- .c4l-**techpals**-title-box  *(bestimmt das Ausehen der Titelbox)*
- .c4l-**techpals**-title box::before *(bestimmt das Aussehen des Bildes)*

- .c4l-**techpals**-box *(bestimmt das Aussehen aller Boxen)* 
- .c4l-**techpals**-box .c4l-**techpals**-avatar2 *(bestimmt das Aussehen aller Boxen mit Avatar rechts)*

- .c4l-**techpals**-box .c4l-**techpals**-tip *(Hier werden die Farben der einzelnen Boxen bestimmt)* 
- .c4l-**techpals**-box .c4l-**techpals**-szenario
- .c4l-**techpals**-box .c4l-**techpals**-problem
- .c4l-**techpals**-box .c4l-**techpals**-dontdo
- .c4l-**techpals**-box .c4l-**techpals**-feedback
- .c4l-**techpals**-box .c4l-**techpals**-task

### for flavours:
Here I work with Pseudoelements, that adds the Avatars. To where avatar1 always defines the left and avatar2 the right Avatar. 


**Adding flavours in the title**
- .c4l-**techpals**-title-box .c4l_**horst_cloud**-title::before *(Hier wird das Titelbild für den Flavour horst_cloud hochgeladen)* 
- .c4l-**techpals**-title-box .c4l_**robi_bot**-title::before *(Hier wird das Titelbild für den Flavour robit_bot hochgeladen)* 


**The CSS-classes for horst_cloud**
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-tip 
- .c4l-**techpals**-box .c4l_avatar2 .c4l-**horst**-tip
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-szenario
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-szenario
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-problem
- .c4l-**techpals**-box .c4l_avatar2 .c4l-**horst**-problem
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-dontdo
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-dontdo
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-feedback
- .c4l-**techpals**-box .c4l_avatar2 .c4l-**horst**-feedback
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-task
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**horst**-task

**The CSS-classes for robi_bot**
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-tip
- .c4l-**techpals**-box .c4l_avatar2 .c4l-**bot**-tip
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-szenario
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-szenario
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-problem
- .c4l-**techpals**-box .c4l_avatar2 .c4l-**bot**-problem
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-dontdo
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-dontdo
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-feedback
- .c4l-**techpals**-box .c4l_avatar2 .c4l-**bot**-feedback
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-task
- .c4l-**techpals**-box .c4l_avatar1 .c4l-**bot**-task

*Hier werden die Bilder eingefügt. Es wird die Kategorie bestimmt, hier **techpals** und dann das Flaouvr **horst** oder **bot***

___


## **🎨 Customization 🎨**

This design is made to be super flexible so you can customize it quickly! 😘 Change the Flavour, update the box types, or swap out images. Everything is designed to be simple and fast to update, giving you maximum control over the look. ✨
