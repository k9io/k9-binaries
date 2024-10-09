Usage
-----

This depends on the k9.yaml file which can be found at: curl https://raw.githubusercontent.com/k9io/k9-ssh/refs/heads/main/etc/k9.yaml

<pre>
$ sudo mkdir -p /opt/k9/etc /opt/k9/bin
$ cd /opt/k9/etc
$ sudo wget https://raw.githubusercontent.com/k9io/k9-ssh/refs/heads/main/etc/k9.yaml
$ sudo nano /opt/k9/etc/k9.yaml  # <- Modify to your Key9 configurations
$ cd /opt/k9/bin
$ sudo wget https://github.com/k9io/k9-binaries/raw/refs/heads/main/k9-ssh/linux/k9-ssh.amd64.gz  # Match your arch/OS! 
$ sudo gzip -d k9-ssh.amd64.gz 
$ sudo k9-ssh.amd64 k9-ssh
</pre>

See https://github.com/k9io/k9-ssh for more information! 

