# How to install a ssl-certificate on Linux

1. Download .pem certificate from youer web browser.
2. Place .pem file into /usr/share/ca-certificates
3. Rename the extension .pem to .crt.
4. Run ``sudo update-ca-certificates``.
