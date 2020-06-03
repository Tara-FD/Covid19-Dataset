# Covid19-Dataset
This dataset contains 1252 CT scans that are positive for SARS-CoV-2 infection (COVID-19) and 1230 CT scans for patients non-infected by SARS-CoV-2, 2482 CT scans in total.
</br> These data have been collected from real patients in hospitals from Sao Paulo, Brazil.
The aim of this dataset is to encourage the research and development of artifical inteligence methods which
are able to identify if a person is infected by SARS-CoV-2 through the analysis of his/her CT scans.
</br> You can find this dataset on kaggle via link below:
</br> http://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset
</br>
## hint:
</br> **Use below code to read data in python:**</br>
```r
datadir = "Covid19-Dataset/SARS-Cov-2/COVID/"
Covid=[]
for img in os.listdir(datadir):
    img_array = cv2.imread(os.path.join(datadir,img),0)
    Covid.append([img_array])
```

</br>
## Citation:
</br>
Angelov, Plamen, and Eduardo Almeida Soares. "EXPLAINABLE-BY-DESIGN APPROACH FOR COVID-19 CLASSIFICATION VIA CT-SCAN." medRxiv (2020).
</br>
Soares, Eduardo, Angelov, Plamen, Biaso, Sarah, Higa Froes, Michele, and Kanda Abe, Daniel. "SARS-CoV-2 CT-scan dataset: A large dataset of real patients CT scans for SARS-CoV-2 identification." medRxiv (2020). doi: https://doi.org/10.1101/2020.04.24.20078584.
</br>Link:
</br>https://www.medrxiv.org/content/10.1101/2020.04.24.20078584v2
