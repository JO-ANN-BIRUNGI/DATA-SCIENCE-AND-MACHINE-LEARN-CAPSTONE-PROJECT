# DATA-SCIENCE-AND-MACHINE-LEARN-CAPSTONE-PROJECT
Forecasting Daily Air Temperature in Doho, Uganda Using Machine Learning and Deep Learning Approaches
This project aimed to forecast daily air temperature in Doho, Uganda, using historical weather data from multiple stations (2013–2016). Accurate temperature predictions are essential for agriculture, energy planning, and disaster preparedness, where reliable forecasts inform critical operational decisions.

The dataset included daily measurements of air temperature, humidity, minimum and maximum temperatures, and station identifiers. Feature engineering was applied to capture temporal and seasonal patterns, including lag variables (1–14 days), rolling statistics (7-day averages and standard deviations), date-based features (month, day-of-year, weekday), and one-hot encoded station identifiers.

Three modeling approaches were employed:

Random Forest Regressor (RF): Classical machine learning model capturing nonlinear relationships.

Long Short-Term Memory (LSTM): Sequential deep learning model capable of learning temporal dependencies.
Model performance was evaluated using Mean Squared Error (MSE), Mean Absolute

Recommendations for Stakeholders

Farmers and Agricultural Planners
Use the daily temperature forecasts to optimize irrigation schedules and crop protection strategies.

Align planting and harvesting decisions with predicted temperature trends to reduce crop stress and increase yield.

Combine temperature forecasts with rainfall and humidity data for precision agriculture.

Energy Providers
Incorporate forecasts into demand planning, as electricity consumption often varies with temperature.

Use predictions to manage load distribution and prevent outages during temperature extremes.

Plan maintenance of energy infrastructure during predicted mild temperature periods.

Disaster Management Authorities
Utilize forecasts to anticipate heatwaves or cold spells, improving early warning systems.

Prepare communities for temperature-related health risks or crop/animal stress events.

Integrate temperature predictions with rainfall and wind forecasts for holistic disaster preparedness.

Urban Planners and Local Governments
Use temperature forecasts to inform public services, e.g., cooling shelters during heatwaves.

Plan infrastructure maintenance (roads, water systems) considering seasonal temperature variations.

Support local climate adaptation strategies with data-driven insights.

Research and Policy Makers
Employ the models for climate trend analysis and urban heat planning.

Use the predictions to design policies for climate-resilient agriculture and energy use.

Extend the methodology to other regions or additional weather variables for broader applications.

General Recommendation

LSTM model is preferred for operational use due to its superior accuracy in capturing temporal and seasonal patterns.

Regularly update the models with new weather data to maintain forecast accuracy.

Combine temperature forecasts with other meteorological variables (rainfall, humidity, wind) for more comprehensive weather decision support.
