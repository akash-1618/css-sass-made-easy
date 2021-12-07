# css-sass-made-easy
Steps to install sass : (Open powershell terminal in the project folder) 
1. npm -v 
2. npm init -y 
3. npm install sass --save-dev 
4. Create folder src -> scss. Inside scss, create main.scss file. Write<br> `$red :red; body { background: $red; }` to test it.
5. sass --watch src/scss:dist/css
6. npm install -g sass (Only do this step if step 5 deosn't work. Installs sass globally. If step 6 doesn't work, open powershell with admin rights or work in cmd prompt in folder location and perform from step 5.) 
7. Delete dist folder completely.
8. npm install parcel-bundler --save-dev or npm install parcel-bundler -D
9. package.json -> <br> `"scripts": { "dev": "parcel src/index.html", "build": "parcel build sc/index.html" }`
10. npm run dev(for testing purposes(faster)) or npm run build(before deployment; optimises(slower))!

<br>These are starter files for sass installation<br>
# Sass starter using Parcel
### Created using Windows OS. May give problems for Unix or Mac OS. [Reference](https://stackoverflow.com/questions/5834014/lf-will-be-replaced-by-crlf-in-git-what-is-that-and-is-it-important)
<br><br>How to use this repo?
1. Clone the repo
2. In your terminal, run npm install
3. In your terminal, run npm run dev

When you are ready to go to production
In your terminal, run npm run build. The final version of your site will be in the dist folder.

[Reference](https://www.youtube.com/watch?v=wYWf2m_yzBQ&list=PL4-IK0AVhVjMYRhK9vRPatSlb-9r0aKgh&index=1)
