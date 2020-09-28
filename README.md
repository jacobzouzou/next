********************************************************************************
Next.js
********************************************************************************
server side render: called also "static pre-rendering"
SEO (Search Engine Optimization) issue for indexing content in client mode

Install
1 create project folder
2 install: npm install next react react-dom
3 create "pages" folder in project folder
4 add package.json with :
  {
    "scripts":{
      "dev":"next"
    }
  }
5 run next: npm run dev

Static site hosts: Netlify, Firebase hosting,...
process require to declare urls that compose the site 

Deployment: 
npm run build
npm run start
