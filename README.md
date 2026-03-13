# Ex09 Event Registration Web Application
## Date:13/03/2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
## frames:
### html:
```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="node-1">
<img src="images/node-2.png" class="node-2" alt="pexels-pixabay-46798-2" />
<div class="node-3">
<p class="text-4"><span class="text-rgb-153-153-153">SPORTS DAY EVENT</span></p>
</div>
<div class="style-primary-container-segments-3">
<div class="menu-6">
<div class="state-enabled">
<div class="state-layer-8">
<div class="stars-filled">
<img src="images/icon-10.svg" class="icon-10" alt="icon" />
</div>
<p class="text-11"><span class="text-rgb-79-55-138">REGISTER</span></p>
</div>
</div>
<div class="state-enabled">
<div class="state-layer-13">
<div class="stars-filled">
<img src="images/icon-15.svg" class="icon-15" alt="icon" />
</div>
<p class="text-16"><span class="text-rgb-79-55-138">SIGN IN</span></p>
</div>
</div>
</div>
<div class="state-enabled">
<div class="state-layer-18">
<div class="close">
<img src="images/icon-20.svg" class="icon-20" alt="icon" />
</div>
</div>
</div>
</div>
<div class="dots-2-selection-1">
<div class="frame-22">
<div class="dot-1-23"></div>
<div class="dot-2-24"></div>
</div>
</div>
<div class="node-25">
<div class="left-26">
<p class="text-27"><span class="text-black">9:41</span></p>
<p class="text-28"><span class="text-black">Tue Apr 1</span></p>
</div>
<div class="right-29">
<img src="images/combined-shape-30.svg" class="combined-shape-30" alt="combined-shape" />
<img src="images/combined-shape-31.svg" class="combined-shape-31" alt="combined-shape" />
<p class="text-32"><span class="text-black">100%</span></p>
<div class="battery-icon-33">
<img src="images/combined-shape-34.svg" class="combined-shape-34" alt="combined-shape" />
<div class="capacity-35"></div>
</div>
</div>
</div>
</div>

</body>
</html>

```
```css
/* Add font files for SF Pro */
@font-face {
  font-family: 'SF Pro';
  src: url('fonts/sf-pro.woff2') format('woff2'),
       url('fonts/sf-pro.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Tillana */
@font-face {
  font-family: 'Tillana';
  src: url('fonts/tillana.woff2') format('woff2'),
       url('fonts/tillana.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Rubik Wet Paint */
@font-face {
  font-family: 'Rubik Wet Paint';
  src: url('fonts/rubik-wet-paint.woff2') format('woff2'),
       url('fonts/rubik-wet-paint.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Zen Antique Soft */
@font-face {
  font-family: 'Zen Antique Soft';
  src: url('fonts/zen-antique-soft.woff2') format('woff2'),
       url('fonts/zen-antique-soft.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Work Sans */
@font-face {
  font-family: 'Work Sans';
  src: url('fonts/work-sans.woff2') format('woff2'),
       url('fonts/work-sans.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

:root {
  --font-family-sf-pro: 'SF Pro', sans-serif;
  --font-family-roboto: 'Roboto', sans-serif;
  --font-family-tillana: 'Tillana', sans-serif;
  --font-family-rubik-wet-paint: 'Rubik Wet Paint', sans-serif;
  --font-family-zen-antique-soft: 'Zen Antique Soft', sans-serif;
  --font-family-work-sans: 'Work Sans', sans-serif;
  --text-rgb-153-153-153: rgba(153, 153, 153, 1);
  --text-rgb-79-55-138: rgba(79, 55, 138, 1);
  --text-black: rgba(0, 0, 0, 1);
  --text-rgb-0-20-23: rgba(0, 20, 23, 1);
  --text-rgb-215-255-15: rgba(215, 255, 15, 1);
  --text-rgb-82-74-74: rgba(82, 74, 74, 1);
  --text-rgb-29-27-32: rgba(29, 27, 32, 1);
  --text-rgb-26-26-26: rgba(26, 26, 26, 1);
}

.text-rgb-153-153-153 {
  color: var(--text-rgb-153-153-153);
}

.text-rgb-79-55-138 {
  color: var(--text-rgb-79-55-138);
}

.text-black {
  color: var(--text-black);
}

.text-rgb-0-20-23 {
  color: var(--text-rgb-0-20-23);
}

.text-rgb-215-255-15 {
  color: var(--text-rgb-215-255-15);
}

.text-rgb-82-74-74 {
  color: var(--text-rgb-82-74-74);
}

.text-rgb-29-27-32 {
  color: var(--text-rgb-29-27-32);
}

.text-rgb-26-26-26 {
  color: var(--text-rgb-26-26-26);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  backdrop-filter: blur(40px);
  mix-blend-mode: linear_dodge;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: normal;
  font-size: 50px;
  letter-spacing: -0.20000000298023224px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-153-153-153);
}

.node-3 {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  backdrop-filter: blur(20px);
}

.icon-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(79, 55, 138, 1);
  border: none;
  outline: none;
}

.stars-filled {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: right;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.state-layer-8 {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  gap: 8px;
  padding: 16px 24px 16px 24px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(234, 221, 255, 1);
}

.state-enabled {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-end;
  gap: 4px;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
  border-radius: 28px;
}

.icon-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(79, 55, 138, 1);
  border: none;
  outline: none;
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: right;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.state-layer-13 {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  gap: 8px;
  padding: 16px 24px 16px 24px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(234, 221, 255, 1);
}

.menu-6 {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;
  gap: 4px;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.icon-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.close {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.state-layer-18 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.style-primary-container-segments-3 {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;
  gap: 8px;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.dot-1-23 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
}

.dot-2-24 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
  opacity: 0.30000001192092896;
}

.frame-22 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 8px 12px 8px 12px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 50px;
}

.dots-2-selection-1 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-27 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-28 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.left-26 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  padding: 2px 0px 2px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.combined-shape-30 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.combined-shape-31 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.text-32 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: right;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  line-height: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.combined-shape-34 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  opacity: 0.4000000059604645;
  border: none;
  outline: none;
}

.capacity-35 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 1.5px;
}

.battery-icon-33 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.right-29 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 4px;
  padding: 5px 0px 5px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-25 {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  gap: 966px;
  padding: 4px 26px 4px 26px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.node-1 {
@media (max-width: 1440px) {
  .node-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .node-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  opacity: 0.75;
}

.node-37 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.mode-light {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 136, 255, 1);
  border-radius: 1px;
  opacity: 0.25;
  mix-blend-mode: multiply;
}

.node-41 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 136, 255, 1);
  border-radius: 2px;
}

.node-42 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 3px 14px 6px rgba(0,0,0,0.5);
  fill: rgba(0, 136, 255, 1);
  border: none;
  outline: none;
}

.lollipop-trailing-40 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-44 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 136, 255, 1);
  border-radius: 2px;
}

.lollipop-leading-pop-45 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 3px 14px 6px rgba(0,0,0,0.5);
  fill: rgba(0, 136, 255, 1);
  border: none;
  outline: none;
}

.lollipop-leading-43 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-selection {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.5;
}

.text-46 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-tillana);
  font-weight: normal;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-0-20-23);
}

.text-47 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.8999999761581421;
  text-align: center;
  font-family: var(--font-family-rubik-wet-paint);
  font-weight: normal;
  font-size: 40px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-215-255-15);
}

.resize-grabber-50 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 3px solid rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.window-resize {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.window {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 20px 76px 0px rgba(0,0,0,0.5);
  background-color: rgba(255, 255, 255, 1);
  border-radius: 34px;
  opacity: 0.25;
}

.text-51 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-zen-antique-soft);
  font-weight: normal;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-52 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-work-sans);
  font-weight: normal;
  font-size: 22px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.dot-1-55 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
}

.dot-2-56 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
  opacity: 0.30000001192092896;
}

.frame-54 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 8px 12px 8px 12px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 50px;
}

.text-59 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-60 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.left-58 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  padding: 2px 0px 2px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.combined-shape-62 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.combined-shape-63 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.text-64 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: right;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  line-height: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.combined-shape-66 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  opacity: 0.4000000059604645;
  border: none;
  outline: none;
}

.capacity-67 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 1.5px;
}

.battery-icon-65 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.right-61 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 4px;
  padding: 5px 0px 5px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-36 {
@media (max-width: 1440px) {
  .node-36 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .node-36 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  opacity: 0.75;
}

.node-69 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.resize-grabber-72 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 3px solid rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.rectangle-73 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-74 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.rectangle-75 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.text-76 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-2-77 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.text-78 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-3-79 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.text-80 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-4-81 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

.content-84 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 100px;
}

.configuration-floating-orientation-horizontal-type {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 4px;
  padding: 12px 8px 12px 8px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 35.50561797752809%;
  box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.5), 0px 4px 8px 3px rgba(0,0,0,0.5);
}

.text-85 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-86 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-87 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-88 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-89 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 20px;
  letter-spacing: 1%;
  line-height: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-82-74-74);
}

.dot-1-92 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
}

.dot-2-93 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
  opacity: 0.30000001192092896;
}

.frame-91 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 8px 12px 8px 12px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 50px;
}

.text-96 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-97 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.left-95 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  padding: 2px 0px 2px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.combined-shape-99 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.combined-shape-100 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.text-101 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: right;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  line-height: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.combined-shape-103 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  opacity: 0.4000000059604645;
  border: none;
  outline: none;
}

.capacity-104 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 1.5px;
}

.battery-icon-102 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.right-98 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 4px;
  padding: 5px 0px 5px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.node-68 {
@media (max-width: 1440px) {
  .node-68 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .node-68 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  opacity: 0.75;
}

.node-106 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.resize-grabber-109 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 3px solid rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.building-blocks-state-layer-1-enabled {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-115 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-114 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 75%;
}

.trailing-element-116 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 10px;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.state-layer-113 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.condition-1-line-leading-monogram-trailing-check-b {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  min-height: 48px;
}

.text-121 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-120 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 75%;
}

.trailing-element-122 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 10px;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.state-layer-119 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-127 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-126 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 75%;
}

.trailing-element-128 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 10px;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.state-layer-125 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-133 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-132 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 91.30434782608695%;
}

.state-layer-131 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.leading-element-137 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-139 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-138 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-136 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-145 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.node-144 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(234, 221, 255, 1);
  border-radius: 100px;
}

.leading-element-143 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-147 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-146 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-142 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-153 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-151 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-155 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-154 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-150 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-161 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-159 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-163 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-162 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-158 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-169 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-167 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-171 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-170 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-166 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-177 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-175 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-179 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-178 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-174 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-185 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-183 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-187 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-roboto);
  font-weight: normal;
  font-size: 16px;
  letter-spacing: 0.5px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-29-27-32);
}

.content-186 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 1;
  flex-shrink: 1;
  width: 76.08695652173914%;
}

.state-layer-182 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 16px;
  padding: 4px 16px 4px 16px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.node-110 {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-190 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-188 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-193 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-191 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-196 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-194 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-199 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-197 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-202 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-roboto);
  font-weight: 500;
  font-size: 16px;
  letter-spacing: 0.15000000596046448px;
  line-height: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-79-55-138);
}

.leading-element-200 {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  padding: 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-203 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: normal;
  font-size: 32px;
  letter-spacing: -0.20000000298023224px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.dot-1-206 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
}

.dot-2-207 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 50px;
  opacity: 0.30000001192092896;
}

.frame-205 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 8px;
  padding: 8px 12px 8px 12px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 50px;
}

.text-210 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-211 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.left-209 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 8px;
  padding: 2px 0px 2px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.combined-shape-213 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.combined-shape-214 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  fill: rgba(0, 0, 0, 1);
  border: none;
  outline: none;
}

.text-215 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: right;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 12px;
  line-height: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.combined-shape-217 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border: 1px solid rgba(0, 0, 0, 1);
  opacity: 0.4000000059604645;
  border: none;
  outline: none;
}

.capacity-218 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 1);
  border-radius: 1.5px;
}

.battery-icon-216 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.right-212 {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  gap: 4px;
  padding: 5px 0px 5px 0px;
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.fill-shadow-221 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 8px 40px 0px rgba(0,0,0,0.5);
  background-color: rgba(219, 191, 238, 1);
  border-radius: 296px;
}

.glass-effect-222 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(0, 0, 0, 0.004000000189989805);
  border-radius: 296px;
}

.mode-light-state-default {
  flex-grow: 0;
  flex-shrink: 1;
  width: 100%;
}

.text-224 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  mix-blend-mode: linear_burn;
  text-align: center;
  font-family: var(--font-family-sf-pro);
  font-weight: 500;
  font-size: 17px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-26-26-26);
}

.node-219 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 4px;
  padding: 6px 20px 6px 20px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 35.50561797752809%;
  border-radius: 1000px;
}

.node-105 {
@media (max-width: 1440px) {
  .node-105 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .node-105 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 20px;
  opacity: 0.75;
}

```


## OUTPUT:
![alt text](<Screenshot 2026-03-13 105241.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
