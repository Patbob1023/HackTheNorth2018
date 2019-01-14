# HackTheNorth2018
A novel investing assistance allowing for split-second identification of investment opportunities through image recognition

## What it does
The web application takes an image as an input and uses machine learning to identify key objects within the image. It then scours the internet to find publicly-trade companies with exposure to these detected objects. Next, the application retrieves real-time data about the stock via the Alpha Vantage API and computes historical and real-time datapoints to predict future movement in the stock price. This information is clearly conveyed to the user - all in under a second.

## How I built it
The front-end of the web application was built using HTML, CSS, and JavaScript, while much of the machine learning and prediction was done with Python. APIs such as Clarifai and Alpha Vantage enabled us to quickly perform tasks such as image recognition and data retrieval.

## Contributors
I would like to thank my teammates Max, Aidan, and Ryan, all of whom helped immensely with this project. It was a pleasure working with them at Hack the North 2018.

## License
[MIT](https://choosealicense.com/licenses/mit/)
