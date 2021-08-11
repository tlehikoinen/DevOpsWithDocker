cd example-backend && docker build . -t backend-2 && docker run -p 8000:8000 backend-2
cd example-frontend && docker build . -t frontend-2 && docker run -p 5000:5000 frontend-2


