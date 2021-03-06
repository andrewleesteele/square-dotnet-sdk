## Balance Payment Details

Reflects the current status of a balance payment.

### Structure

`BalancePaymentDetails`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `AccountId` | `string` | Optional | ID for the account used to fund the payment. |
| `Status` | `string` | Optional | The balance payment’s current state. Can be `COMPLETED` or `FAILED`. |

### Example (as JSON)

```json
{
  "account_id": "account_id2",
  "status": "status8"
}
```

