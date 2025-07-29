## how to install tailwind in ur Visual studio 
## Step 1 
initialize npm project by pasting
npm init -y
## STEP 2:-install Tailwind css version 4 by
npm install tailwindcss @tailwindcss/cli
## Step 3:- 
create a folder named as src
## Step 4
create a file in src named as input.css and paste inside the file
@import "tailwindcss";
## Step 5
Paste this in terminal and enter
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
## STEp 6
create an html file in same src folder
## Step 7
congrats now u can use tailwind in ur vs code
## Step 7 
make sure to donwload tailwind extension in vs code