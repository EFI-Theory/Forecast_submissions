# EFI Theory

A repository for forecast development and analysis as part of the Ecological Forecasting Initiative (EFI) Theory Working Group.

We are currently working on developing forecast models that can be used across multiple NEON data streams in the Ecological Forecasting Initiative's forecast challenge. Code to run forecasts is in ./Generate_forecasts, with subfolders for each forecast model. Models are run automatically every day through github actions.

If you are interested in joining the project, we would love for you to help! See contact information for Abby Lewis below to get in touch. Here are some possible places to start:
- ./Generate_forecasts/temp_lm/forecast_model.R provides a good starting point with a very basic linear model
- ./Generate_forecasts/ETS/forecast_model.R provides a good start point for a time series model

Automation is done using .yml files, which you can find and modify in .github/workflows

Please note, we are adding the prefix "tg_" to the start of all theory group models for consistency. 

## Contact

- Abigail Lewis, Virginia Tech, aslewis@vt.edu
