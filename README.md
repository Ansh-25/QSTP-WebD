#### Mobile responsive Portfolio Website using Tailwind CSS.  
preview the site at [link](https://ansh-25.github.io/QSTP-WebD/)

###### For setting up tailwind css

run command 
```
npm init -y
npm install -D tailwindcss postcss autoprefixer vite
npx tailwindcss init -p
```
add `"start": "vite"` in scripts of `package.json`  
add "*" in content of `tailwind.config.js`
link input.css file in html and write the following in input.css:   
```
    @tailwind base;  
    @tailwind components;
    @tailwind utilities;
```
