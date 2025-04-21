{

npm install -D tailwindcss@3
npx tailwindcss init
intsall it

install krne ke baad tailwindconfig.css ka ek file a jayega aur usme
content me humko woh options dalne hai jo woh file ko read kar sake 
(html,cs,js)

uske baad ek folder bana na hai jiska name src hoga uske andr input.css ka file bana na hai taki files ko access mil sake 

src -> input.css

fir woh file ke andr yeh paste krna hai

@tailwind base;
@tailwind components;
@tailwind utilities;

uske baad terminal me prompt dalna hai taki woh watch kar skae yeh run krne ke baad automatically output.css ayega

npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

last me index.html me css link krna hai  output.css me 

  <link rel="stylesheet" href="src/output.css">

}


