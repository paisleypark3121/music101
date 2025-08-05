## MUSIC101

### replit
In order to have it run on replit, use the import from git up and put the following code on .replit file:

```
run = "python3 -m http.server 3000"

[nix]
channel = "stable-25_05"
packages = ["python3"]

[deployment]
run = ["python3", "-m", "http.server", "3000"]

[[ports]]
localPort = 3000
externalPort = 80
```
