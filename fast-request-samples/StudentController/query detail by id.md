# query detail by id

> URL: http://localhost:8081/student/1
>
> Origin Url: http://localhost:8081/student/{id}
>
> Type: GET


### Request headers

|Header Name| Header Value|
|---------|------|

### Parameters

##### Path parameters

| Parameter | Type | Value | Description |
|---------|------|------|------------|
|id|Number|1|student id|


##### URL parameters

|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Body parameters

###### JSON

```

```

###### JSON document

```

```


##### Form URL-Encoded
|Required| Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


##### Multipart
|Required | Parameter | Type | Value | Description |
|---------|---------|------|------|------------|


### Response

##### Response example

```
{
  "code": 1,
  "message": null,
  "data": {
    "id": 1,
    "name": "kings",
    "age": 20,
    "gender": 1
  }
}
```

##### Response document
```
{
	"code":"返回码, 0为成功, 其他值为失败",
	"message":"描述内容, 一般在code不为0时有意义",
	"data":{
		"id":"id",
		"name":"名字",
		"age":"年龄",
		"gender":"性别 sex[0-unknown 1-female 2-male]"
	}
}
```


