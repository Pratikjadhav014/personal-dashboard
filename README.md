

\# Personal Dashboard



A personal dashboard built using HTML, CSS, and JavaScript.



\## Technologies Used

\- HTML5

\- CSS3

\- JavaScript

\- Docker

\- Nginx



\## Run Locally

Open `index.html` in your browser.



\## Run with Docker



Build the Docker image:



```bash

docker build -t personal-dashboard .

```



Run the container:



```bash

docker run -d -p 8080:80 --name dashboard-container personal-dashboard

```



Open http://localhost:8080 in your browser.



\## Stop the Container



```bash

docker stop dashboard-container

```



\## Remove the Container



```bash

docker rm dashboard-container

```





