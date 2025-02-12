# Advanced Integration

## Refunds

----[mla, mlm, mco, mlu, mlb, mlc]----

Refunds happen when a payment was completed but the seller decides to cancel it partially or totally. You can find information in the [Refunds and cancellations](/developers/en/guides/additional-content/sales-processing/cancellations-and-refunds) section.

------------

----[mpe]----

Refunds happen when a payment was completed but the seller decides to cancel it totally. You can find more information in the [Refunds and cancellations](/developers/en/guides/additional-content/sales-processing/cancellations-and-refunds) section.

------------
> WARNING
> 
> Note
> 
> Remember that in the case QR payments, refunds are available but cancellations are not.

## Get order data

If you want to assign an order to a POS, you can do it using the following:

```curl
curl -X GET \
-H 'Authorization: Bearer ACCESS_TOKEN' \
https://api.mercadopago.com/instore/qr/seller/collectors/USER_ID/pos/EXTERNAL_POS_ID/orders
```
Obtain more information in our [API Reference](/developers/en/reference/instore_orders_v2/_instore_qr_seller_collectors_user_id_pos_external_pos_id_orders/get).

## Generate reports of your sales

Integrate [Mercado Pago reports](developers/en/guides/additional-content/reports/general-considerations/reconciliation-reports) with your system to make sales reconcilitation and know about your account movements.

## Test and validate your integration 

We detailed all necessary scenarios you should test to ensure your system is successfully integrated with Mercado Pago. 
Find all this information in the [Tests section](/developers/en/guides/qr-code/integration-test).

---

> NEXT_STEP_CARD_EN
>
> Test your integration
>
> Perform the most frequent use cases to validate your integration.
>
> [Test your integration](/developers/en/guides/qr-code/integration-test)
