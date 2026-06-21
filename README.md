# 🚀 .NET Developer Roadmap: Web & HTTP Fundamentals

Welcome to my learning repository! This project contains my structured, handwritten study notes covering the core pillars of web architecture, network protocols, and security mechanisms essential for **.NET Backend Development**. 

These notes bridge the gap between theoretical networking and practical software engineering (such as designing Web APIs and managing security in .NET).

---

## 🗺️ Project Structure & Topics Covered

### 🔹 Lesson 1: Web Infrastructure & Internet Foundations
* **Concepts:** Understanding the Global Network (Internet vs. WWW), Client-Server Architecture, and the Application Layer.
* **Domain & Network:** Deep dive into IP Addressing (IPv4/IPv6), Domain Name System (DNS) resolution, Web Hosting, and URL Hierarchy.
* **Browser Execution:** How a browser parses URLs, handles DOM trees, and renders pages via Web Servers (like Kestrel in .NET).

📖 **Download / View Notes:**
* [📄 Page 1: Internet Infrastructure](./1.pdf)
* [📄 Page 2: Web Architecture](./2.pdf)

---

### 🔹 Lesson 2: Deep Dive into HTTP/HTTPS Protocols
* **The Cycle:** Detailed analysis of the HTTP Request/Response Cycle.
* **Anatomy of Requests:** Exploring Methods (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`, `HEAD`, `OPTIONS`), Request Headers (`User-Agent`, `Accept`, `Authorization`), and Metadata.
* **Anatomy of Responses:** Status Lines, Status Codes (1xx to 5xx), Response Headers (`Content-Type`, `Cache-Control`, `Set-Cookie`), and Payload Media Types (MIME).
* **Architectural Properties:** Understanding **Safe** vs. **Idempotent** operations in RESTful designs.

📖 **Download / View Notes:**
* [📄 Page 3: HTTP Requests](./3.pdf)
* [📄 Page 4: HTTP Responses](./4.pdf)
* [📄 Page 5: HTTP Methods and CRUD](./5.pdf)

---

### 🔹 Lesson 3: Web Security, State Management & Authentication
* **State Management:** Addressing the *Stateless* nature of HTTP using Cookies vs. Server-side Sessions.
* **JWT (JSON Web Token):** Deep dive into Token-based authentication, structural analysis (Header, Payload, Signature), scalability advantages, and downsides (e.g., immediate revocation challenges).
* **CORS (Cross-Origin Resource Sharing):** Understanding origin components (`Protocol + Domain + Port`), Preflight requests (`OPTIONS` method), and configuring CORS headers to prevent browser-level blocks.

📖 **Download / View Notes:**
* [📄 Page 6: State Management](./6.pdf)
* [📄 Page 7: CORS Mechanism](./7.pdf)
* [📄 Page 8: JWT Authentication](./8.pdf)

---

## 🛠️ Tools Used
* **Digitization:** CamScanner (for high-contrast document scanning).
* **Version Control:** Git & GitHub for public documentation.

*Feedback and discussions on .NET architectures are always welcome! Feel free to explore the notes.*
