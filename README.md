
# Docker Commands





- docker --version ===> To check the version of Docker

- docker pull  ===> This command is used to pull images from the docker repository(hub.docker.com)

- docker run -d -p <image name>  ===>  This command is used to create a container from an image
   - -d - run the container in detached mode
   - -p 80:80 - map port 80 of the host to port 80 
   - <image name>the image to use  
    
- docker ps ===> This command is used to list the running containers

- docker ps -a ===> This command is used to show all the running and exited containers

- docker stop <container id> ===>  This command stops a running container

- docker commit <conatainer id> <username/imagename>  ===>  This command creates a new image of an edited container on the local system

- docker login  ===> This command is used to login to the docker hub repository

- docker push   ===> This command is used to push an image to the docker hub repository

- docker images ===> This command lists all the locally stored docker images

- docker rm  ===> This command is used to delete a stopped container

- docker rmi ===> This command is used to delete an image from local storage

- docker build  ===>  This command is used to build an image from a specified docker file



## Screenshots

## docker version
![App Screenshot](https://dsm01pap002files.storage.live.com/y4m8v3itBYUPhqlzpXX61F02J2NHIZu0k7Dn6Y9_HFI7rDJawXpKlzgOCjamXJmGH_9xQHf833S5il-RJeFCu3wTFGzUrB0Rt7CWqMSYu_Me0u8GToBwDworUU4_zQlhQ4plDEyqyqzH5Ap4Ja6enAkH-XAc3YdxQclLVIvqi9RharNzBN3gOz0GA98jWlFsjHmj0i8qcmDB5tCBw4TFSzxAzI9RQRzK8hNPdo53ZrW2pM?encodeFailures=1&width=368&height=141)
## Pull getting-start image
![App Screenshot](https://dsm01pap002files.storage.live.com/y4mh6fbAtLfBAl-BXbPU5MJ0tN1dDfNxwat5GkYtUeHjAAiiu-JZqrqJob8d8Tpy_YlFb9cFOXdlZ8d9gtkls4AhnK5LcqY7_Yc5cuteGmJJU2Z4ssl6mzTYkvQ0seLm-RyFzay22yrmbu4YIqbXUUg5j4FqV_rOwrURwypj6yikkdM6L5igkEnaqdQ185_Jq3kmDlwnz9qhp7ppmze8vZUcMV-rgazQK-wwA_Srl49BaE?encodeFailures=1&width=855&height=356)
## Run Image
![App Screenshot](https://dsm01pap002files.storage.live.com/y4mJNUfpgTCHHm0gEUKwhr4zNhSddlb3yBKQaYY5V2sthGmT1Aj8lLtaW5HSFlzJb7yJn27lRxvyhK1-MnmJ7lv_-ChrrLiDqc_EqUWsxvUSoKTKHeMHxjIsFxs9hlZDsUL9KBcvzd414OK1FyOmBG8ApXN-gtT2h7BOhV-SQzSMMOIxWePOY5jHQKbJA4oLJC71J1weWdPvK2MgfiLMC2RNXL5_v7EVQdgzB-F4SYWdck?encodeFailures=1&width=1473&height=457)

![App Screenshot](https://dsm01pap002files.storage.live.com/y4m3Y7jGBW_QnsXLccXySZYY-6L4zteV21uYZCElSxQWRTUvpvrW5cHzqRwW8bRqvnCjHITE1CWGAbqu6KNqdasRUS4NxF7mAbcW8YoPN5jcYHhOrehGqoBEhQkjEWGxRhpS6GQm_cyysFy-9y8OjgJFsdHoMgyqWLXy7ccrydH-kKy2pdrkfZR7vzGnna1JYqe4DJ6f8H3VF45q9P-8_76etYuKYt8pgJoFDkCmM5f79Y?encodeFailures=1&width=1496&height=842)
## Removeing image
![App Screenshot](https://dsm01pap002files.storage.live.com/y4mm3oXjDMxR28b1FyStSJDM-wUx6fjLxz5HXkwrppz5R8q8_kQf3VKhZ8Eskts4xL2wHoTtL38d3WSgemLK-q6nYjyUyd1zIUNqkNZHuo13zhlY3rXdqKnXyMMnrjNlL92SdyXKg23IUcm9QFlIAD5Efo9C2-G5aJAj-BvYnyPeip7BpSmHJ4vny4sAbGhWWXRqPMOK97cWmQYXVpo4wGOwFk9kb7LeG8fnx67yM9wv24?encodeFailures=1&width=941&height=390)
## Run krishnaik06/welcomeapp 
![App Screenshot](https://dsm01pap002files.storage.live.com/y4m7M-pFb5dVKTrEj8LM_Xw1tygXsVzDnJc-7rBJfoTrl-ezSl4T1VBI_yzoXav-UqRS672qQ-RLcwyIhl4U0FAx9UEVokRkYnaveOC-MnelnCH2qRIqCHolpClHcNi6BVV-zfG15h0FzoOy3u9R6V7Eaomkn6lkgKhJSm0SLVBXQhtRUcYyiUBYrRxbng84z3fKwCvnRZqcwg146su4dcjGThsXJ7sOAHLC9Itf8cVHnc?encodeFailures=1&width=1393&height=242)
![App Screenshot](https://dsm01pap002files.storage.live.com/y4mAXm0inli6h7sgock3Od-9IJM6xBez9Xr7T0pCqanvAmxxnYrKe6uFDNIeKVbnAmiT-ZOyXIsdlXDqRANuw-HO0ZPaVLEyUAhSjlPwLOSMsZVdRFewVNpCpjqlnIowjmUxEzzQwx3UMACdwvFZ_Bm8x07slQDulTMZMI0rRJvupwHj1GfQiJOENlHtZAX71Pl2dP3TD7AXHkSJGuTw1hJ9TzdkDka7EPA9iElAPpq_-Q?encodeFailures=1&width=1496&height=842)


