Frontend Developer Interview Questions

HTML
1. Difference between HTML and HTML5
1️⃣ What is HTML?
HTML (HyperText Markup Language) is the standard language used to create web pages.
Older versions (like HTML 4.01) were mainly used to structure content.

2️⃣ What is HTML5?
HTML5 is the latest version of HTML. It introduced new features like semantic tags, audio/video support, and better form controls.

Doctype Declaration:
In older HTML versions, the doctype declaration was long and complex, whereas HTML5 uses a simple declaration: <!DOCTYPE html>.

Audio and Video Support:
Older HTML versions did not support audio and video directly and required plugins like Flash, whereas HTML5 provides built-in <audio> and <video> tags.

Semantic Tags:
Older HTML did not include semantic tags, while HTML5 introduced semantic elements such as <header>, <footer>, <article>, and <section> to better describe the structure of a webpage.

Graphics Support:
In older HTML, graphics required external plugins, whereas HTML5 supports graphics using <canvas> and SVG.

Storage:
Older HTML mainly used cookies to store data, while HTML5 introduced localStorage and sessionStorage for client-side storage.

Mobile Support:
Older HTML had limited support for mobile devices, whereas HTML5 provides better compatibility and support for modern mobile applications.

Form Controls:
Older HTML had only basic input types, while HTML5 introduced new input types such as email, date, range, and number.

HTML doctype >go to VS code > type ! > give enter

2. What are semantic tags?
Semantic tags are HTML elements that clearly describe the meaning and purpose of the content inside them.
In simple terms, semantic tags tell the browser and developers what the content represents.

Common semantic tags in HTML5 include:

<header> – Defines the top section of a webpage

<nav> – Defines navigation links

<section> – Represents a section of content

<article> – Represents independent content (like a blog post)

<aside> – Defines side content (like a sidebar)

<footer> – Defines the bottom section of a webpage

   <header>
      <h1>Semantic Tags</h1>
      <nav>
         <a href="#">Home</a>
         <a href="#">About</a>
      </nav>
   </header>

   <section>
      <article>
         <h2>Blog post</h2>
        <p>this is a blog post</p>
      </article>
   </section>

   <aside>
      <p>Sidebar content</p>
   </aside>

   <footer>
      <p>Copyright 2023</p>
   </footer>

3. What is the difference between inline and block elements?
   Block elements start on a new line and take the full width of the container, while inline elemenets do not start on a new line and only take the required width for thier content.


4. Difference between localStorage and sessionStorage?

5. What is SVG?
6. What are the audio and video tags in HTML5?
7. What is the location object in HTML?
8. What is a meta tag in HTML?
9. Difference between HTML4 and HTML5
10. What are the attributes of the <img> tag?
11. What is colspan and rowspan in a table?
12. What are the different types of lists in HTML?
13. What is the <progress> element in HTML?

CSS
1. Difference between CSS and CSS3?
2. Difference between position: absolute, relative, and fixed?
3. What is the CSS box model?
4. Difference between LESS and SASS?
5. Difference between class selector and ID selector?
6. What is Flexbox in CSS?
7. What is a flex container and flex items?
8. Difference between visibility: hidden and display: none?
9. What is the float property?
10. Explain the universal selector (*)
11. What is a media query?
12. How to apply media query in CSS?
13. What is the purpose of z-index?
14. Difference between padding and margin?
15. What is box-shadow and text-shadow in CSS?
16. What are media types in CSS (screen, print, all)?

JAVASCRIPT
1. What is ES6?
2. What is the difference between rest and spread operators?
3. What is the event loop?
4. What is event capturing and bubbling?
5. What is event delegation?
6. What is an arrow function?
7. What is the find() method?
8. What is the filter() method?
9. Difference between forEach and for loop?
10. What is the map() function?
11. What is WeakMap and WeakSet?
12. What are Promises?
13. What is setTimeout?
14. What is setInterval?
15. What is a callback function?
16. What is async and await?
17. Difference between var, let, and const?
18. JavaScript data types?
19. What is promise chaining?
20. What is callback hell?
21. Difference between == and ===?
22. What is a closure?
23. What is hoisting in JavaScript?
24. What is the Temporal Dead Zone?
25. Difference between call(), apply(), and bind()?
26. Difference between null and undefined?
27. What is the DOM?
28. What is event delegation?
29. Explain the 'this' keyword in JS
30. Difference between map(), reduce(), and filter() on arrays
31. How is error handling done in JS?
32. How to prevent default behavior in events?
33. List of ES6 features
34. How to find elements in arrays?

ReactJS
1. What is React?
2. What is a Single Page Application (SPA)?
3. What is the Virtual DOM?
4. What are the main features of React?
5. What is state in React?
6. What are props?
7. How to pass values between components?
8. What is a constructor in React class component?
9. What is the use of the super() keyword?
10. What are React events?
11. React Lifecycle methods:
- componentDidMount
- componentWillUnmount
12. How to get previous state value?
13. What is setState() method?
14. What is the use of keys in lists (map)?
15. What is useRef?
16. What is React.memo()?
17. How to handle forms in React (controlled vs uncontrolled)?
18. What is React architecture?
19. What are React Hooks?
- useState
- useEffect
- useMemo
- useContext
- useCallback
- useReducer
- useRef
20. What are custom hooks?
21. What is useNavigate in React Router?
22. What is memory optimization?
23. Difference between useCallback and useMemo?
24. What is useReducer?
25. Difference between class and functional components?
26. What is JSX?
27. What is React Router?
28. How to configure React Router?
29. Conditional rendering in React
30. What is hydration in React?
31. What are React fragments?
32. Difference between controlled and uncontrolled components?
33. Performance optimization in React
34. What is code splitting?
35. What is lazy loading?
36. What is type checking in React (PropTypes)?
37. How to reuse code in React?
38. What is React diffing algorithm?
39. How to pass data between components?
40. What is state management in React?
41. What are synthetic events?
42. How to handle errors in React?
43. What are PropTypes?
44. What is StrictMode in React?
45. What are error boundaries?
46. How to reduce bundle size?
47. How to optimize performance in React?
48. How to set up a React app?
49. What is the use of the <Link> component?
50. What is Axios?