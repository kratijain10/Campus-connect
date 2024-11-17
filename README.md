# Final Year Project - ETC 2025  

## Project Overview  
This repository contains the source code and resources for the Final Year Project (ETC 2025). The project is built with a Node.js backend and a modern frontend framework.  

## Prerequisites  
Before running the application, ensure that the following are installed:  
- Node.js (v16.x or later)  
- npm (Node Package Manager)  

## Installation  

Follow the steps below to set up the project:  

### Clone the Repository  
```bash  
git clone https://github.com/sajal221202/Final-Year-Project-ETC-2025.git  
cd Final-Year-Project-ETC-2025  
```  

### Install Node Modules  

1. Install dependencies for the **parent folder** (main project directory):  
   ```bash  
   npm install  
   ```  

2. Navigate to the `frontend` folder and install dependencies:  
   ```bash  
   cd frontend  
   npm install  
   cd ..  
   ```  

## Running the Project  

### Backend  
Start the backend server by running the following command in the main folder:  
```bash  
npm run dev  
```  

### Frontend  
Navigate to the `frontend` folder and start the frontend:  
```bash  
cd frontend  
npm run dev  
```  

## Environment Variables  

Create a `.env` file in the main folder and include the following variables:  
```
# Server Configuration  
PORT=5000  

# Database Configuration  
MONGO_URI=<your_mongo_uri>  

# Authentication Keys  
JWT_SECRET=<yourverystrongsecret>  

# Environment  
NODE_ENV=development  

# Mail Configuration  
MAILTRAP_TOKEN=<your_mailtrap_token>  
EMAIL_FROM=mailtrap@demomailtrap.com  
EMAIL_FROM_NAME=<Your_Name>  

# Cloudinary Configuration  
CLOUDINARY_API_KEY=<your_cloudinary_api_key>  
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>  
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>  

# Frontend Client  
CLIENT_URL=http://localhost:5173  
```  

Replace the placeholders (`<your_value>`) with actual values based on your project's requirements.  

## Directory Structure  
```
Final-Year-Project-ETC-2025/  
├── backend/        # Contains backend source code and API  
├── frontend/       # Contains frontend source code  
├── .env            # Environment variable file (to be created)  
├── README.md       # Project documentation  
├── package.json    # Backend dependencies  
└── .gitignore      # Git ignore file  
```  

## Contribution  
Feel free to fork the repository and submit pull requests. Contributions are always welcome!  

## License  
This project is licensed under the MIT License.  

---  
