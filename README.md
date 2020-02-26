# dask-ray-modin
Performance checking of Dask and Ray using Modin Pandas

The datasets used for this experiment are from Kaggle which are as follows:
* Kiva_loans.csv (https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding/data)
* Parking.csv (https://www.kaggle.com/new-york-city/nyc-parking-tickets)

Since Dask and Ray are still in experimental stage, most of the apis are not yet implemented. But when you run your pandas using 
Ray or Dask you can certainly see the difference in the standalone machine.

Here is the link for the medium post on the same.

https://medium.com/sfu-big-data/up-the-data-processing-ante-with-pandas-modin-ray-b354bb9401
