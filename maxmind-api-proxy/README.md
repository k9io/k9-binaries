Usage
-----

This depends on the config.json file which can be found at: https://raw.githubusercontent.com/k9io/maxmind-api-proxy/refs/heads/main/etc/config.json

<pre>
$ sudo wget https://raw.githubusercontent.com/k9io/maxmind-api-proxy/refs/heads/main/etc/config.json
$ sudo nano config.json  # <- Modify to meet your needs!
$ sudo wget https://github.com/k9io/k9-binaries/raw/refs/heads/main/maxmind-api-proxy/linux/maxmind-api-proxy.amd64.gz  # Match your arch/OS! 
$ sudo gzip -d maxmind-api-proxy.amd64.gz 
$ sudo maxmind-api-proxy.amd64 maxmind-api-proxy
$ ./maxmind-api-proxy ./config.json
</pre>

See https://github.com/k9io/maxmind-api-proxy for more information! 

