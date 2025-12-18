#Tailwind css CLI

<h1>Website</h1>
1.copy -  npm install tailwindcss @tailwindcss/cli

<h1>VS code</h1>
1. open terminal
2. paste cmd
3. enter
4. create index.html and input.css
5. open package.json 
6. copy - npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch  from tailwind website
    write into package.json  "scripts": {
    "start": "npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch"                
  }
  remove src from link
7. open input.css
    write @import "tailwindcss";
8. open index.html
    write  <link rel="stylesheet" href="output.css">
9. open terminal 
    write npm run start 

git - repo create
git  clone <link>
git add . / git add index.html
git commit -m "msg"
git push origin main

