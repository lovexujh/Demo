> test见覅偶尔玩就玩


**好的**

``` dart

Dio dio = new Dio(); // with default Options

// Set default configs
dio.options.baseUrl = "https://www.xx.com/api";
dio.options.connectTimeout = 5000; //5s
dio.options.receiveTimeout = 3000;

// or new Dio with a BaseOptions instance.
BaseOptions options = new BaseOptions(
    baseUrl: "https://www.xx.com/api",
    connectTimeout: 5000,
    receiveTimeout: 3000,
);
Dio dio = new Dio(options);


```
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
