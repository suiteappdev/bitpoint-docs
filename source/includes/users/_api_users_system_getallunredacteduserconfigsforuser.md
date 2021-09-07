## GetAllUnredactedUserConfigsForUser

**Category:** System<br />**Permissions:** Operator, Trading<br />**Call Type:** Synchronous

Gets all the unredacted configs for a user

### Request

```json
{
    "userId": 0,
    "userName": ""
}
```

| Key      | Value                                                        |
| -------- | ------------------------------------------------------------ |
| userId   | **integer.** The ID of the user whose configuration key-value pairs you want to return. |
| userName | **string.** The user name of the user whose configuration key-value pairs you want to return. |

### Response

```json
[
    {
        "Key": "Config1",
        "Value": "Config1Val"
    }
]
```

The Response returns an array of a variable number of elements, depending on the needs of the Exchange.

| Key   | Value                                                        |
| ----- | ------------------------------------------------------------ |
| Key   | **string.** The name of the key part of the key-value pair.  |
| Value | **string.** The value part of the key-value pair. The value must be a string. |


