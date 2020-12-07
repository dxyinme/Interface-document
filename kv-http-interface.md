
Set
```
method : POST
contentType : "application/json"
requestBody: {
    key: string,
    value: string
}

responseBody: {
    key: string,
    errorCode: integer
}
```

Delete
```
method : DELETE
contentType : "application/json"
requestBody: {
    key: string
}

responseBody: {
    errorCode: integer
}
```

Get
```
method : GET
contentType : "application/json"
requestBody: {
    key: string
}

responseBody: {
    value: string
    errorCode: integer
}
```


error code 
```
-1  otherError
0   OK
1   NewKey
2   NoSuchKey
```