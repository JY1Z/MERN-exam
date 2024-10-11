# EXAM

## Backend
- [Example for Backend auth&no-auth](https://github.com/tx00-resources/week7-bepp)

### File Structure
#### withAuth
server/    
├── config/      
│   └── db.js (MongoDB connection)     
├── controllers/    
│   ├── itemController.js (CRUD logic for items) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/controllers/userControllers.js)        
│   └── userController.js (User registration, login, and management) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/controllers/jobControllers.js)        
├── models/    
│   ├── itemModel.js (Mongoose schema for items) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/models/jobModel.js)  
│   └── userModel.js (Mongoose schema for users) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/models/userModel.js)   
├── routes/  
│   ├── itemRoutes.js (API routes for items) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/routes/jobRouter.js)  
│   └── userRoutes.js (API routes for users) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/routes/userRouter.js)    
├── middleware/   
│   ├── customMiddleware.js (Request logging, unknownEndpoint and error handling) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/middleware/customMiddleware.js)      
│   └── requireAuth.js (Authentication middleware) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/middleware/requireAuth.js)   
├── .env (Environment variables) [cm2](https://github.com/tx00-resources/cm2-starter/blob/main/backend/api-server-starter/.env.example)   
├── app.js (Express app entry point) [cm2](https://github.com/JY1Z/collaborative-project-2/blob/main/backend/api-server-starter/app.js)   
├── package.json (Dependencies and scripts)    
└── package-lock.json (Exact dependency versions) 

### Postman
GET:all(read),itmeID(read)
POST:create
PUT:itemID (update)
DELETE: itemID(delete)  
/api/tours/:tourId
/api/tours

### Backend testing
- [BE pp](https://github.com/tx00-web-en/Activities/blob/week7/material/bepp.md) [answer](https://github.com/JY1Z/week7-be-pp)
- week 6 activities 

## Frontend
- [CRUD, User Authentication, Protected Routes](https://github.com/tx00-resources/week7-fepp/tree/branch7-protect-jobs/frontend/src)
- [It will fully prepare you for the front-end portion of the exam.](https://github.com/tx00-web-en/Activities/blob/week7/material/fepp.md)
1. JWT auth 
2. fetch+CURD (useEffect hook)

## Full Stack  
- [CM2](https://github.com/tx00-web-en/Activities/blob/week6/material/cm.md)  [collaborative-project-2](https://github.com/JY1Z/collaborative-project-2)
