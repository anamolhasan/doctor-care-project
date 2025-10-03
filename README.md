# html-css-js-crash-course-doctor-care-project
![html-css-js-crash-course-doctor-care-project](./images/github-cover.png)



# Tailwind PostCSS  install
### 1
```bash
   npm init -y
```
### 2
```bash
npm install tailwindcss @tailwindcss/postcss postcss vite
```
### 3 
do you create   ``` postcss.config.mjs ``` 
```bash
export default {
  plugins: {
    "@tailwindcss/postcss": {},
  }
}
```
### 4
``` css/style.css ```
``` @import "tailwindcss"; ```

### 5 added in html file 
```   <link href="./css/style.css" rel="stylesheet">  ```
### 5 
package.json
```bash
 "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  ```
  ``` npm run dev ```
  