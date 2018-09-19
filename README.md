# netflix-zuul-api-gateway-server
creating new netflix-zuul-api-gateway-server git

# To call service using zuul use below patten
Eg: i want to call currency-exchange-service service of url = http://localhost:8000/currency-exchange/from/USD/to/INR
application-name = currency-exchange-service
uri = currency-exchange/from/USD/to/INR

- calling service using netfilx-zuul-api-gateway-server (url = http://localhost:8765/)

http://localhost:8765/{application-name}/{uri}
http://localhost:8765/currency-exchange-service/currency-exchange/from/USD/to/INR
