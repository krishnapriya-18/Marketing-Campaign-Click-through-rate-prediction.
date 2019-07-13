# Marketing-Campaign-Click-through-rate-prediction.

AIM:

- Developed workflow for CTR prediction and suggested important metrics for
getting more ROI.
- Suggested important insights on campaign running time and day, banner
positions for display campaigns etc.


PROCESS:

- Trained the model on available CTR data from now one of the google’s acquired
company.
- Machine Learning models: Obtained best accuracy of results with tuned XGBoost
model.

ABOUT THE DATA:

- Training set - 10 days of click-through data, ordered chronologically.
- Test set - 1 day of ads for testing your model predictions.
- id: ad identifier
- click: 0/1 for non-click/click
- hour: format is YYMMDDHH, so 14091123 means 23:00 on Sept. 11, 2014 UTC.
- banner_pos
- Site features - Site_id, Site_domain, Site_category
- App features - app_id, app_domain
- Device features - device_type, device_conn_type
- C1,C14 - C21 - Anonymized categorical variables

