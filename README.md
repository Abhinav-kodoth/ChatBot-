# ChatBot – using React 

A simple chatbot built using **React as an external library**, without Vite to understand how React works when added directly inside an HTML file.



## The goal was to learn: 

- How React loads and runs directly in the browser  
- How to embed React components inside a standard HTML file  
- How JSX is compiled using `babel-standalone`  
- How ReactDOM renders components into simple DOM containers  
- How state is handled using `useState()` inside a pure CDN setup 


##  Personal Learning

This project helped me understand the **foundations** of React by removing all abstraction layers.  
Key learning takeaways:

- Learned how React works without tools like Vite, CRA
- Understood the role of CDN scripts (`react.js`, `babel.js`)  
- Manually controlled the structure of the app inside `<script type="text/babel">`  
- Deepened understanding of JSX compilation and how it translates to JS  

## Scope of Improvement

###  **1.Use a Proper Build Tool**
- Eventually migrate to Vite or React CRA  
- Learn about ES Modules and hot reloading  
- Build a scalable file structure

### **2. Real Chatbot Logic**
- Replace the placeholder response system  
- Integrate an actual NLP model or API  
