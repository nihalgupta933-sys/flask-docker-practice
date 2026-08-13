# flask-docker-practice

Just a basic learning exercise I did to practice **Docker** commands and **Git** workflows by containerizing a simple Python script.

## 📂 Project Files
*   [app.py](app.py) - The basic Python script using Flask.
*   [Dockerfile](Dockerfile) - The 5-line configuration script to run the code in a container.
*   [requirements.txt](requirements.txt) - The file listing the required Flask package.

---

## 💻 Workflow & Verification

### 1. Build the Docker Image
I built the local Docker image using the tag `aldrago10/welcome-app`.
![Docker Build](ss/Screenshot%202026-08-13%20133739.png)

### 2. Check Local Images & Push to Docker Hub
I verified the image in Docker Desktop and successfully pushed it to my public Docker Hub registry.
![Docker Desktop](ss/Screenshot%202026-08-13%20133800.png)
![Docker Hub Push](ss/Screenshot%202026-08-13%20134014.png)
![Docker Hub Dashboard](ss/Screenshot%202026-08-13%20134034.png)

### 3. Test Pulling from Registry
To simulate a clean deployment, I deleted the local image from my computer, pulled it fresh from Docker Hub, and verified it was downloaded using the `docker images` command.
![Docker Pull](ss/Screenshot%202026-08-13%20134240.png)

### 4. Run and Verify in Browser
Finally, I ran the containerized application locally on port 5000 and verified that the Flask web server loaded perfectly in the browser.
![Running App](ss/Screenshot%202026-08-13%20134315.png)
