# load-balancer
Load Balancer fir dynamic routes

1. Here, I have implemented the load baka=lancer using the below types

    a.priroity routes based on high or low priority field in the request body
    b.fast/slow routes based on the payload size
    c.we can redirect to routes based on the field "userrole" (either it is admin or normal user), etc..
    d. default, we can retur the server by round robin algo

2. For the queueing, we have used here 3 queues
    a.FIFO queues
    b.Priroity queues
    c.Round Robin





