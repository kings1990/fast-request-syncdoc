# add book12345
> URL: http://localhost:8081/book/add
>
> Origin Url: http://localhost:8081/book/add
>
> Type: POST


### Request headers

|Header Name| Header Value|
|---------|------|

### Parameters

##### Path parameters

| Parameter | Type | Value | Description |
|---------|------|------|------------|


##### URL parameters

|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Body parameters

###### JSON

```

```

###### JSON Document

```

```


##### Form URL-Encoded
|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|
|true|id|Number|1|book id|
|true|name|String|Effective Java|book name|
|true|createTime|String|2001-10-11 09:17:16|book name|
|true|description|String|Skills of java|book description|


##### Multipart
|Required | Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


## Response Example
```
{
  "id": 1,
  "name": "Effective Java",
  "createTime": "2001-10-11T09:17:16",
  "description": "Skills of java"
}
```


