��#   Z D Y S 
 
1. Run Kali linux 
2. Be sure all the scanning tools are in Kali (Nmap - Nikto and WPScan tools already exist in Kali) you only have to install Owasp-zap
3. run this command after installing zap for scans that selected zap, command => zaproxy -daemon -port 8090 -host 127.0.0.1 -config api.disablekey=true
4. run this command after creating kali_api_server.py file, command => python3 kali_api_server.py
5. run app.py file in windows and start scanning 
