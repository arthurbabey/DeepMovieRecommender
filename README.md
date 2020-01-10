# DeepMovieRecommender





 # Contributors

- Nessredine Loudiy [@Loudiy](https://github.com/Loudiy)
- Stanislas Ducotterd [@StanislasDucotterd](https://github.com/StanislasDucotterd)
- Lamyae Omari Alaoui [@lomarial](https://github.com/lomarial)
- Arthur Babey [@arthurbabey](https://github.com/arthurbabey)

 # Python and external libraries

This project has been developped using `Python 3.6`.
We use the following libraries with the mentionned version.

`Tensorflow : '2.1.0-rc1', 
 Sklearn : '0.21.3', 
 Numpy : '1.17.4', 
 Scikit-image : '0.15.0'
 Keras : '2.3.1')`
 
 
 
# Repo structure
<pre>
.
├── README.md
│                           
├── datasets            
│   └── training
│   │    ├── groundtruth                     Label images (400x400)
│   │    └── images                          Satelite images (400x400)
|   └── test_set_images                      Satelite images (608x608)
│                               
│  
├── report                                  Final report
├── scripts                                   
│   │──helpers_unet.py
│   │  
│   │──│unet.py 
│   │ 
│   ├── notebooks
│   │   ├── unet.ipynb  
│   │
│   └── best_model                      Folder to place our best model download from the link mentionned above
│         
└── submissions                         Best submission on AIcrowd
</pre>
