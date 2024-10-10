# EXAM

## Backend
- [Example for Backend auth&no-auth](https://github.com/tx00-resources/week7-bepp)
- 
### File Structure
server/    
├── config/      
│   └── db.js (MongoDB connection)     
├── controllers/    
│   └── itemController.js (CRUD logic)     
├── models/    
│   └── itemModel.js (Mongoose schema)  
├── routes/  
│   └── itemRoutes.js (API routes for User)   
├── middleware/   
│   ├── customMiddleware.js(Request logging, unknownEndpoint and error handling)  
│   └── requireAuth.js (Authentication middleware)   
├── .env (Environment variables)   
├── app.js (Express app entry point)   
├── package.json (Dependencies and scripts)    
└── package-lock.json (Exact dependency versions)    

## Frontend
- [CRUD, User Authentication, Protected Routes](https://github.com/tx00-resources/week7-fepp/tree/branch7-protect-jobs/frontend/src)
