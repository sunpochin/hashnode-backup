## http post blocked by CORS caused by not providing enough post body file


```
db_item = models.Item(**item.dict(), quantity=1, owner_id=-1)
```

backend respond:
```
Access to XMLHttpRequest at 'http://localhost:8000/items/add' from origin 'http://localhost:8080' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource.
```

backend showing on console:
```
pydantic.error_wrappers.ValidationError: 1 validation error for Item
response -> owner_id
  none is not an allowed value (type=type_error.none.not_allowed)
```
