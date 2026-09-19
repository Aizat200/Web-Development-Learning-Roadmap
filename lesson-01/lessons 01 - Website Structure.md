# 🟢 Level 1 — Website Fundamentals

# Lesson 01 — Website Structure

## 🎯 Objective

Learn how to build the basic structure of a website using **HTML5** and understand how different pages connect together.

By the end of this lesson, you should be able to create a simple multi-page website with navigation, images, sections, and a footer.

---

## 📚 What You Will Learn

* HTML5 document structure
* Semantic HTML
* Headings and paragraphs
* Links and navigation
* Images
* Lists
* Sections
* Page structure
* Basic accessibility
* Multi-page website structure

---

# 🧠 1. HTML5 Structure

Learn the basic structure of an HTML document.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>

<body>

    <h1>Hello World</h1>

</body>

</html>
```

### Understand:

| Element           | Purpose                    |
| ----------------- | -------------------------- |
| `<!DOCTYPE html>` | Defines HTML5              |
| `<html>`          | Root element               |
| `<head>`          | Metadata and configuration |
| `<title>`         | Browser page title         |
| `<body>`          | Visible website content    |

---

# 🧱 2. Semantic HTML

Learn to structure your website using meaningful HTML elements.

```html
<header>
    Website Header
</header>

<nav>
    Navigation
</nav>

<main>
    Main Content
</main>

<section>
    Content Section
</section>

<footer>
    Website Footer
</footer>
```

### Important Elements

* `<header>`
* `<nav>`
* `<main>`
* `<section>`
* `<article>`
* `<aside>`
* `<footer>`

### Why use semantic HTML?

Instead of creating everything with:

```html
<div>
    ...
</div>
```

Use elements that describe their purpose.

For example:

```html
<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
</nav>
```

This makes the structure easier for developers, browsers, search engines, and accessibility tools to understand.

---

# 🧭 3. Navigation Bar

Create a navigation bar that connects all pages.

```html
<nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="services.html">Services</a>
    <a href="contact.html">Contact</a>
</nav>
```

### Your navigation should allow users to move between:

**Home → About → Services → Contact**

And every page should have the same navigation.

---

# 🏠 4. Home Page

Create a homepage introducing your website.

### Required:

* Website title
* Short description
* Hero section
* Image
* Call-to-action button

Example structure:

```html
<main>

    <section>
        <h1>Welcome to My Website</h1>

        <p>
            This is my first website created using HTML5.
        </p>

        <a href="services.html">Explore Services</a>
    </section>

</main>
```

---

# 👤 5. About Page

Create an About page.

### Include:

* Introduction
* Personal/company information
* Mission
* Vision
* Image

Example:

```html
<section>
    <h1>About Us</h1>

    <p>
        We build modern digital solutions for businesses.
    </p>

    <h2>Our Mission</h2>

    <p>
        To create useful and accessible technology.
    </p>
</section>
```

---

# 💼 6. Services Page

Create a page showing available services.

Example:

```html
<section>
    <h1>Our Services</h1>

    <article>
        <h2>Web Development</h2>
        <p>Building modern websites and web applications.</p>
    </article>

    <article>
        <h2>UI/UX Design</h2>
        <p>Creating user-friendly digital experiences.</p>
    </article>

    <article>
        <h2>Software Development</h2>
        <p>Developing custom software solutions.</p>
    </article>

</section>
```

---

# 📞 7. Contact Page

Create a basic Contact Us page.

### Include:

* Email
* Phone
* Address
* Contact form

Example:

```html
<section>
    <h1>Contact Us</h1>

    <p>Email: hello@example.com</p>
    <p>Phone: +60 12-345 6789</p>

    <form>

        <label for="name">Name</label>
        <input type="text" id="name" name="name">

        <label for="email">Email</label>
        <input type="email" id="email" name="email">

        <label for="message">Message</label>
        <textarea id="message" name="message"></textarea>

        <button type="submit">Send Message</button>

    </form>

