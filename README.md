# puppeteer-crawler
A light weight distributed crawler using headless chrome with puppeteer, rabbitmq and mongodb.

## Why Puppeteer?
Modern websites use ReactJS, VueJS, AngularJS and other front-end frameworks and libraries, the static web pages usually have nothing but an empty entry point. Everything meaningful is rendered by JavasScript code which fetch data from server side API. Poor old crawler/spider frameworks like apache nutch and scrapy couldn't handle this new style websites without extensions.  
  
Commercial crawlers usually leverage WebKit and JS engine to scrape these websites, whiling still using constructed HTTP requests and HTML parser for other websites, to get higher performance.  
  
Google released Chrome DevTools API and Puppeteer, which provide a more covinient way to manipulate modern full-featured web browser programmably. For most of vertical crawlers, the performance lost is not the most important thing, so I made this crawler by using Puppeteer as mandatory, to make it less complicated.  
  
