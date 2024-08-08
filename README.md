# How to detect deforestation
To simplify the detection, the model will detect forested areas instead of the deforestation itself. Everything that isn't detected should be the deforested areas.
Highly recommended using Anaconda virtual environments to make tensorflow easier to install and work with. The project was made with Python3.10.9.

After treating the GEOtiff images from the dataset with fix_dataset.ipynb simply run the training notebook.
If you already have a trained model, the training cell can be skipped


# References

##AMAZON dataset
<div class="csl-bib-body">
  <div class="csl-entry">Bragagnolo, L., da Silva, R. V., & Grzybowski, J. M. V. (2021). Amazon and Atlantic Forest image datasets for semantic segmentation [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4498086</div>
</div>