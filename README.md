# SEANAC

The source codes, experimental test-beds and, the datasets of our paper titled 
"A One-by-One Method for Community Detection in Attributed Networks"
by [Soroosh Shalileh](https://www.hse.ru/en/org/persons/316426865) and, [Boris Mirkin](https://www.hse.ru/en/staff/bmirkin)


For more information on how to call our algorithm "SEANAC" one can 
refer to any the demo jupyter notebooks "clustering_results_Lawyers". 

Also this algorithm can be run through the terminal by calling:
        
        python SEANAC.py --Name="name of dataset in ../data" --PreProcessing="z-m" --Run=1 

Note: data sets should be stored in data directory.

For generating similar synthetic data sets, One should call "synthetic_data_generator.py" as 
this is demonstrated in Jupyter notebook "MediumSize_synthetic_data.ipynb".



If you use our code, please cite our following paper:

BibTex:

    @inproceedings{SEANAC_IDEAL,
    title={A One-by-One Method for Community Detection in Attributed Networks},
    author={S. Shalileh and B. Mirkin},
    booktitle={International Conference on Intelligent Data Engineering and Automated Learning. Lecture Notes in Computer Science, vol 12490. },
    pages={413--422},
    year={2020},
    address={Guimarães, Portugal}}
    
Or:


Shalileh S. & Mirkin B. (2020) A One-by-One Method for Community Detection in Attributed Networks. In: Analide C., Novais P., Camacho D., Yin H. (eds) Intelligent Data Engineering and Automated Learning – IDEAL 2020. IDEAL 2020. Springer, Cham. 
