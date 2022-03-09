# HTTP Parse Code Kata
This is an exercise to parse a given raw HTTP Packet.

## Input Test Data
```
"HTTP/1.1 200 OK\nContent-Type: application/json\nContent-Length: 13\nConnection: close\n\n{\"foo\":\"bar\"}"
```

```
"HTTP/1.1 200 OK\nContent-Type: application/json\nContent-Length: 15\nConnection: close\n\n{\"fizz\":\"buzz\"}"
```

```
"HTTP/1.1 400 Bad Request\nContent-Type: application/json\nContent-Length: 23\nConnection: close\n\n{\"error\":\"bad request\"}"
```

## Assumptions
- Raw http response packet is a string

## Features - Parse Response Body
Extract the body of the raw http packet and convert to an object

## Feature - Parse Response Status
Take the raw HTTP packet and extract the response status as an integer value
