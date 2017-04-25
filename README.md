# yopeso-evaluation
A short application challenge used as a basis for evaluation

Create an application that displays the weather information.

The weather data should be taken from this api: http://openweathermap.org/forecast16. The parameters you should send to the api: your current latitude & longitude and number of days to retrieve the weather (16). In order to be able to retrieve the data, you also need to have an api key, which you can get from here: http://openweathermap.org/appid

After you retrieve the data, save it locally (take care that if you perform many requests fast, then your api key will get “banned”).

You should display the data from the api on the screen like this: <img src="https://github.com/alexmiclea/yopeso-evaluation/blob/master/row.png" alt="Forecast Row"/> You can take the image to be displayed for each weather row using this format: http://openweathermap.org/img/w/ICON_KEY.png. For instance, for the cloud icon use “03d”: http://openweathermap.org/img/w/03d.png

Write unit tests for your code!
