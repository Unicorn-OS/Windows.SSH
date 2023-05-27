https://chrisjhart.com/Windows-10-ssh-copy-id/

`type $env:USERPROFILE\.ssh\id_rsa.pub | ssh {IP-ADDRESS-OR-FQDN} "cat >> .ssh/authorized_keys"`
