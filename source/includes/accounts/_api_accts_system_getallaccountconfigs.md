## GetAllAccountConfigs

**Category:** System <br />
**Permissions:** Operator <br />
**Call Type:** Synchronous

Retrieves a list of Key/Value pairs of a key across all Accounts


### Request

```json
{
    "key": "Config1",
}
```

| Key        | Value                                                        |
| ---------- | ------------------------------------------------------------ |
| key      | **string.** The key to retrieve from all accounts.  ||

### Response

```json
[
    {
        "AccountId": 0,
        "Key": "Config1",
        "Value": "Config1Val",
    },
]
```

The Response is an array of positions for the account by product.

| Key                        | Value                                                        |
| -------------------------- | ------------------------------------------------------------ |
| accountId                  | **integer.** The ID of the account that holds this config. |
| key              | **string.** The key of the account config. |
| value              | **string.** The value of the account config. |


