Usage
-----

This depends on the k9-client-logging-proxy.yaml file which can be found at: curl https://raw.githubusercontent.com/k9io/k9-client-logging-proxy/refs/heads/main/etc/k9-client-logging-proxy.yaml

<pre>
$ sudo mkdir -p /opt/k9/etc /opt/k9/bin
$ cd /opt/k9/etc
$ sudo wget https://raw.githubusercontent.com/k9io/k9-client-logging-proxy/refs/heads/main/etc/k9-client-logging-proxy.yaml
$ sudo nano /opt/k9/etc/k9-client-logging-proxy.yaml  # <- Modify to your Key9 configurations
$ cd /opt/k9/bin
$ sudo wget https://github.com/k9io/k9-binaries/raw/refs/heads/main/k9-client-logging-proxy/linux/k9-client-logging-proxy.amd64.gz  # Match your arch/OS! 
$ sudo gzip -d k9-client-logging-proxy.amd64.gz 
$ sudo k9-client-logging-proxy.amd64 k9-client-logging-proxy
</pre>

See https://github.com/k9io/k9-client-logging-proxy for more information! 

