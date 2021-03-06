## Device Details

Details about the device that took the payment.

### Structure

`DeviceDetails`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `DeviceId` | `string` | Optional | Square-issued ID of the device. |
| `DeviceInstallationId` | `string` | Optional | Square-issued installation ID for the device. |
| `DeviceName` | `string` | Optional | The name of the device set by the merchant. |

### Example (as JSON)

```json
{
  "device_id": "device_id6",
  "device_installation_id": "device_installation_id8",
  "device_name": "device_name2"
}
```

