

---

## 🚀 Features

- **User Authentication:**  
  - Sign up, log in, log out (Devise)
  - Edit profile (username, email, password) without requiring current password for non-password changes

- **Linktree Management:**  
  - Create, read, update, and delete your own "tree" (profile with links)
  - Each user can have only one tree
  - Each tree includes: name, custom links (e.g., Instagram, YouTube), style

- **Friendly URLs:**  
  - User and tree profiles use readable slugs (e.g., `/malaki-asaran` instead of `/4`) via Friendly ID

- **MVC Architecture:**  
  - Clear separation of Models, Views, and Controllers for maintainable code

- **Reusable Components:**  
  - Partials for navigation bar and other UI elements

- **Data Validations:**  
  - Ensures valid URLs, minimum name length, and required fields

- **Admin Panel:**  
  - (Optional) Easily extendable with Rails Admin for managing users and trees

- **Responsive Design:**  
  - Custom CSS and Bootstrap for a modern, mobile-friendly interface

- **Deployment Ready:**  
  - PostgreSQL for production database
  - Deployable to Fly.io or Render

---

## 🛠️ Tech Stack

- **Ruby on Rails 7**
- **Ruby** (latest version)
- **PostgreSQL**
- **Devise** (authentication)
- **Friendly ID** (slugs)
- **Bootstrap** (CSS framework)
- **Puma** (web server)
- **Yarn & Node.js** (assets)
- **Fly.io** or **Render** (deployment)

---

## ⚡ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-user/linktree-clone.git
   cd linktree-clone
Install dependencies:

Bash

bundle install
yarn install
Set up the database:

Bash

rails db:create db:migrate db:seed
Configure environment variables:

(e.g., Devise mailer, database, etc. – see .env.example)
Start the server:

Bash

rails server
Access the app:
Open http://localhost:3000 in your browser.

🧪 Tests
Bash

bundle exec rspec
🖼️ Screenshots
Home Page	User Tree	Edit Profile
Home	Tree	Edit Profile
💡 Key Concepts Covered
MVC (Model-View-Controller) architecture
Rails routing and path helpers
Scaffolding for rapid CRUD development
User authentication with Devise
Friendly URLs with Friendly ID
Model relationships (User has_one :tree)
Data validations and error handling
Customizing Devise controllers and views
Using partials for DRY code
PostgreSQL setup for production
Deployment to Fly.io or Render

LinkedIn | GitHub
Thank you for visiting! If you like this project, please star the repo and follow me on GitHub.
Happy coding! 🚀
