# 彩虹云外链网盘 加密备份
恢复: cat *.enc.* > f.enc && openssl enc -d -aes-256-cbc -pbkdf2 -in f.enc -out f.tar.gz && tar -xzf f.tar.gz
密码: 见 auto_backup.sh 的 ENCRYPT_PASS
