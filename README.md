# An Empirical Study On Duplicate Bug Report Identification Using Siamese Cross-Encoder Network

This project replicates "Towards Accurate Duplicate Bug Retrieval Using Deep Learning Techniques" 
by Jayati Deshmukh, K. M. Annervaz, Sanjay Podder, Shubhashis Sengupta, and Neville Dubash
in International Conference on Software Maintenance (ICSM) 2017.
We show that even without handling structured information separately, we can achieve
comparable performance with respect to the original work.

## Dataset
Download and store the dataset into MongoDB from [here](http://alazar.people.ysu.edu/msr14data/).
If you are using Docker for MongoDB, you can find the `docker-compose.yaml` file in the root directory.

# Installing Packages
We highly encourage to use a virtual environment to run the project.
You can find the list of necessary packages in the `requirements.txt` file in the root directory.
Install them by running
```shell
pip install -r requirements.txt
```

## Run
Start a jupyter server by running
```shell
jupyter notebook
```
Then open `notebooks/siamese-trials/title-descr-eclipse.ipynb` in the jupyter app.
To see result for different datasets, change the third line in the second cell accordingly.

## Result
Check `project-report.pdf` for detailed analysis of the evaluation and findings.
