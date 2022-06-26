# machine_learning_project

Creating conda environment

1. conda create -p venv python==3.7 -y (to create environment)
2. conda activate venv/ (to activate virtual environment)
3. git log (to check git commit)
4. git remote -v (to check remote url or origin variable)
5. git add -A (to add file in git)
6. git branch (to get the branch name)
7. git push origin main (to push code to github).

To setup CI/CD pipeline in heroku we need 3 things as follow:

1. HEROKU_EMAIL: rahulkothari215@gmail.com 
2. HEROKU_API_KEY: 3e78e708-d712-403f-8b9b-ae21aae8e8e1
3. HEROKU_APP_NAME: ml-rahul

To Build Docker Image
```
docker build -t <image_name>:<tagname> .
```

> Note: Image name for docker must be lowercase.

TO list Docker Image
```
docker images
```

Run Docker Image
```
docker run -p 5000:5000 -e PORT=5000 image_id
```

To check running container in docker
```
docker ps
```
TO stop docker container
```
docker stop <container_id>
```

