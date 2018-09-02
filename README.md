# Blog using Django

Simple Django app featuring steps given in the [Django Girls Tutorial](https://tutorial.djangogirls.org/en/)

### How to run using Docker

- Build the image 

  ```sh
  $ sudo docker build -t someone/django-blog .
  ```

- Run using docker-compose

  ```sh
  $ sudo docker-compose up
  ```

- Run on Swarm cluster

    - Initialise the cluster
      ```sh
      $ sudo docker swarm init
      ```

    - Deploy the stack
      ```sh
      $ sudo docker stack deploy --compose-file docker-stack.yml blog-service
      ```

## Licensing

`wait-for-it.sh` is taken from [vishnubob/wait-for-it](https://github.com/vishnubob/wait-for-it) - licensed under [MIT License](https://github.com/vishnubob/wait-for-it/blob/master/LICENSE)

This repository is licensed under GNU General Public License v3.0. See [LICENSE](./LICENSE) for the full license text.
