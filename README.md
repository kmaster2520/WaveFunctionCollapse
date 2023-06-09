# Wave Function Collapse

This code base generates images generated using Wave Function Collapse. 
More info is found [here](https://github.com/mxgmn/WaveFunctionCollapse).
However, that repository using an image file as an input, whereas this repository
uses a tilemap and configuration files to describe tile properties. 

Inspired by [Coding Train](https://thecodingtrain.com/challenges/171-wave-function-collapse),

To generate a simple wave function collapse, type:
```commandline
python main.py
```

Which would generate and image like:
![alt text](./samples/pipes.png)


Specific configurations can be applied:
```commandline
python main.py -c nospace
```
Which generates:
![alt text](./samples/pipes_nospace.png)