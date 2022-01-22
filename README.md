# making_noise
In this repo I explore some methodologies for procedural map making using noise. 

1. generate noise matrices using numpy 
2. using kroneker product to scale up the noise and make it fine/large
3. apply some gaussian filters to smooth the results
4. average all the matrices with different granularity together 
5. plot them in a 3d surface with some adequate color scheme
6. implement the perlin noise algorithm 
7. test performance of both 
8. develop and test some other filters 
9. experiment with the techniques above to produce some different type of terrain/textures 

__some of the generated maps__

![map2](https://github.com/fmerizzi/making_noise/blob/master/images/simple_noise/Figure%2018.png)

![map3](https://github.com/fmerizzi/making_noise/blob/master/images/simple_noise/Figure%208.png)

![map3](https://github.com/fmerizzi/making_noise/blob/master/images/simple_noise/Figure%2018(1).png)

![map3](https://github.com/fmerizzi/making_noise/blob/master/images/simple_noise/Figure%2014.png)

__perlin texture__

![perlin](https://github.com/fmerizzi/making_noise/blob/master/images/simple_noise/perlin%20structure.png)

# Transfer of morphological information from real-world maps to procedurally genetrated ones

In this section I explore a new technique to produce noise maps with real world properties. The basic idea is to use style transfer to get all the features from world maps and transfer them into a procedurally generated map. 

The approach can be considered the opposite of hydraulic erosion, rather than simulating a real world phenomenon we extract the feature from the real world. 

The approach was mostly successful in the transfering mountain style, with the creation of valley, mountain tips. 

Details of the implementation are discussed in the notebook. 

__map before style transfer__

![before](https://github.com/fmerizzi/making_noise/blob/master/images/file_transfer_noise/before.png)

__map after style transfer__

![after](https://github.com/fmerizzi/making_noise/blob/master/images/file_transfer_noise/after.png)

![another](https://github.com/fmerizzi/making_noise/blob/master/images/file_transfer_noise/another.png)

__the image from which the style was pulled, my home town of Sondrio__

![before](https://github.com/fmerizzi/making_noise/blob/master/images/file_transfer_noise/original.png)
