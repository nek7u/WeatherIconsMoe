Rainmeter  
WebParser Measure vs. RunCommand plugin + curl.exe[^1]

||WebParser Measure|RunCommand plugin + curl.exe|
|:----------:|:----------:|:----------:|
|HTTP/HTTPS|✔|✔|
|HTTP GET request|✔|✔|
|HTTP POST request||✔|
|HTTP HEAD request||✔|
|HTTP Request Headers|✔|✔|
|Accept-Encoding: gzip, deflate||[^2]|
|UserAgent|✔|✔|
|Cookie||✔|
|via Proxy server|✔|✔|
|UTF-8|✔|✔|

[WebParser Measure](https://docs.rainmeter.net/manual/measures/webparser/)  
[RunCommand plugin](https://docs.rainmeter.net/manual/plugins/runcommand/)  
[curl.exe for windows](https://curl.haxx.se/windows/)  

[^1]: curl.exe need to be allowed to access network by Windows Defender Firewall.  
[^2]: curl.exe --compressed option  
gzip not avairable | Windows 10 1909 | curl 7.55.1 (Windows) libcurl/7.55.1  
gzip avairable | curl 7.70.0 (x86_64-pc-win32) libcurl/7.70.0  

2020-05-28 Windows 10 1909

