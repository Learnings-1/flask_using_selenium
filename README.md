### Step1 : Build Project
```bash
docker build -t <docker-user-name>/<app-name> .
Example : docker build -t syedimran1/flask-1 .
```
### Step2 : Run Project Locally
```bash
docker run -p 8080:8080 <docker-user-name>/<app-name>:latest
Example : docker run -p 8080:8080 syedimran1/flask-11:latest
```

### Step3 : Push Project
```bash
docker push <docker-user-name>/<app-name>:latest
Example : docker push syedimran1/flask-11:latest
```

### Step4 : Deploy Project
```bash
cf push <app-name>
Example : cf push flask-1
```


