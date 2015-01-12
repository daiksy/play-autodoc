@(title: String, description: Option[String], request: Request, response: Response)
## @title
@description

### Example

#### Request
```
@request.method @request.path @request.httpVersion@request.headers@request.body
```

#### Response
```
@response.status@response.headers@response.body
```