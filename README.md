# 03.1 - Meta Viewport CSS Media Queries

## **HTML Instructions**

In both pages, add the meta viewport code:

```html
<meta name="viewport" content="width=device-width, initial-scale=1" />
```

----

## CSS Instructional Steps

## ✅ CODE ALONG

### **1. Set a base background color for mobile**

- Create a base style for the `body`.
- Set the background color to **light gray**.
- This style will apply to mobile screens by default.

----

### **2. Create a tablet media query (min-width: 768px)**

- Write a media query that activates when the screen width is **at least 768px**.
- Inside the query:
  - Target the `body`.
  - Change the background color to **light blue**.
- This breakpoint is commonly used for tablets.

----

### **3. Create a desktop media query (min-width: 1024px)**

- Write a media query that activates when the screen width is **at least 1024px**.
- Inside the query:
  - Target the `body`.
  - Change the background color to **light yellow**.
- This breakpoint is commonly used for desktops.

----

## ✅ CODE IT SOLO

### **1. Hide the mobile navigation menu**

- In the base CSS:
  - Select the `<ul>` inside `<nav>`.
  - Set `display: none;` to hide the navigation list for mobile.

### **2. Create a tablet media query (min-width: 768px) for navigation**

Inside the 768px media query:

#### **a. Hide the menu icon**

- Select the `.menu` class.
- Set `display: none;`.

#### **b. Show the navigation bar**

- Select the `<nav> ul`.
- Change it from hidden to visible (e.g., `display: block;` or `display: flex;`).

#### **c. Apply Flexbox to `.sections`**

- Select the `.sections` class.
- Apply Flexbox properties such as:
  - `display: flex;`
  - `justify-content: space-between;`

### **3. Create a desktop media query (min-width: 1024px)**

- Add a new media query for screens **1024px or wider**.
- Inside the query:
  - Apply **any custom styles** you want for the desktop layout.
