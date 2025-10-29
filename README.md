#SciVault

**SciVault** is a lightweight web application built to manage and organize scientific research data.  
It allows users to upload, browse, and access datasets such as experimental results or clinical records in a simple and structured way.

##User Roles

- **Data Submitters** – Upload and manage research datasets (e.g., CSV files).  
- **Researchers** – After admin validation, can view and download available datasets.

---

##Project Structure

SciVault/
│
├── public/ # Frontend (HTML, CSS, JS)
├── uploads/ # Stores uploaded CSV files
├── server.js # Express backend server
└── package.json # Backend dependencies and metadata


---

##Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express  
- **File Uploads:** Multer  
- **Storage:** Local filesystem (`uploads/` folder)

---

##Getting Started

1. Ensure **Node.js** is installed.
2. Clone this repository:
   ```bash
   git clone <repo-url>
   cd SciVault
3. Install dependencies:
   npm install
   
4. Start the server:
   node server.js

5. Open the HTML files in your browser (e.g., using Live Server).
   
##Features

Upload and manage research data files
Basic role-based access for Submitters and Researchers
Clean, multi-page layout
Includes sample datasets in the uploads/ directory

##Future Improvements

Add user authentication and database integration
Enable dataset search and filtering
Add in-browser data previews
Implement admin-based researcher approval workflow

##Developed as part of a Database and Cloud Computing Project.




