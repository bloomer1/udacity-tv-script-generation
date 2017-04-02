## TV Script Generation.
In this project, we will generate our own Simpsons TV scripts using RNNs. We will be using part of the Simpsons dataset of scripts from 27 seasons. The Neural Network we will build will generate a new TV script for a scene at Moe's Tavern.
![simpsons][image-simpsons]

```
homer_simpson:(tipsy) man, this website makes talking drunk to my wife so much safer.(frink noise)
lisa_simpson: i read it! just stick your problems.
seymour_skinner: it's your tears to see her soon!
moe_szyslak: oh my god! what are you doing? you're not so much. i lost your problem to the ripcord stuff!
```

## Installation
You only need to install [Conda](https://conda.io/docs/install/quick.html) and run the following commands:
```
conda env create -f environment.yml
source activate udacity-tv-script-generation 
```
You can open the solution by simply:
```
jupyter notebook dlnd_tv_script_generation.ipynb 
```

<!-- Images -->
[image-simpsons]: https://deadhomersociety.files.wordpress.com/2013/01/homerdefined10.png "Simpsons Moe's Tavern"
