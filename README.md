# Apartment-management
This project is created for deploying web application by docker compose.
It composes of 4 parts
- MongoDB
- Frontend ( Angular ) - https://github.com/ThanawatP/apartment-management-angular
- Backend API ( Express.js ) - https://github.com/ThanawatP/apartment-management-api
- Initial data script ( Bash script ) - https://github.com/ThanawatP/apartment-management-init

# Quickstart
```
docker-compose up -d
```
It might take a long time in first running because of building docker image processes.
After finish running process, open browser and access
```
localhost
```

# Deployment without using docker compose
You have to clone each projects from above links and follow these steps
1. start MongoDB
2. start API
3. run script
4. start Angular
