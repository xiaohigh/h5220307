
## 请求报文
```
GET https://www.baidu.com/ HTTP/1.1
Host: www.baidu.com
Connection: keep-alive
Cache-Control: max-age=0
sec-ch-ua: " Not A;Brand";v="99", "Chromium";v="101", "Google Chrome";v="101"
sec-ch-ua-mobile: ?0
sec-ch-ua-platform: "Windows"
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/101.0.4951.67 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9
Sec-Fetch-Site: none
Sec-Fetch-Mode: navigate
Sec-Fetch-User: ?1
Sec-Fetch-Dest: document
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8,la;q=0.7
Cookie: BIDUPSID=8977326ACBEB70D8618665882E66AE49;


```

## 响应报文
```
HTTP/1.1 200 OK
Bdpagetype: 2
Bdqid: 0x8af6ea280001d9cd
Cache-Control: private
Connection: keep-alive
Content-Type: text/html;charset=utf-8
Date: Wed, 18 May 2022 08:37:32 GMT
Expires: Wed, 18 May 2022 08:37:32 GMT
Server: BWS/1.1
Set-Cookie: BDSVRTM=376; path=/
Set-Cookie: BD_HOME=1; path=/
Set-Cookie: H_PS_PSSID=36427_36367_34813_36420_36165_34584_35978_36055_35802_36337_26350; path=/; domain=.baidu.com
Strict-Transport-Security: max-age=172800
Traceid: 1652863052278789402610013448279024589261
X-Frame-Options: sameorigin
X-Ua-Compatible: IE=Edge,chrome=1
Content-Length: 449738

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{margin:0}
        body{background-color: #aef;}
    </style>
</head>
<body>
    <h1>百度一下 你就知道</h1>    

    <script>
        console.log('欢迎加入百度');
    </script>
</body>
</html>
```