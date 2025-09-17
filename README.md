**How to run this project locally**

1. install mongodb and create a database and some details
2. update the /backend/.env file as per required details given in that file
3. update the /frontend/.env file as per required deatils given in that file
4. now run this command:   systemctl start mongod
5. go to /frontend folder & run these two commands:  npm install  &   npm run dev -- --host
6. go to /backend folder & run these two commands:  npm install  &  npm run dev
7. you can access the forntend page in broswer at:   your_ip_address:5173    & backend page at:   your_ip_address:5000
