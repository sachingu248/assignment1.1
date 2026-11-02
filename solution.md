Assignment 1.1 — How a Website Works

When a user types a URL (Uniform Resource Locator) into a web browser like Google Chrome, the browser acts as a client and sends a request to the web server using HTTP (HyperText Transfer Protocol) or HTTPS (HyperText Transfer Protocol Secure). HTTPS is the secure version of HTTP that encrypts communication between the browser and server. First, the browser finds the server's IP address using DNS (Domain Name System). Then, it sends an HTTP/HTTPS request to the server. The server processes the request and may communicate with a database to retrieve or store information. After processing, the server sends an HTTP response containing the requested data, such as HTML, CSS, JavaScript, and images. The browser receives these files and displays the website on the screen. This process is called the request-response cycle. A static website displays fixed content that usually remains the same for every visitor, whereas a dynamic website displays changing content based on user actions, database information, or other conditions. Thus, the browser, client, server, and database work together to load and display a website.

HTTP and HTTPS
HTTP: HyperText Transfer Protocol. It transfers data between a browser and a web server without encryption.
HTTPS: HyperText Transfer Protocol Secure. It transfers data securely using encryption (TLS).
Static vs Dynamic Websites
Static website: Displays fixed content, usually the same for every visitor.
Dynamic website: Displays content that can change based on user input, database information, or other conditions.
Request-Response Cycle
User enters a URL in the browser.
Browser finds the server using DNS.
Browser sends a request to the server.
Server processes the request and accesses the database if needed.
Server sends a response to the browser.
Browser displays the website on the screen.