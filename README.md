# making_noise
In this repo I explore some methodologies for procedural map making using noise. 
the basic idea is the following:

1. generate some noise matrix using numpy 
2. using kroneker product to scale up the noise and make it fine/large
3. apply some gaussian filters to smooth the results
4. average all the matrices together 
5. plot them in a 3d surface with some adequate color scheme
6. implement the perlin noise algorithm 
7. test performance of both 
8. develop and test some filters 

__some example of the generated maps__

![map2](https://github.com/fmerizzi/making_noise/blob/master/Figure%2018.png)

![map1](https://github.com/fmerizzi/making_noise/blob/master/Figure%207.png)

__noise__


![map1](https://github.com/fmerizzi/making_noise/blob/master/movie%20(1).gif)
