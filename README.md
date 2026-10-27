# k.tuleubaeva_docker
Тулеубаева Камила АҚЖ-33 СРО-2 СРО-3
## ☁️ Docker Hub

Дайын 3 образдар:

[https://hub.docker.com/r/kamila20/kamila-cyberrisk](https://hub.docker.com/r/kamila20/kamila-cyberrisk)

##


## Қолданылған технологиялар

- **HTML** — веб-сайттың құрылымы.
- **Docker** — сайтты контейнерде іске қосу.
- **Nginx** — веб-сайтты көрсетуге арналған веб-сервер.
- **Docker Hub** — Docker образын сақтау.
- **GitHub** — жоба файлдарын сақтау.

## Жоба файлдары

- `index.html` — сайттың негізгі беті.
- `Dockerfile` — Docker образын құру нұсқаулығы.
- `README.md` — жобаның сипаттамасы және іске қосу жолы.



### Docker образын құру: docker build -t kamila-cyberrisk .

Бұл команда сайттың Docker образын жасайды.



### Контейнерді іске қосу : docker run -d --name kamila-cyberrisk-container -p 8080:80 kamila-cyberrisk

Бұл команда сайтты контейнер ішінде іске қосады.



### Сайтты ашу: [**http://localhost:8080**](http://localhost:8080)



## Жұмысты тексеру

Контейнерлерді көру: docker ps

Docker образдарын көру: docker images

