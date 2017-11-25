# Download Google Street View Panoramas

This project is aims to estimate the shade provision of the street trees using publicly 
accessible Google Street View panoramas and building height model in Boston. The method
can also be applied to other cities considering the massively available of Google Street
View service and the building height model information

For more details about the method check the paper 

Li and Ratti, "Mapping the spatial distribution of shade provision of street trees in Boston using Google Street View panoramas", Urban Forestry and Urban Greening. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Before you running the code, you need to have several Python modules installed on your computer. 

1. urllib
2. cStringIO
3. Numpy
4. PIL/Pillow

```
pip cStringIO
pip urllib
pip pillow
```

End with an example of getting some data out of the system or using it for a little demo

### How to use the function

Explain what these tests test and why

```
import os,os.path
panoFolder = r'/Users/senseablecity/Dropbox (MIT)/ResearchProj/ShadeProvisionBoston/code'
##panoId = 'U8B4cKDxnauFW-Yt7siKtw'
panoId = "c8gcWEqLiOcVwDrtJDiB4g"
panoImgFile = os.path.join(panoFolder,panoId + '.jpg')

GSVpanoramaDowloader_GoogleMaps(panoId,panoImgFile)
```

## Authors

* **Xiaojiang Li** - *Initial work* - [Treepedia](http://senseable.mit.edu/treepedia)

See also the list of [contributors](http://senseable.mit.edu/) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Google Maps
* Massachusetts Open Data
* etc
