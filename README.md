# Do-not-disturb-pi
In this file you will find the explanation to create a do not disturb pi  
1)Install node-red on your pi  
2)Find the ip-address off the pi in the terminal 'hostname-I'  
3)Start the server in terminal 'node-red start'  
4)Go to the ip-address of the pi in the browser, add the port after the ip-address  
5)For the nodes:   
Red sense hat:
add a inject, a change and a SenseHat node
Change the properties of the change node like the photo below:
then connect the inject node to the change node and the change node to the sense hat node

![red sense hat](https://user-images.githubusercontent.com/46092824/78166537-3e046280-744d-11ea-8b41-5978541317c1.png)

Green sense hat:
add a inject and a change node
Change the properties of the change node like the photo below:


![Image description](https://user-images.githubusercontent.com/46092824/78166297-d4845400-744c-11ea-9761-013546b1775b.png)
