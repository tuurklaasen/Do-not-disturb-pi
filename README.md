# Do-not-disturb-pi
In this file you will find the explanation to create a do not disturb pi  
1)Install node-red on your pi  
2)Find the ip-address off the pi in the terminal 'hostname-I'  
3)Start the server in terminal 'node-red start'  
4)Go to the ip-address of the pi in the browser, add the port after the ip-address  
5)For the nodes:   
   1-Red sense hat:  
  add a inject, a change and a SenseHat node  
  Change the properties of the change node like the photo below:  
  then connect the inject node to the change node and the change node to the sense hat node  

![red sense hat](https://user-images.githubusercontent.com/46092824/78166537-3e046280-744d-11ea-8b41-5978541317c1.png)

  2-Green sense hat:  
  add a inject and a change node  
   Change the properties of the change node like the photo below:  
  then connect the inject to the change node and the change node to the first SenseHat node  

![green sense hat](https://user-images.githubusercontent.com/46092824/78167011-05b15400-744e-11ea-8fe1-8a165405bbf8.png)

  3-For the off button repeat step '2-' and change green to off  

6)You can add a shutdown button by adding a inject and an exec node: and change the properties of the exec node like the photo below  

![shutdown](https://user-images.githubusercontent.com/46092824/78167263-7bb5bb00-744e-11ea-933a-26b9838fd53d.png)

If you did all that you should have a flow like this:  
![image](https://user-images.githubusercontent.com/46092824/78167429-c2a3b080-744e-11ea-8bc3-4fc99413b98f.png)

