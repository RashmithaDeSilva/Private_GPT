# Private GPT

This is private chatGPT model that can use locally, and this project create based on ollama and open-webui

### GUI
![alt text](imgs/img-1.png)

---

### How to start 
* Runs on CPU.
* This will start two containers that runs ollama container for store models other runs open webui for frontend.
~~~sh
docker-compose -f ./Docker/docker-compose.yml up -d 
~~~

---

### How to download models
* You can download models from ollama "https://ollama.com/library" to ollama container.
* Method 1
    * Using docker dekstop
    ![alt text](imgs/img-2.png)
* Method 2
    * Using CMD
    ~~~sh
    docker exec -it ollama sh
    ~~~
    ![alt text](imgs/img-3.png)