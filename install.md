$adlist= Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/Brandonbr1/ad-list-hosts/main/host' <br>
$adfile = "$env:windir\System32\drivers\etc\hosts" <br>
$adlist | Add-Content -PassThru $adfile <br>
