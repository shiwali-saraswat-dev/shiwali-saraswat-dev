[![Shiwali Saraswat - Senior Backend Engineer](assets/banner.png)](assets/banner.png)

# Hi, I'm Shiwali Saraswat 👋

**Senior Backend Engineer · API Architect · PHP / Laravel Specialist**

6+ years building production-grade backend systems, payment integrations, and scalable APIs. Currently expanding into React on the frontend.

> 🟢 **Open to work:** PHP / Laravel Developer and Tech Lead roles, Noida · Delhi · Gurgaon, with remote, hybrid, and international options.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shiwali-saraswat-dev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saraswatshiwali@gmail.com)

---

### 📈 Impact From Production Work

Most of my professional work lives in private repositories, so GitHub can't show it. Here is what it looked like:

- **15+ production systems** delivered end to end as the sole backend developer
- **SQL optimization:** cut a critical query from **~90s to ~13s**
- **Process automation:** reduced a manual workflow from **6 hours to 20 minutes**
- **Data pipeline:** built a **10M+ record** import pipeline for an OpenCart-based store
- **Marketplace:** built a multivendor marketplace with payment integrations
- **Microservices:** introduced Lumen-based services to the team's stack
- **Upgrades:** led Laravel version upgrades from **5.x to 8**
- **Payments & auth:** Stripe, Braintree, and PayPal integrations, plus OAuth2, Passport, Sanctum, and JWT

---

### 🛠 Tech Stack

**Core (daily, production-proven)**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=flat-square&logo=fastapi&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-3423A6?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Braintree](https://img.shields.io/badge/Braintree-000000?style=flat-square&logo=braintree&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-777BB4?style=flat-square&logo=php&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Also worked with**

![Lumen](https://img.shields.io/badge/Lumen-E0271F?style=flat-square&logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white)
![OpenCart](https://img.shields.io/badge/OpenCart-21B7DC?style=flat-square&logo=opencart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Bruno](https://img.shields.io/badge/Bruno-F5A623?style=flat-square&logo=bruno&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

**Currently learning**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

### 🚀 Featured Projects

#### [Library Management API](https://github.com/shiwali-saraswat-dev/library-management-api) · 🚧 In progress

*A RESTful Laravel 12 API for a library's catalog, members, and borrowing workflow.*

- **Built:** Auth, Category, Author, Book, and Member modules — all with role-based access control
- **Architecture:** Controller → Service → Repository → Policy → Resource layering, with centralized error handling and request tracing (`X-Request-Id` on every response)
- **Security:** Sanctum authentication and a four-tier RBAC hierarchy (owner → admin → librarian → member) via spatie/laravel-permission
- **API design:** cursor pagination, role-aware HATEOAS links, consistent success/error envelopes, OpenAPI docs via l5-swagger (Auth, Books, Categories, and Authors documented; Members in progress)
- **Quality:** Pest test suite, Larastan static analysis, and a GitHub Actions CI pipeline running both checks on every push
- **In progress:** borrow/return workflow with concurrency-safe transactions
- **Roadmap:** reservations, fines, idempotent writes

`PHP 8.3` `Laravel 12` `MySQL` `Sanctum` `OpenAPI` `Pest` `GitHub Actions`

#### [Unified Hotel ERP](https://github.com/shiwali-saraswat-dev/Unified-Hotel-ERP)

*A hospitality management suite built to demonstrate modern Laravel 12 patterns.*

- **Modules:** Guest PMS (room booking), POS (food ordering), and BMS (banquet management)
- **Modernization:** migrated from Laravel 8 to Laravel 12 using PHP 8.x features
- **Security:** role-based access control with Laravel Breeze for secure administration
- **Data integrity:** soft and permanent delete workflows with strict validation across modules
- **UX:** custom pagination, dynamic asset loading, and real-time notifications via SweetAlert2 / Toastr

`Laravel 12` `Blade` `MySQL` `Tailwind CSS`

#### [Food Delivery App (React)](https://github.com/shiwali-saraswat-dev/food-delivery-app-react)

*A food-ordering UI practice project, built and refactored publicly through a feature-branch + pull-request workflow.*

- **Built:** header/nav, tabs, category and brand cards, promotional banner, restaurant listing with ratings/cuisine/delivery time, chain carousel, and footer — fully componentized from an original single-file prototype
- **Process:** every change ships through its own branch and PR; some (e.g. `explore/props-patterns`) deliberately compare a few implementation approaches in the PR description before settling on one
- **Next:** search, cart, checkout, and order tracking

`React` `Parcel` `JavaScript`

#### [DSA in PHP](https://github.com/shiwali-saraswat-dev/dsa_php)

*Data structures, algorithms, and problem-solving patterns in PHP, organized by topic, for backend interview preparation.*

`PHP`

#### [React From Scratch](https://github.com/shiwali-saraswat-dev/react-from-scratch)

*A self-paced React learning log, numbered module by module: plain HTML and vanilla JS through JSX, components, hooks, data fetching, and routing.*

- **Covers so far:** functional components and composition, props patterns, JS expressions in JSX, the `useState` hook, fetching data with a loading UI, a search/toggle UI, and React Router
- **Format:** each concept lives in its own numbered folder (`001-hello-world-html` → `023-react-routing`), so progress is traceable step by step

`React` `Vite` `React Router` `JavaScript`

---

### 🌱 What I'm Working On

- Building the borrow/return workflow in the Library Management API
- Building out React skills through small, real-world projects
- Practicing data structures and algorithms in PHP

---

### 📊 Languages

[![Top Languages](https://github-stats-extended.vercel.app/api/top-langs/?username=shiwali-saraswat-dev&layout=compact&theme=tokyonight&hide_border=true&hide=html,css,scss)](https://github.com/shiwali-saraswat-dev?tab=repositories)

---

*Specialized in Backend Architecture · API Development · Laravel Ecosystem. Growing into React.*
