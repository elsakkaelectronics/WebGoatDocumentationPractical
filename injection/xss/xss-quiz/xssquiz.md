<h1>xss quiz</h1>
<img src='https://i.postimg.cc/HkFLTgZ9/Screenshot-2026-08-05-173150.png'>

### 1. Is a well-known website, like Netflix, immune to XSS attacks?
✅ **Correct Answer: Solution 4**  
Even trusted websites can be vulnerable. Browsers don’t inherently know if a script is malicious — they just execute what the site delivers. That’s why XSS can affect even big names.

---

### 2. When do XSS attacks occur?
✅ **Correct Answer: Solution 3**  
XSS happens when a site fails to properly validate or sanitize user input, allowing malicious scripts to run in the victim’s browser.

---

### 3. What are Stored XSS attacks?
✅ **Correct Answer: Solution 1**  
Stored XSS means the malicious script is permanently saved on the server (e.g., in a database or comment field). Every time a user requests that data, the script executes in their browser.

---

### 4. What are Reflected XSS attacks?
✅ **Correct Answer: Solution 2**  
Reflected XSS occurs when malicious input is immediately “reflected” back in the server’s response (like in a search result or error message), causing the script to execute in the victim’s browser.

---

### 5. Is JavaScript the only way to perform XSS attacks?
✅ **Correct Answer: Solution 4**  
No — while JavaScript is the most common, XSS can also exploit other executable content like HTML, Flash, or any code the browser interprets.
