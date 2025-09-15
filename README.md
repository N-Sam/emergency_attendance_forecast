# Healthcare Emergency Forecast

While doing this forecasting project, my main goal was to recommend a suitable forecasting method for an NHS acute trust and provide a twenty-eight-day forecast of the daily number of paediatric emergency attendance. After a careful evaluation and comparison of the suitable method with a naive benchmark on a twenty-eight-day forecast result, using the root mean square error score(RMSE) scores of these methods on test data, I decided which method is the best for the NHS Trust to forecast the daily number of pediatric emergency attendances at the hospital. The least RMSE value shows which method would be the most suitable for their data to support them with planning their staffing decision to sufficiently handle pediatric emergency attendances. which was “Prophet” as it produced the lowest error score.

[openincollab](http://colab.research.google.com/github/N-Sam/emergency_attendance_forecast/)

## To reproduce this notebook on a local machine;
1. Create a conda environment using the file environment.yml included in this folder

It works better on OpenStack.
on the existing hds_forecast conda environment.
2 . The data set was deployed on a GitHub repository and linked to the notebook using a URL provided in the notebook.

Thanks.
