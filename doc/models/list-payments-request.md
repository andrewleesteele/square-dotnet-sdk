## List Payments Request

Retrieves a list of payments taken by the account making the request.

Max results per page: 100

### Structure

`ListPaymentsRequest`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `BeginTime` | `string` | Optional | Timestamp for the beginning of the reporting period, in RFC 3339 format.<br>Inclusive. Default: The current time minus one year. |
| `EndTime` | `string` | Optional | Timestamp for the end of the requested reporting period, in RFC 3339 format.<br><br>Default: The current time. |
| `SortOrder` | `string` | Optional | The order in which results are listed.<br>- `ASC` - oldest to newest<br>- `DESC` - newest to oldest (default). |
| `Cursor` | `string` | Optional | A pagination cursor returned by a previous call to this endpoint.<br>Provide this to retrieve the next set of results for the original query.<br><br>See [Pagination](https://developer.squareup.com/docs/basics/api101/pagination) for more information. |
| `LocationId` | `string` | Optional | Limit results to the location supplied. By default, results are returned<br>for the default (main) location associated with the merchant. |
| `Total` | `long?` | Optional | The exact amount in the total_money for a `Payment`. |
| `Last4` | `string` | Optional | The last 4 digits of `Payment` card. |
| `CardBrand` | `string` | Optional | The brand of `Payment` card. For example, `VISA` |
| `Limit` | `int?` | Optional | Maximum number of results to be returned in a single page.<br>It is possible to receive fewer results than the specified limit on a given page.<br><br>If the supplied value is greater than 100, at most 100 results will be returned.<br><br>Default: `100` |

### Example (as JSON)

```json
{}
```

