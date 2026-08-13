# flask-docker-practice

Just a basic learning exercise I did to practice the absolute basics of **Docker** and **Git**. 

I wanted to make sure I know how to use basic commands to push code to Git and wrap a simple Python script inside a container. This basic skill will help me later when I need to containerize scripts for data engineering.

## 📂 Project Files
You can view each file directly here:
*   [app.py](app.py) - The basic Python script using Flask.
*   [Dockerfile](Dockerfile) - The 5-line configuration script to run the code in a container.
*   [requirements.txt](requirements.txt) - The file listing the required Flask package.

## 💻 Commands I Practiced

```bash
# To build the image from the Dockerfile:
docker build -t flask-docker-practice .

# To run the container on port 5000:
docker run -p 5000:5000 flask-docker-practice
```

