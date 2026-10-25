When a user types a URL into the browser (the client), the browser first asks a DNS server to translate the domain name into the IP address of the web server. It then sends an HTTP or HTTPS request to that server. HTTP (HyperText Transfer Protocol) is the set of rules for transferring web data, and HTTPS (HyperText Transfer Protocol Secure) is its secure version, which encrypts the data using SSL/TLS. The server receives the request and processes it. If the site needs stored information such as user accounts or products, the server queries the database, which stores and returns the data. The server then sends a response containing HTML, CSS, JavaScript, images, and a status code (such as 200 OK) back to the browser. The browser reads this response and renders it as the web page on the screen. This whole process is called the request-response cycle. A static website shows the same fixed content to every user, because its pages are pre-built HTML files and it needs no database. A dynamic website generates content on the server at the time of the request, using a database, so the content can change per user, as on social media or online shopping sites.

**Screenshot steps (Network tab):**
1. Open any website in Chrome (e.g., google.com).
2. Press F12 (or right-click → Inspect) to open DevTools.
3. Click the **Network** tab.
4. Reload the page (Ctrl+R) so the requests appear.
5. Take a screenshot showing the list of requests, including the Status and Type columns, and paste it into your submission.
