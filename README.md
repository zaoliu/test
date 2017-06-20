# 服务器：
    alias ssh_wesdk_api01='ssh -o ServerAliveInterval=60 -i '
    alias ssh_wesdk_lvs01='ssh -o ServerAliveInterval=60 -i '
    alias ssh_wesdk_lvs02='ssh -o ServerAliveInterval=60 -i '
    alias ssh_wesdk_lvs03='ssh -o ServerAliveInterval=60 -i '

# 定时任务：
### lvs01-lvs03:
    update_sclick_stat.py的定时任务
    sudo crontab -e //读log要root权限

### api01:
    update_hq_offer.py的定时任务
    crontab -e

# API
    lvs03
    sudo supervisorctl restart wall
