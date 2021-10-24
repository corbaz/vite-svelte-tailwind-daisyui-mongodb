# Svelte + TS + Vite

```cmd
C:\www\__Svelte>npm init vite@latest vite-svelte-ts-tailwind -- --template svelte-ts
Need to install the following packages:
  create-vite@latest
Ok to proceed? (y) y

Scaffolding project in C:\www\__Svelte\vite-svelte-ts-tailwind...

Done. Now run:

  cd vite-svelte-ts-tailwind
  npm install
  npm run dev
  
  
C:\www\__Svelte\vite-svelte-ts-tailwind>ncu
Checking C:\www\__Svelte\vite-svelte-ts-tailwind\package.json
[====================] 8/8 100%

@sveltejs/vite-plugin-svelte  ^1.0.0-next.11  →  ^1.0.0-next.30
svelte                               ^3.37.0  →         ^3.44.0
svelte-check                          ^2.1.0  →          ^2.2.7
svelte-preprocess                     ^4.7.2  →          ^4.9.8
tslib                                 ^2.2.0  →          ^2.3.1
typescript                            ^4.3.2  →          ^4.4.4
vite                                  ^2.6.4  →         ^2.6.10

Run ncu -u to upgrade package.json


#Setting up Tailwind CSS
Tailwind CSS requires Node.js 12.13.0 or higher.

##Install Tailwind via npm
Install Tailwind and its peer-dependencies using npm:

npm install -D tailwindcss@latest postcss@latest autoprefixer@latest


##Create your configuration files
Next, generate your tailwind.config.js and postcss.config.js files:

npx tailwindcss init -p

```

```cmd
Quick setup — if you’ve done this kind of thing before
or	
https://github.com/corbaz/vite-svelte-tailwind-daisyui-mongodb.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# svelte-tailwind-mongodb" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/corbaz/svelte-tailwind-mongodb.git
git push -u origin main
...
