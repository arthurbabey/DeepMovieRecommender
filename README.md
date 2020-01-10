# DeepMovieRecommender
This repository contains the code and dasaset (MovieLens-100k) to perform a graph convolutional matrix completion in order to predict movie ratings. The method is based based on Van der Berg et al. work, we use their source code which can be found here: [Github repository](https://www.github.com/riannevdberg/gc-mc).



 # How to run the code
 
 First you will need to install the external libraries listed below. 
 To obtain extended features by scrapping you can run the get_imdb_id.ipynb notebook.
 Then to load the data, visualize them, build features matrix and train the model you can run the ntds_project.ipynb notebook.



 # Contributors

- Nessreddine Loudiy [@Loudiy](https://github.com/Loudiy)
- Stanislas Ducotterd [@StanislasDucotterd](https://github.com/StanislasDucotterd)
- Lamyae Omari Alaoui [@lomarial](https://github.com/lomarial)
- Arthur Babey [@arthurbabey](https://github.com/arthurbabey)

 # Python and external libraries

This project has been developped using `Python 3.6.9`.
We use the following libraries with the mentionned version.

```bash
 Tensorflow==1.8.0, 
 Scipy==1.2.1, 
 Numpy==1.16.2, 
 Pandas==0.25.2,
 Networkx==2.2,
 Pgeocode==0.2.0
```

 
 
# Repo structure
<pre>
.
├── README.md                   
│                           
├── movielens-100k           data set
│                               
├── get_imdb_id.ipynb        scrapping notebook
│  
├── ntds_project.ipynb       main notebook
│ 
├── model.py                 model implementation
├── data_utils.py            util function
├── layers.py                layers for model 
├── metrics.py               metrics function
├── run_gcmc.py              training 
├── preprocessing.py         preprocessing function
├── utils.py                 util function
├── train_mini_batch.py      mini_batch training
├── initialization.py        variable initialization
├── __intit__.py       

   
</pre>
