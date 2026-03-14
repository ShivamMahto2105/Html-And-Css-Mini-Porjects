# Responsive Contact Us Page

A clean and responsive **Contact Us page** built using **HTML5 and CSS3**.
This project demonstrates how to create a modern contact section with address, phone, email details, and a message form.

---

## 📌 Features

* Responsive layout for **desktop, tablet, and mobile**
* Clean **card-style UI**
* **Flexbox layout**
* Contact information section
* Message form with inputs and textarea
* **Font Awesome icons**
* Vertical divider using **CSS pseudo-element (::before)**

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Flexbox**
* **Responsive Media Queries**
* **Font Awesome Icons**

External resources:

* Font Awesome
* Google Fonts (Poppins)

---

## 📄 index.html

Contains the structure of the webpage including:

* Contact details
* Form inputs
* Icons
* Page layout

---

## 🎨 style.css

Responsible for styling such as:

* Page background
* Container layout
* Flexbox alignment
* Typography
* Button hover effects
* Responsive behavior

The layout uses **Flexbox** to divide the page into:

```
Contact Information | Message Form
```

---

## 📱 Responsive Design

Media queries are used to adjust layout for smaller screens.

Desktop layout:

```
---------------------------------------
| Contact Info | Send Message Form   |
---------------------------------------
```

Mobile layout:

```
Send Message Form
Contact Info
```

---

## ✨ CSS Concept Used

### Pseudo-element

The vertical separator is created using:

```
::before
```

Example:

```css
.content .add-cont-email::before{
  content:'';
  position:absolute;
  height:70%;
  width:2px;
  background:#afafb6;
}
```

This allows adding decorative elements without extra HTML.

---

## 🚀 How to Run the Project

1. Download or clone the repository
2. Open the folder
3. Double-click **index.html**

or run with a live server.

---

## 📸 Preview
![Preview Image](https://github.com/ShivamMahto2105/Html-And-Css-Mini-Porjects/blob/main/7%20Responsive%20Contact%20Us/Preview.png)

## 📧 Contact

If you have any queries or suggestions, feel free to reach out.

Author: **Shivam Kumar Mahto**

Email:
[shivammahto2105@gmail.com](mailto:shivammahto2105@gmail.com)
[skguddu2003@gmail.com](mailto:skguddu2003@gmail.com)

---

## ⭐ Future Improvements

* Form validation with JavaScript
* Backend integration to send emails
* Tailwind CSS version
* Dark mode support

