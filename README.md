# ad-list-hosts

This provides a Host file that will block almost all ads whitout going overkill like some host file are like 1mb in file raw size
this one it tries to keep it simple with it tries to block  Ads, Error Trackers, Analytics and Social Trackers

## to install

`$adlist= Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/Brandonbr1/ad-list-hosts/main/host' 
$adfile = "$env:windir\System32\drivers\etc\hosts"
$adlist | Add-Content -PassThru $adfile`

## LICENSE
[Creative Commons Zero v1.0 Universal](https://github.com/Brandonbr1/ad-list-hosts/blob/main/LICENSE)
