# INFR3120U - Assignment 1: Portfolio Site
* Student Name: Musawer Beissed
* Student Email: AbdulMusawer.Beissed@ontariotechu.net
* GitHub Repo: https://github.com/Musawer0/INFR3120U-Assignment1
* Live Site: https://Musawer0.github.io/INFR3120U-Assignment1/

---

## 1. Viewport Dimensions and Media Queries
Everything is structured using floated divs and clear classes. I used three separate CSS files linked with media queries:

* Laptop / Desktop (`laptop.css` - `min-width: 961px`): 
  Uses a fixed 960px width wrapper centered on the screen with margin auto. The main content is floated to the left and the aside highlights box is floated to the right to make use of wider screens.
* Tablet (`tablet.css` - `min-width: 481px and max-width: 960px`): 
  Uses a fluid wrapper set to 92% width so it fits mid-sized screens. I removed the side-by-side floats so the columns stack vertically, and made the nav links wider (25% width) so they are easier to tap.
* Mobile (`phone.css` - `max-width: 480px`): 
  The wrapper is set to 100% width with no margins. The navigation links stack vertically into full-width block buttons so they work better on touchscreens.

## 2. Gradients Used
I used both linear and angled gradients with vendor prefixes for browser support:
* Linear Gradient (top to bottom): Applied to the `#banner` header across the pages. It blends from dark navy `#121926` down to `#1f2c40`.
* Angled Linear Gradient (45deg): Applied to the project boxes (`.project-box`) on the projects page and the highlights sidebar box on the homepage to give them a slight diagonal highlight.

## 3. Adobe Color Scheme
I generated a dark minimal color scheme on Adobe Color using these 5 hex values:
* `#0E131F` - Dark background color for the body
* `#1A2232` - Container color for the main wrapper
* `#00ADB5` - Accent teal for headings, link hovers, and active borders
* `#6B7A8F` - Slate gray for borders, captions, and footer text
* `#F4F6F9` - Light text color for high contrast and readability

## 4. Pages and Features
* `index.html`: Home page introducing my background in Networking & IT Security.
* `about.html`: Bio info, profile picture with figcaption, and HTML5 video player with controls and poster.
* `projects.html`: 5 technical lab projects from my networking courses at Ontario Tech.
* `contact.html`: Contact form with HTML5 validations (name, email, phone, message) and a simple anti-bot math check.