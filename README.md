# NaiveDemandForecaster
A simple model that generates scenario based projections (aka forecasts) for grid-delivered electricity. Wrapped in a Shiny app. See this link to use the app: https://coble-neal.shinyapps.io/DemandForecaster/ 

To do list:
~~- Adjust the E_auto slider to better match the initial level of demand. ~~
- Add sliders for maximum penetration ratios of solar PVs and EVs as a proportion of total houses.
- Add commercial and industrial demand for electricity.
- Add ability to impose shocks on input variables after the initial time period.
- Integrate with a translog cost function to drive the price of electricity, taking number of houses and average demand per house as inputs.
