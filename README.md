# ArtGalleryPro | Gallery Management System

A comprehensive, web-based management system designed to help art galleries streamline their daily operations, from inventory and artist tracking to client relations and sales.

## Features

- **Artwork Inventory:** Digitally catalog pieces with details like title, artist, medium, dimensions, provenance, and status (Available, Sold, On Loan).
- **Client & Artist CRM:** Maintain a centralized database of contacts, track interactions, and manage preferences.
- **Sales & Invoicing:** Generate invoices, record payments, and track financial transactions.
- **Exhibition Management:** Organize exhibitions, associate artworks, and manage checklists.
- **User-Friendly Dashboard:** Get a quick overview of recent activity, key metrics, and upcoming tasks.

## Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Authentication:** JWT (JSON Web Tokens)

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- PostgreSQL

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/artgallerypro.git
    cd artgallerypro
    ```

2.  **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

3.  **Install frontend dependencies:**
    ```bash
    cd ../frontend
    npm install
    ```

4.  **Set up environment variables:**
    - Create a `.env` file in the `backend` directory based on the `.env.example` file.
    - Add your database connection string and JWT secret.

5.  **Run the application:**
    - Start the backend server (from `/backend`):
      ```bash
      npm run dev
      ```
    - Start the frontend development server (from `/frontend`):
      ```bash
      npm start
      ```

6.  Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
