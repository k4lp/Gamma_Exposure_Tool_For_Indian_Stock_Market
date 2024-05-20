This is basic form that asks you for a One time token from your broker. This is needed in order to get AuthToken for the day.
![Screenshot (1)](https://github.com/k4lp/Gamma_Exposure_Tool_For_Indian_Stock_Market/assets/61631873/9c74148d-6554-4fcc-82e5-36c0a4906a4b)

This is Raw calculations from Gamma exposure profile, calculated using the base formula and indicates nothing more.
![Screenshot (8)](https://github.com/k4lp/Gamma_Exposure_Tool_For_Indian_Stock_Market/assets/61631873/05fb0e7c-e327-4368-9cf0-e2b5dfceeffb)

This is proprietary calculations which differs from the raw spot GEX data. This is done by ignoring some options and putting heavy weightage on other options by looking at the volume, price difference between different time frames ,volume SMAs and EMAs combined with RSI value and Bollinger Bands. When the chart has mostly positive bars, the market is flat and going up. When there is negative bars above the spot price, It may go down. When every bar is negative, The market is volatile and it may crash anytIme.
![Screenshot (3)](https://github.com/k4lp/Gamma_Exposure_Tool_For_Indian_Stock_Market/assets/61631873/1a6bdaf8-d458-4265-9002-347f1570c494)
