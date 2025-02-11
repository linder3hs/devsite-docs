# Change store status

The peformance statuses are defined as follows:

* **Enabled**: the store is open and ready to take orders.
* **Paused**: the store is paused and will not be able to receive new orders, but it will continue to be displayed in the Mercado Pago app.
* **Disabled**: the store is closed, it will not be able to receive new orders and will no longer be displayed in the Mercado Pago app.

To change them, you must perform a PUT sending the `store_id` and `access-token` (generated by the OAuth authentication process) to the endpoint [/proximity-integration/stores/{store_id}/status](/developers/en/reference/mp_delivery/_proximity-integration_stores_store_id_status/put). See [Security](/developers/en/guides/additional-content/security/oauth/introduction) for more information about OAuth.