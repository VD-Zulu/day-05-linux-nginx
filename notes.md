# Day 05 - Linux + Nginx Lab

## Environment
Operating System: Ubuntu 22.04 LTS  
Hostname: (output of `hostname`)  
IP Address: (output of `ip addr`)

## Nginx
Installation: sudo apt install nginx -y  
Service Status: (output of `systemctl status nginx`)  
Web Root: /var/www/html

## Networking
SSH Port: 22  
HTTP Port: 80

## Firewall
Rules configured: Allow SSH and HTTP (sudo ufw status)

## Testing
Tests performed: curl localhost, curl http://SERVER-IP

## Troubleshooting
Failure: Stopped Nginx service  
Evidence: curl failed, status inactive  
Root Cause: Service stopped  
Resolution: Restarted Nginx  
Verification: Webpage loaded successfully

## Lessons Learned
1. Always check service status before restarting.  
2. Logs provide root cause evidence.  
3. Firewall rules must allow HTTP traffic.
