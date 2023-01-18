# Docker



- Check if Docker run
    ```
    Docker run hello-world
    ```
- -it: Run it in terminal
    ```
    Docker run -it ubuntu bash
    ```
- run python 3.9
    ```
    docker run -it --entrypoint=bash python:3.9
    ```
 - build
    ```
    docker build -t test:pandas .

    ```
 - Run
   2023-01-18 pass to argv   
    ```
    docker run -it test:pandas 2023-01-18

    ```
               