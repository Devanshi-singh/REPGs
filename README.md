# REPGs
"I prioritized security, scalability, and modern UX throughout the development:"
Security Best Practice: "A major focus was on database integrity. I implemented server-side validation and, critically, used Prepared Statements in the registration flow (register.php). This is the industry standard for preventing SQL Injection attacks, demonstrating a commitment to writing secure back-end code."
Front-End Architecture: "I designed a highly maintainable and responsive interface. The styling utilizes a CSS Variable System for scalability, and the layouts are fully responsive across devices using media queries (visible in properties.css and payment.css)."
Data-Driven Dynamic Content: "The user dashboard (dashboard.php) is a dynamic, data-driven view. It uses embedded PHP to execute multiple SELECT queries against two tables (users and users2), effectively joining and presenting personalized user and booking information in real-time."
