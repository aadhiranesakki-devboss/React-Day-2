# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


Steps to create React Project

1. Select the parent folder and open cmd
2. Give command npm create vite project-name
3. Select React -> Javascript
4. Give command cd project-folder
5. npm install to install react and react-dom package to your project
6. give npm run dev and launch the url in browser
7. Delete App.css
8. Clear Index.css
9. Clear App.jsx and just get the boiler plate code using rfce shortcut
10. Continue building the project


Steps to convert html to JSX
1. Comments are different html <!-- Page Heading --> jsx {/* <!-- Page Heading --> */}
2. All self clossing tag should have closing tag eg. <img></img> or <img/>
3. class should be changed to className
4. Add the bootstrap cdn link to the head of index.html


Steps to Deploy in Netlify
1. Login to Netlify
2. Create a new website using github
3. Select your repository
4. Select your branch if needed
5. No changes in the commands
6. Give Deploy and see the logs
7. Once completed you can open the url. 
8. If there is any errors rectify and repeat the process.