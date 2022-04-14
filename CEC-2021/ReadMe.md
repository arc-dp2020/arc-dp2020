### Deep Learning Model with GA-based Visual Feature Selection and Context Integration
### IEEE Congress on Evolutionary Computation (CEC)  2021

_____________________________________________________________________________________________

# ReadME

## Datasets

The datasets usedin this paper can also be downloaded from the links below 
1. [CamVid Database](http://mi.eng.cam.ac.uk/research/projects/VideoRec/)
2. [Stanford Backgrodund Dataset](http://dags.stanford.edu/projects/scenedataset.html)


## Notes on Usage

The proposed model can be divided into 3 logical layers or modules. The first layer (i.e., the Visual Layer) is introduced to extract optimized features using a Genetic Algorithm and train the One-vs-All binary classifier. The following layer deals with contextual information that learns the global and local contexts of an image. The final layer combines all the information optimally using a noble MLP-based regression method to produce the final class label. 

User should run the SuperpixelData.m file and set the paramereters maually.
```matlab
1.  dataBases - which database to run on
2.  classifiers - fist layer classifier
3.  Integration_Layer - regression model
```


Dataset perparation: For each input image file, one label file with .txt extension needs to be provided. Some samples label files are provided.

## Publications 
If you find codes and results useful in your research, please consider citing:


    @inproceedings{9504753,
	Author = {Mandal, Ranju and Azam, Basim and Verma, Brijesh and Zhang, Mengjie},
	Title = {Deep Learning Model with GA-based Visual Feature Selection and Context Integration},
	Booktitle  = {2021 IEEE Congress on Evolutionary Computation (CEC)},
	Year = {2021},
	Pages={288-295}
    }

## Contributions / Queries 

Requests and queries are welcome. 
Please drop me an email at b.azam@cqu.edu.au
