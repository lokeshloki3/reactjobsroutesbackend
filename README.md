# React + Vite

Steps to run program in VS Code - 

npm create vite@latest reactjobs

React

JavaScript

cd reactjobs
code .

npm install
npm run dev

vite.config.js -
plugins: [react()],
	server: {
	port: 3000,
}

install Tailwind PostCSS method

Console Ninja Extension

Font awesome -
	npm i react-icons

Separate Pages (Framwork) - (Separate Pages cannot formed using Libraries i.e. above)
	npm i react-router-dom
	
Jason server - (Install again if copy to other folder)
	npm install -D json-server
	Add in script of package.json - "server" : "json-server --watch src/jobs.json --port 8000"
	npm run server
	
Spinners -
	npm i react-spinners
	
Add proxy in vite.config -
	    proxy: {
      '/api': {
        target: 'http://localhost:8000',
        changeOrigin: true,
        rewrite: (path) => path.replace(/^\/api/, ''),
      }


Toastify - npm i react-toastify

npm run build

npm run preview in other terminal
