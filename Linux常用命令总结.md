1. cat /etc/ssh/sshd_config | grep MaxAuthTries     // 查询MaxAuthTries在文件sshd_config中是否配置

2. find / -name xxx    // 查找xxx文件

3. ps -ef | grep java    // 查看java进程

4. vi xxx    // 修改xxx文件内容

5. ls   // 查看当前目录下所有文件

6. ls -l  或者  ll    // 查看文件详情

7. cd   // 切换目录

8. cd ..   // 切换到上层目录

9. rm  // 删除文件

10. pwd  // 显示当前目录

11. uname -r  //查看系统类型

12. chown clouddragon agent -R
    chgrp devdeploy agent -R 

13. netstat -tlunp   // 查看ip端口号等

14. 查看context-path: cd /opt/服务 然后cat application.yml 找里面的server下的servlet下的context-path

15. cat /etc/ssh/sshd_config |grep MaxAuthTries     //查询MaxAuthTries在文件sshd_config中是否配置

16. 复制文件到其他目录： cp -i 3348_iast_task.db /home/opsadmin

17. 进入容器：首先 docker ps 查看容器列表，然后 'docker exec -it 容器id /bin/bash' 进入容器

18. 容器文件拷贝到宿主机：docker cp 容器id:需要拷贝文件在容器中的路径 需要拷贝文件到宿主机的路径

19. root远程登录查询命令  sshd -T |egrep 'protocol|permitrootlogin|permitemptypasswords|ciphers'
