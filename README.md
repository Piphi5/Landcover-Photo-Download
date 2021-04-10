# Landcover-Photo-Download

This notebook serves to download GLOBE Landcover photos from the `FrontiersData.csv` file with the following name convention: `GOLC_[measureLatitude]_[measureLongitude]_[siteName]_[SiteElevation]m_[yyyymmdd]_[landCoverId]_{directionNumber}
    [direction]_[MCD12Q1_006_LW_label]_[muc_code]_IGBP[MCD12Q1_006_LC_Type1][MCD12Q1_006_LC_Type1_label]_
    {surfaceConditions=True}_[locationMethod][accuracy_m]m_ widthXheight.jpg`.

Such a naming convention allows important data regarding the photo to be extracted from the name and therefore lets the photo be useful without the original data. 
