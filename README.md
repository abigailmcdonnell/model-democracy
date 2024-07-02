# model-democracy
Does discounting ‘hot’ climate models improve the predictive skill of climate model ensembles?

Abigail McDonnell, Adam Michael Bauer, Cristian Proistosescu

To run on google colab:
Please update the mount to import the pre-processed dataset. Also, make a shortcut to your Google drive with the shared folder. 
This can be done by right clicking on the shared "Abigail_McDonnell" folder, selecting "Add shortcut to Drive", and clicking on the "MyDrive" option.
Here is an example of a mounted drive: 

ds = xr.open_dataset('/content/drive/MyDrive/Abigail_McDonnell/global_data_processed_precip.nc')

| Figure        | Source File     |
|---------------|-----------------|
| Figure 1a: Shows weighted and unweighted mean temperature projections with weights based on historical temperature trends for the chosen pseudo-observation  | `example_temp.ipynb`  |
| Figure 1b: Shows weighted and unweighted mean precipitation projections with weights based on historical temperature trends for the chosen pseudo-observation     | `example_precip_temp.ipynb`  |
| Figure 1c: Shows weighted and unweighted mean precipitation projections with weights based on historical precipitation trends for the chosen pseudo-observation      | `example_precip.ipynb`  |
| Figure 1d: Shows weighted and unweighted mean temperature projections with weights based on the pseudo-observation’s historical temperature trend.      | `temp_weights.ipynb`  |
| Figure 1e: Shows weighted and unweighted mean precipiation projections with weights based on the pseudo-observation’s historical temperature trend.       | `preciptemp_weights.ipynb`  |
| Figure 1f: Shows weighted and unweighted mean precipiation projections with weights based on the pseudo-observation’s historical precipitation trend.       | `precip_weights.ipynb`  |
| Figure 2a: Shows the spatial distribution of the relative RMSE between the raw temperature ensemble mean and our historical temperature trend-derived weighting technique.       | `regional_analysis.ipynb`  |
| Figure 2c: Shows the spatial distribution of the relative RMSE between the raw precipitation ensemble mean and our historical temperature trend-derived weighting technique.       | `reigonal_analysis_precip_temp.ipynb`  |
| Figure 2e: Shows the spatial distribution of the relative RMSE between the raw precipitation ensemble mean and our historical precipitation trend-derived weighting technique.       | `reigonal_analysis_precip_precip.ipynb`  |
| Figure 2b, d, f: Shows the variance in future regional temperature anomalies that is explained by historical global temperature trends.     | `preprocessing_all.ipynb`  |


