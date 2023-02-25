---------------------------
OneLayer_AE_model.ipynb:
AE model:
    - MINST dataset
    - | 784 -> 512 | -> | 512 -> 10 | -> | 10 -> 512 | -> | 512 -> 748 |
    -  based on: https://www.cs.toronto.edu/~lczhang/360/lec/w05/autoencoder.html and https://pytorch.org/tutorials/beginner/basics/intro.html
    
---------------------------

# 25.02.2023  
*Code durchgehen*  

Next Steps: 
* models speichern 
* AE, VAE, UMAP, PCA, PCA+UMAP (search for source)  
* neues notebook für comparison   
* optimierung der Autoencoder  
        * overfit testing  
        * auf test daten schmeißen
        * Validation daten ?  
* Notebook für comparsion   
* evaluation plots
* descision über fine tuning der Models - ja/nein  
 
* Documentation mit links und literatur füllen! 

Arbeitspaket 2: 
* sc daten suchen und darauf schmeißen 
* Fragestellung genauer spezifizieren (andere Model? nur unsere Model? Was genau wollen wir erreichen? Eigentlich ja den step von "beispiel --> realworld") 
* anwendung dann nur auf trainingsset oder auch verwandten experimenten?  

**open questions**  

* [cluster anaylse](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html)  
* richtiger umgang k-means? fit oder fit_predict  
* 
