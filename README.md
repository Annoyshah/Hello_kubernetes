# Hello_kubernetes
<h3> Basic demo project to practise k8s</h3>

<h4>:dizzy: Here I have created a Mongodb pod and an internal service , also created a Mongo express deployment and refrenced database url from configMap and database username and password from Secret into environment variables of deployment config file of Mongo Express. In order to access Mongo express through browser I have created an external service that will allow external service to connect to the pod .
</h4>

<h4> 
:dizzy: Request flow looks like this :
Request comes from browser and it goes to external service of mongo express , it will then be forwarded to mongo express pod , pod will transfer that to internal service of Mongodb then it gets forwarded to Mongodb pod </h4>
<img src ="https://github.com/Annoyshah/Hello_kubernetes/blob/main/Images/demo-proj1.png">
<img src ="https://github.com/Annoyshah/Hello_kubernetes/blob/main/Images/demo-proj2.png">
<img src ="https://github.com/Annoyshah/Hello_kubernetes/blob/main/Images/demo-proj3.png">
<img src ="https://github.com/Annoyshah/Hello_kubernetes/blob/main/Images/demo_proj4%20(copy%201).png">
