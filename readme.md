# Neural Storeyteller

Neural Storyteller is a recurrent neural network that generates little language description about images and their region. We first train a recurrent neural network (RNN) decoder on a source book which contains a lot of passages. Then we map each passage from the source to a skip-thought vector. The RNN then condition the skip-thought vector and aims to generate the passage that it has encoded. Along with this we will train a visual-semantic embedding COCO images and captions. The caption images are then map into a common vector space. After that we will embed new image and retrieve caption and generates a language description of that image.

![alt text](ppt/1.png)
![alt text](ppt/2.png)
![alt text](ppt/3.png)
![alt text](ppt/4.png)
![alt text](ppt/5.png)
![alt text](ppt/6.png)
![alt text](ppt/7.png)
![alt text](ppt/8.png)
![alt text](ppt/9.png)
![alt text](ppt/10.png)
![alt text](ppt/11.png)
![alt text](ppt/12.png)
![alt text](ppt/13.png)
![alt text](ppt/14.png)
![alt text](ppt/15.png)
![alt text](ppt/16.png)
![alt text](ppt/17.png)
![alt text](ppt/18.png)
![alt text](ppt/19.png)
