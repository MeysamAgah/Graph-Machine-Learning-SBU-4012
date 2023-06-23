# Assignment #4
In this Assignment I answered marked question from [this file](https://github.com/MeysamAgah/Graph-Machine-Learning-SBU-4012/blob/main/Assignments%20and%20Homeworks/Assignment%234/CS224W_Winter2223_HW1.pdf)

![2 1](https://user-images.githubusercontent.com/113939902/234376572-e34d1ea7-4715-42fb-b04a-f42b67c8a854.png)
<br> 
this is for left graph <br>
![2 1 Left Graph](https://user-images.githubusercontent.com/113939902/234395211-48e7ff66-4cc1-47b5-9509-9c24babf36bb.png)
<br> 
this is for right graph <br>
![2 1 Right Graph](https://user-images.githubusercontent.com/113939902/234395341-c5427022-ff3b-4abd-b040-40f6d572653b.png)
<br>
As you see 3 layers of message passing needed to distinguish between 2 nodes
![2 3](https://user-images.githubusercontent.com/113939902/234376847-f7870c54-c327-4cb0-bc9a-93c507b1cc6e.png)

![2 6](https://user-images.githubusercontent.com/113939902/234376887-73692cc0-d68b-4b9f-b38d-3c4bb0929ea5.png)

![4 1](https://user-images.githubusercontent.com/113939902/234376913-2369788f-2a96-493e-9146-117b22701ec9.png)
<br>In order to solve this exercise Trying node mapping methode :<br>
(A,1) <br>
(B,5) <br>
(C,6) <br>
(D,2) <br>
(E,4) <br>
(F,8) <br>
(G,7) <br>
(H,3) <br>
so graphs are isomorphism
![4 2](https://user-images.githubusercontent.com/113939902/234376926-4d3d0bdb-9e84-4f57-833a-ac58efd482ea.png) <br>
![4.2](https://raw.githubusercontent.com/MeysamAgah/Graph-Machine-Learning-SBU-4012/main/Assignments%20and%20Homeworks/Assignment%234/4.2.png)<br>
at above figure we call left graph G1 and right one G2. mean of both graphs are 2 and max of both graphs are 3, this proove that in each kind of case we may need to use one of aggregation function to become able to make difference between grahs
![4 3](https://user-images.githubusercontent.com/113939902/234376946-05496175-29aa-4be1-8a88-ec6d772d92b4.png)<br>
![4 3 1](https://user-images.githubusercontent.com/113939902/234376966-d40d9adf-95f4-4c13-a29b-f90d1b213522.png) <br>
We try to use proof by contradition to show WL test not able to decide whether graphs are isomorphism or not after k iterations. by implementing algorithm and observing result we see that we have two embbeded graphs with at leats two feature representation vectors at k-th iteration then we'll have 2 different results. <br>
first, if two feature representation vectors are same then it means each node of G1 and its edges are same as a node in G2 and its edges and according to this test is ale to decide graphs are isomorphism or not.<br>
second, if two feature representation vectors are not same then that means there is a node in G1 which its feature representation is different from G2 and again test can decide graphs are isomorphis or not.<br>
we can conclude that test can decide whether graphs are isomorphis or not and according to question we have 2 graphs with same embedding and same aggregation and combine function that are not isomorphis and according to proof WL test also decides the graphs are not isomorphic.

