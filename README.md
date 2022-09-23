<p align = "center" draggable=”false” ><img src="prophet.png" 
     width="200px"
     height="auto"/>
</p>

# stock-predictor

Predict stock market prices using Prophet.

Check https://finance.yahoo.com/lookup for trending tickers

Choose your ticker and the number of days from today

Use curl to access aws EC2 instance:

curl --header "Content-Type: application/json" --request POST --data '{"ticker":"MSFT", "days":7}' http://35.78.66.0:8000/predict