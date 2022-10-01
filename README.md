

#1. git clone command 
    git clone --branch feature https://github.com/CSYE6225-Rahul/RahulS_webapp.git

#2. RUN "DemoApplication.java"

#3. test
    curl -v http://localhost:8080/healthz

#4. expected output
    
    GET /healthz HTTP/1.1
    > Host: localhost:8080
    > User-Agent: curl/7.79.1
    > Accept: */*
    >
    *Mark bundle as not supporting multiuse
    < HTTP/1.1 200 

