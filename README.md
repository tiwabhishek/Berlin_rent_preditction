[TOC]


# [Berlin rent prediction using Machine learning](http://ec2-16-170-235-79.eu-north-1.compute.amazonaws.com "Berlin rent prediction using Machine learning").
- Use http:// to access the website.
- The development of the model is thoroughly documented in the notebook [file](model/berlin.ipynb "file").
- The [server](server "server"), util, and [web page](client "web page") files document are in this read's relevant section.md file.

#### Data procurement
- Data was procured from the kegel website with  this [Link.](https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany "Link.")
#### Data pre-processing, feature engineering, and model training.
- All of this could be found in the notebook.
#### Sever and port hosting.
- Server was created using flask module, to handle https, CORS used. Port was hosted using [Nginx](httphttps://nginx.org/en/download.html:// "Nginx"), Its [configration file](nignix_file "configration file") needs to be added in sites-availbe folder in /etc/nginx/.

#### Website and Hosting it in EC2 on AWS.
CSS, HTML, and Java script files are present [client](client "client") folder. 
An EC2 server was used to host the server and its Public address was used Which can be accessed through the link attached to the head of read.md.