</section>
```

> At this stage, the form does **not** need a backend. You will learn how to process forms in a later lesson.

---

# 🖼️ 8. Images

Learn how to add images to your website.

```html
<img
    src="images/profile.jpg"
    alt="Profile photo"
    width="300"
>
```

### Learn:

* `src`
* `alt`
* Image paths
* Relative paths
* Image file organization

### Challenge

Add at least **3 images** to your website.

---

# 🦶 9. Footer

Create a reusable footer.

```html
<footer>

    <p>&copy; 2026 My Website. All rights reserved.</p>

    <a href="contact.html">Contact Us</a>

</footer>
```

Every page should contain a footer.

---

# 📁 10. Project Structure

Your project should look something like this:

```text
lesson-01/
│
├── index.html
├── about.html
├── services.html
├── contact.html
│
├── images/
│   ├── hero.jpg
│   ├── about.jpg
│   └── service.jpg
│
└── README.md
```

---

# 🛠️ Practical Task

## Build: **My First Business Website**

Create a 4-page website for a fictional company.

### Required Pages

```text
Home
│
├── About
├── Services
└── Contact
```

### Required Features

* [ ] HTML5 structure
* [ ] Semantic HTML
* [ ] Navigation bar
* [ ] Home page
* [ ] About page
* [ ] Services page
* [ ] Contact page
* [ ] Contact form
* [ ] Images
* [ ] Footer
* [ ] Working links between pages
* [ ] Meaningful `alt` text for images

---

# 🧪 Challenge

Try to build the website **without copying a complete template**.

You can search for individual concepts such as:

```text
How to create HTML navigation
How to add images in HTML
HTML semantic elements
HTML forms
HTML links
```

But try to write the final code yourself.

---

# ✅ Completion Checklist

Before moving to Lesson 02:

### HTML

* [ ] I understand the basic HTML5 structure.
* [ ] I understand semantic HTML.
* [ ] I can create headings and paragraphs.
* [ ] I can create links.
* [ ] I can add images.
* [ ] I can create forms.

### Website

* [ ] Home works.
* [ ] About works.
* [ ] Services works.
* [ ] Contact works.
* [ ] Navigation works on every page.
* [ ] Footer exists on every page.
* [ ] Images load correctly.
* [ ] No broken links.

### Understanding

* [ ] I know the difference between `<div>` and semantic elements.
* [ ] I understand relative file paths.
* [ ] I understand how multiple HTML pages connect.
* [ ] I can create a website from scratch without a template.

---

# 🧠 Reflection

After completing the lesson, answer these questions:

1. What is HTML?
2. What is the purpose of semantic HTML?
3. What is the difference between `<a>` and `<button>`?
4. Why is the `alt` attribute important?
5. What is the purpose of `<nav>`?
6. What is the difference between `<section>` and `<article>`?
7. How do you link one HTML page to another?
8. What happens when a file path is incorrect?

---

# 🏆 Final Challenge

Create the entire website **from an empty folder**.

Do not use a website template.

The final result should contain:

```text
        MY WEBSITE
─────────────────────────
 Home | About | Services | Contact
─────────────────────────

        Welcome 👋

   [ Hero Image ]

   Discover our services.

      [ Learn More ]

─────────────────────────
 About Us

 Our company...

─────────────────────────
 Our Services

 [ Service 1 ]
 [ Service 2 ]
 [ Service 3 ]

─────────────────────────
 Contact Us

 Name:    [          ]
 Email:   [          ]
 Message: [          ]

          [ Send ]

─────────────────────────
© 2026 My Website
─────────────────────────
```

### 🎓 Skill unlocked

After completing Lesson 01:

**HTML → Website Structure → Multi-Page Website**

Next:

➡️ **Lesson 02 — CSS Fundamentals & Professional Website Styling**
