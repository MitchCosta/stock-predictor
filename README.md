<p align = "center" draggable=”false” ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxnJjqd48VnXk-EoDT6XVO78MlHEX5SXkczQVJEYzmd_CQJGZCyUroKPuPVUAJ2JlMJOc&usqp=CAU" 
     width="200px"
     height="auto"/>
</p>

# stock-predictor

Predict stock market prices using Prophet.

Check https://finance.yahoo.com/lookup for trending tickers

Choose your ticker and the number of days from today

Use curl to access aws EC2 instance:

curl --header "Content-Type: application/json" --request POST --data '{"ticker":"MSFT", "days":7}' http://35.78.66.0:8000/predict