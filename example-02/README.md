# example-02

- web page authentication
- single webpage
- file listing
- file download button
- file delete button
- file upload button with upload progress status
- reboot esp button
- all done on a single web page that uses javascript to call /listfiles and /file?name=something&action=delete or /file?name=something&action=download

## Configuration
Edit these variables at the beginning of example-02.ino

```
const String default_ssid = "somessid";
const String default_wifipassword = "mypassword";
const String default_httpuser = "admin";
const String default_httppassword = "admin";
const int default_webserverporthttp = 80;
```
