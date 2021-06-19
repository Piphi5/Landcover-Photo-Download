# Landcover-Photo-Download

This notebook serves to download GLOBE Landcover photos from the `FrontiersData.csv` file that contains the data from the [GLOBE Observer and the GO on a Trail Data Challenge: A Citizen Science Approach to Generating a Global Land Cover Land Use Reference Dataset](https://www.frontiersin.org/articles/10.3389/fclim.2021.620497/full) paper. The downloaded photos are mentioned in that paper and stored on the [GLOBE Website](https://observer.globe.gov/get-data/land-cover-data).

The photos are downloaded with the following naming convention:
`GOLC_[measureLatitude]_[measureLongitude]_[siteName]_[SiteElevation]m_[yyyymmdd]_[landCoverId]_{directionNumber}
    [direction]_[MCD12Q1_006_LW_label]_[muc_code]_IGBP[MCD12Q1_006_LC_Type1][MCD12Q1_006_LC_Type1_label]_
    {surfaceConditions=True}_[locationMethod][accuracy_m]m_ widthXheight.jpg`.

Such a naming convention allows important data regarding the photo to be extracted from the name and therefore lets the photo be useful without the original data. 
