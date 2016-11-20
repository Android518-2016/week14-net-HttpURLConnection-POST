# week14-net-HttpURLConnectionExample-POST
Sample code that opens an HTTP connection (socket) to a 
an website api
It needs an api key, an api appid POST data is constructed
for the request

n.b. HTTP POST is more secure as you do not expose data in the URL
as you do with HTTP GET
The app retrieves the JSON response  which
is displayed as text in the UI, normally this would be
parsed and used otherwise in the UI.

Uses 
* ConnectivityManager and NetworkInfo
* AsyncTask 
* URLEncoder
* HttpURLConnection for POST
* BufferedInputStream
* ByteArrayOutputStream
* DataOutputStream

## app HttpUrlConnection
Note: input URL cannot be https:

Use of logcat to watch the logging
```
adb logcat -s HttpURLPOST
```
