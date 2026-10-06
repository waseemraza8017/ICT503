# Open pgAdmin and create database as:
helpdesk

# Open Terminal 1 and execute the following commands one-by-one
cd backend
npm install
npm run start:dev          


# Open Terminal 2 and execute the following commands one-by-one
cd frontend
npm install
npm run dev                


# Open Terminal 3 and execute the following commands one-by-one
cd backend
npm run migration:run
npm run seed