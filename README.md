Frontend Developer Interview Questions

HTML
1. Difference between HTML and HTML5
1️⃣ What is HTML?
HTML (HyperText Markup Language) is the standard language used to create web pages.
HTML Older versions (like 4.01) were mainly used to structure the content.

2️⃣ What is HTML5?
HTML5 is the latest version of HTML. It introduced new features like semantic tags, audio/video support, and better form controls.

Doctype Declaration:
In older HTML versions, the doctype declaration was long and complex, whereas HTML5 uses a simple declaration: <!DOCTYPE html>.

Audio and Video Support:
Older HTML versions did not support audio and video directly and required plugins like Flash, whereas HTML5 provides built-in <audio> and <video> tags.

Semantic Tags:
Older HTML did not include semantic tags, while HTML5 introduced semantic elements such as <header>, <footer>, <article>, and <section> to describe better structure of a webpage.

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
   localStorage and sessionStorage are both used to store data in the browser as key-value pairs. The main difference is localStorage stores data permanently until it is manually cleared, even after closing the browser. sessionStorage stores data only for the current session, meaning once the tab or browser is closed, the data wil be removed. 

5. What is SVG?
   SVG stands for Scalable Vector Graphics. It is used to display images in XML format. Unlike normal images like JPEG or PNG, SVG images do not lose quality when resized because they are based on mathematical shapes rather than pixels. SVG is widely used for icons, logos, and animations in web applications, and it can also be styled and manipulated using CSS and JavaScript.

6. What are the audio and video tags in HTML5?
   In HTML5, the <audio> and <video> tags are used to embed media directly into web pages without needing external plugins. The audio tag is used to play sound files, and the video tag is used for videos. Both support attributes like controls, autoplay, and loop. These tags make multimedia integration easy and are supported by modern browsers.

7. What is the location object in HTML?
•	The location object is part of the window object in JavaScript and is used to get or manipulate the current URL of the browser. It provides properties like href, hostname, pathname, and methods like reload () and assign (). Developers use it for redirection, navigation, and retrieving URL information dynamically.

8. What is a meta tag in HTML?
•	Meta tags are used to provide metadata about a webpage, such as character encoding, description, keywords, and viewport settings. These tags are placed inside the head section and are not visible on the webpage. They are important for SEO and browser behaviour, like defining how content should be displayed on mobile devices.

9. Difference between HTML4 and HTML5
•	HTML5 is an improved version of HTML4 with better support for modern web applications. It introduced semantic elements like header, footer, and section, which improve readability and SEO. It also supports multimedia elements like audio and video without plugins. HTML5 includes APIs like Geolocation and Canvas, making it more powerful and efficient than HTML4.

10. What are the attributes of the <img> tag?  The <img> tag is used to display images in HTML. Important attributes include src, which defines the image path, alt, which provides alternative text for accessibility, and width and height, which control image size. The alt attribute is especially important for screen readers and SEO.

11. What is colspan and rowspan in a table?
•	In HTML tables, colspan and rowspan are used to merge cells. Colspan is used to merge multiple columns into a single cell, while rowspan is used to merge rows. These attributes help in designing complex table layouts and improving readability.

12. What are the different types of lists in HTML?
•	HTML supports three types of lists: ordered lists using <ol>, unordered lists using <ul>, and description lists using <dl>. Ordered lists display items in numbered format, unordered lists use bullets, and description lists are used for defining terms and descriptions.

13. What is the <progress> element in HTML?
•	The <progress> element represents the progress of a task, such as file upload or loading status. It has attributes like value and max to indicate completion percentage. It improves user experience by visually showing progress.


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


1. What is HTML?

HTML (HyperText Markup Language) is used to structure web pages using elements like headings, paragraphs, and links.

2. What are semantic tags?

Tags that clearly define meaning (e.g., <header>, <footer>, <article>).

3. Difference between HTML and HTML5?

HTML5 supports audio/video, semantic tags, localStorage, and better APIs.

4. What is SVG?

SVG (Scalable Vector Graphics) is used to display vector images that scale without losing quality.

5. What is a meta tag?

Provides metadata like description, charset, viewport.

🎨 CSS (6–10)
6. Difference between class and id?

Class → reusable

ID → unique

7. What is Flexbox?

Layout system for arranging items in rows/columns.

8. What is Grid?

2D layout system (rows + columns).

9. What is responsive design?

Design that adapts to different screen sizes.

10. What is z-index?

Controls stacking order of elements.

⚡ JavaScript (11–20)
11. What is closure?

Function that remembers its outer variables even after execution.

12. Difference between var, let, const?

var → function scope

let → block scope

const → cannot reassign

13. What is hoisting?

Variables/functions are moved to top during compilation.

14. What is event loop?

Handles async operations in JS.

15. What is promise?

Object representing future completion/failure of async task.

16. async/await?

Cleaner way to handle promises.

17. Difference between == and ===?

== → loose comparison

=== → strict comparison

18. What is DOM?

Document Object Model – represents HTML structure.

19. What is debounce?

Delays function execution to reduce calls.

20. What is throttle?

Limits function execution rate.

⚛️ React (21–30)
21. What is React?

JavaScript library for building UI.

22. What is component?

Reusable UI block.

23. What are props?

Data passed from parent to child.

24. What is state?

Data managed within component.

25. What is useEffect?

Hook used for side effects (API calls, etc.).

26. What is useState?

Hook to manage state.

27. Virtual DOM?

Lightweight copy of real DOM for faster updates.

28. What is key in React?

Unique identifier for list elements.

29. Controlled vs uncontrolled components?

Controlled → React controls input

Uncontrolled → DOM controls

30. What is React Router?

Used for navigation between pages.

⚙️ Backend (Node.js / Express) (31–40)
31. What is Node.js?

JavaScript runtime for server-side development.

32. What is Express.js?

Framework for building APIs in Node.js.

33. What is middleware?

Function between request & response.

34. What is REST API?

API using HTTP methods (GET, POST, etc.).

35. Difference between GET and POST?

GET → fetch data

POST → send data

36. What is JSON?

Data format for storing/transferring data.

37. What is JWT?

Token-based authentication system.

38. What is CORS?

Allows/restricts cross-origin requests.

39. What is status code?

Response code (200, 404, 500, etc.).

40. What is API?

Interface for communication between systems.

🗄️ Database (41–45)
41. What is SQL?

Structured Query Language for relational DB.

42. What is primary key?

Unique identifier in a table.

43. What is join?

Combines data from multiple tables.

44. Difference between SQL and NoSQL?

SQL → structured

NoSQL → flexible

45. What is CRUD?

Create, Read, Update, Delete.

🔧 Misc / Full Stack (46–50)
46. What is Git?

Version control system.

47. What is GitHub?

Platform to host Git repositories.

48. What is MVC?

Model-View-Controller architecture.

49. What is authentication vs authorization?

Authentication → who you are

Authorization → what you can access

50. Explain your project

Explain:

Purpose

Tech stack

Features

Challenges