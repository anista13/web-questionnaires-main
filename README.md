= Web questionnaires

backend and frontedn running seperately.to make it work run back and fron at the same time. 

backend: 
cd backend
python app.py

frontend:
cd frontend
npm install
npm run dev

error in frontend: 
cd "D:\Master Degree\web-questionnaires-main\web-questionnaires-main\frontend"

Remove-Item -Recurse -Force node_modules
Remove-Item -Force package-lock.json

npm install
npm run dev