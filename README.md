# css-sass-made-easy
Steps to install sass : (Open powershell terminal in the project folder) 
1. npm -v 
2. npm init -y 
3. npm install sass --save-dev 
4. Create folder src -> scss. Inside scss, create main.scss file. Write<br> `$red :red; body { background: $red; }` to test it.
5. sass --watch src/scss:dist/css
6. npm install -g sass (Only do this step if step 5 deosn't works. Installs sass globally. If step 6 doesn't work, open powershell with admin rights or work in cmd prompt in folder location and perform from step 5.) 
7. Delete dist folder completely.
8. npm install parcel-bundler --save-dev or npm install parcel-bundler -D
9. package.json -> <br> `"scripts": { "dev": "parcel src/index.html", "build": "parcel build sc/index.html" }`
10. npm run dev(for testing purposes(faster)) or npm run build(before deployment; optimises(slower))![image](https://user-images.githubusercontent.com/43025153/126164140-8b0c7c18-b6ff-4cc3-898a-e3cb75727a2a.png)
