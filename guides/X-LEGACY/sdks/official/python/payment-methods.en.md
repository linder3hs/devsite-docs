## Get payment methods

It is possible to consult the available payment methods and obtain a list with the details of each one using the SDK below. For details on request parameters, check the [Get payment methods](https://www.mercadopago[FAKER][URL][DOMAIN]/developers/en/reference/payment_methods/_payment_methods/get) API.

[[[
```python
import mercadopago
sdk = mercadopago.SDK("ACCESS_TOKEN")

payment_methods_response = sdk.payment_methods().list_all()
payment_methods = payment_methods_response["response"]
```
]]]