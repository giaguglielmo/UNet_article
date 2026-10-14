# UNet_article
Dataset for article "Transferability assessment of U-net model for rapid large-scale flood prediction over unseen catchments"

Data Structure

The dataset is provided in the data_article_UNet.zip archive, which contains the following directory structure and file:

data_article_UNet.zip
├── train basin/
│   ├── dem/
│   │   ├── elevation.tif
│   │   ├── slope.tif
│   │   ├── aspect.tif
│   │   ├── ti.tif
│   │   └── mask/
│   │       └── mask.tif
│   ├── depths/
│   │   └── depth_<rainfall_level>.tif
│   ├── velocities/
│   │   └── velocity_<rainfall_level>.tif
│   └── rainfall.csv
├── test basin/
│   └── ... (same structure as "train basin")
└── hec-ras hydrograph data.xlsx

The archive must be extracted before accessing the individual files.
