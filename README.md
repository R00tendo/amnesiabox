# AmnesiaBox
**Ram only secure static content hosting server written in Go**
<img width=900 src="https://github.com/user-attachments/assets/b9de2850-f8e1-4dc7-890a-6a62d6e111f2">


# Installation & usage
```
git clone https://github.com/R00tendo/amnesiabox
cd amnesiabox
go run ./cmd/server/server.go
```

# Configuration 
**Method 1 (command line parameters):**
```
 -cert string
        ssl public certificate path
  -disable-captcha
        disables login and upload captcha
  -hidehosted
        enable or disable showing sites hosted
  -key string
        ssl private key path
  -l string
        listener (127.0.0.1:8080)
  -open
        make anyone be able to run a site without password
  -password string
        global password that you need to upload a site
  -sizelimit int
        size limit for the file uploads (default 10485760)
```

**Method 2 (configuration file):**
```
listener=127.0.0.1:8080
open=true
sizelimit=1024
```
