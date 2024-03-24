# **K8s-Voting-App-Project**
This is a voting app created using Python, this app is exposed to the customers
and they can cast their vote

This info will be registered in an in-memory db(temporary db) that we set
using Redis From here we have a .net application that filers the data and
stores it permanently in a Postgres db and the results can be viewed on an app
created using nodejs

Important: Redis and Db service names should be "**redis**" and "**db**"

Steps:

1 git clone 

2 cd **K8s-Voting-App-Project**

3 kubectl apply -f .

4 kubectl delete -f .

![architecture excalidraw](https://github.com/V-vk-404/K8s-Voting-App-Project/assets/78948052/ed8b4d46-50b9-4f96-bcf3-c40d962083de)



