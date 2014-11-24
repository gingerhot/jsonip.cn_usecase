### What does jsonip.cn do ?

jsonip.cn provides a simple api to return a JSON format ip data.

The data includes a http client's ip or more detail of Geo/Browser/OS etc.

### Two APIs

1. GET http://jsonip.cn

    ```
    { "ip": "123.45.67.89", "detail": "http://jsonip.cn/i" }
    ```

2. GET http://jsonip.cn/i

    ```
    {
       "ip": "123.45.67.89",
       "os":"Masintoshi",
       "browser": "Chrome",
       "contury": "中国",
       "city": "北京"
    }
    ```

### Usecases

The "index.html" give an example in a web page where an Ajax used to query the ip info.

___________________

By B1nj0y perlxruby@gmail.com

Blog: http://b1nj0y.com
