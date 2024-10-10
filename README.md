# EXAM

## Backend
- [Example for Backend auth&no-auth](https://github.com/tx00-resources/week7-bepp)
- 
### File Structure
#### withAuth
server/    
├── config/      
│   └── db.js (MongoDB connection)     
├── controllers/    
│   ├── itemController.js (CRUD logic for items) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/controllers/userControllers.js)        
│   └── userController.js (User registration, login, and management) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/controllers/jobControllers.js)        
├── models/    
│   ├── itemModel.js (Mongoose schema for items) [cm2]([https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/controllers/jobControllers.js](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/models/jobModel.js))  
│   └── userModel.js (Mongoose schema for users) [cm2]([https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/controllers/userControllers.js](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/models/userModel.js))   
├── routes/  
│   ├── itemRoutes.js (API routes for items)   
│   └── userRoutes.js (API routes for users)    
├── middleware/   
│   ├── customMiddleware.js (Request logging, unknownEndpoint and error handling)  
│   ├── requireAuth.js (Authentication middleware)   
│   └── withAuth.js (Authorization middleware for user roles, etc.)    
├── .env (Environment variables)   
├── app.js (Express app entry point)   
├── package.json (Dependencies and scripts)    
└── package-lock.json (Exact dependency versions) 

### Backend testing

## Frontend
- [CRUD, User Authentication, Protected Routes](https://github.com/tx00-resources/week7-fepp/tree/branch7-protect-jobs/frontend/src)



## Full Stack  
- [CM2](https://github.com/tx00-web-en/Activities/blob/week6/material/cm.md)  [collaborative-project-2](https://github.com/JY1Z/collaborative-project-2)
- [CM2 revisit](https://github.com/tx00-web-en/Activities/blob/week7/material/fepp.md)
