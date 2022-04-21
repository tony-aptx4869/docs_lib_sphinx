  447  20/12/21 12:52:56 wget -N https://blueforcer.de/awtrix/awtrix.sh
  448  20/12/21 12:57:37 chmod +x awtrix.sh 
  457  20/12/21 13:11:37 mkdir -p /usr/local/s_awtrix
  458  20/12/21 12:57:42 ./awtrix.sh 
  459  20/12/21 13:14:57 cd /usr/local/awtrix/
  461  20/12/21 13:15:18 systemctl stop awtrix
  462  20/12/21 13:16:01 mv awtrix.jar ../
  466  20/12/21 13:16:12 rm -rf awtrix/
  470  20/12/21 13:18:19 systemctl disable awtrix
  472  20/12/21 13:19:24 systemctl start awtrix
  475  20/12/21 13:20:09 systemctl status awtrix
  476  20/12/21 13:20:29 systemctl stop awtrix
  477  20/12/21 13:20:55 unzip -l awtrix2.zip 
  479  20/12/21 13:21:43 unzip -c awtrix2.zip 
  484  20/12/21 13:23:02 unzip awtrix2.zip 
  486  20/12/21 13:23:13 mv awtrix2 awtrix
  488  20/12/21 13:23:17 cd awtrix/
  493  20/12/21 13:23:49 mv awtrix temp
  495  20/12/21 13:23:58 mv temp/data awtrix
  497  20/12/21 13:24:02 cd awtrix/
  502  20/12/21 13:24:30 systemctl start awtrix
  503  20/12/21 13:24:36 systemctl status awtrix
  504  20/12/21 13:25:44 cd /usr/local/awtrix
  514  20/12/21 13:30:11 mv awtrix.jar /root
  517  20/12/21 13:28:11 ./awtrix.sh 
  518  20/12/21 13:32:04 ./awtrix.sh 
  519  20/12/21 13:37:47 cd /usr/local/awtrix/
  522  20/12/21 15:27:06 cd /usr/local/awtrix/
  528  20/12/21 15:32:57 md5 /usr/local/awtrix/awtrix.jar
  532  20/12/21 15:33:36 shasum -a 256 /usr/local/awtrix/awtrix.jar
  533  20/12/21 15:34:03 cd /usr/local/awtrix
  535  20/12/21 15:34:21 mv awtrix.jar.bak awtrix.jar.sta
  537  20/12/21 15:35:00 systemctl stop awtrix.service
  538  20/12/21 15:35:07 rm awtrix.jar
  544  20/12/21 15:36:29 cp awtrix.jar.bet awtrix.jar
  546  20/12/21 15:36:46 systemctl start awtrix.service
  547  20/12/21 16:21:57 systemctl stop awtrix.service 
  548  20/12/21 16:22:03 cd /usr/local/awtrix/
  550  20/12/21 16:22:15 cp awtrix.jar.nit awtrix.jar
  552  20/12/21 16:22:26 systemctl start awtrix.service 
  553  20/12/21 16:30:46 systemctl stop awtrix.service 
  554  20/12/21 16:30:56 cp awtrix.jar.bet awtrix.jar
  556  20/12/21 16:31:05 systemctl start awtrix.service 
  557  20/12/21 16:31:08 systemctl start awtrix.service 
  560  20/12/21 16:40:11 systemctl status awtrix.service 
  561  20/12/21 16:40:30 systemctl restart awtrix.service 
  562  20/12/21 16:42:32 systemctl status awtrix.service 
  563  20/12/21 16:42:59 cat /usr/local/awtrix/logs/1639989631295.log
  564  20/12/21 16:43:11 tail -f /usr/local/awtrix/logs/1639989631295.log
  565  20/12/21 16:48:53 systemctl restart awtrix.service 
  566  20/12/21 16:48:58 systemctl status awtrix.service 
  567  20/12/21 16:49:11 tail -f /usr/local/awtrix/logs/1639990134307.log
  568  20/12/21 16:53:31 systemctl restart awtrix.service 
  569  20/12/21 16:53:37 systemctl status awtrix.service 
  570  20/12/21 16:53:54 tail -f /usr/local/awtrix/logs/1639990411686.log
  571  20/12/21 16:57:13 systemctl restart awtrix.service 
  572  20/12/21 16:57:45 systemctl status awtrix.service 
  573  20/12/21 16:57:56 tail -f /usr/local/awtrix/logs/1639990634212.log
  576  20/12/21 18:06:58 systemctl status awtrix.service 
  577  20/12/21 18:07:11 tail -f /usr/local/awtrix/logs/1639990634212.log
  578  20/12/21 18:09:34 systemctl restart awtrix.service 
  579  20/12/21 18:10:58 systemctl stop awtrix.service 
  580  20/12/21 18:11:12 cd /usr/local/awtrix/
  582  20/12/21 18:11:20 cp awtrix.jar.sta awtrix.jar
  584  20/12/21 18:11:26 systemctl restart awtrix.service 
  585  20/12/21 18:11:32 systemctl status awtrix.service 
  586  20/12/21 18:11:56 tail -f /usr/local/awtrix/logs/12-20-181127.txt
  590  20/12/21 18:15:49 rm -rf s_awtrix/
  591  20/12/21 18:16:04 systemctl stop awtrix.service 
  592  20/12/21 18:16:17 cd awtrix/
  599  20/12/21 18:17:07 rm -rf awtrix
  601  20/12/21 18:17:13 unzip awtrix2.zip 
  603  20/12/21 18:17:32 mv awtrix2/data awtrix
  605  20/12/21 18:17:35 cd awtrix
  607  20/12/21 18:17:43 rm awtrix.jar.bak 
  612  20/12/21 18:18:18 systemctl start awtrix.service 
  613  20/12/21 18:18:27 systemctl status awtrix.service 
  614  20/12/21 18:18:47 tail -f /usr/local/awtrix/logs/12-20-181818.txt 
  615  20/12/21 18:47:54 cd /usr/local/awtrix
  620  20/12/21 19:19:23 tail -f /usr/local/awtrix/logs/12-20-181818.txt 
  621  21/12/21 09:22:13 tail -f /usr/local/awtrix/logs/12-20-181818.txt 
  625  22/12/21 01:24:52 cd /usr/local/awtrix
  629  22/12/21 01:25:01 cd awtrix2
  637  22/12/21 10:39:00 cd /usr/local/awtrix
  639  22/12/21 10:39:15 cd /usr/local/awtrix/logs/
  648  22/12/21 13:53:14 systemctl status awtrix
  649  22/12/21 13:53:40 tail -f /usr/local/awtrix/logs/12-20-181818.txt
  650  22/12/21 15:35:44 journalctl -f -u awtrix.service
  651  22/12/21 17:05:56 tail -f /usr/local/awtrix/logs/12-20-181818.txt
  656  03/01/22 11:32:08 systemctl status awtrix.service 
  657  03/01/22 11:33:06 systemctl restart awtrix.service 
  665  04/01/22 09:50:51 systemctl status awtrix.service 
  667  14/01/22 19:28:52 systemctl restart awtrix
  668  14/01/22 19:29:09 systemctl status awtrix
  669  14/01/22 19:29:59 cd /usr/local/awtrix/logs/
  672  18/01/22 17:13:03 systemctl status awtrix
  673  31/01/22 18:19:44 systemctl restart awtrix.service 
  674  31/01/22 18:19:53 systemctl status awtrix.service 
  677  09/02/22 10:32:16 systemctl status awtrix.service 
  678  09/02/22 10:32:51 cd /usr/local/awtrix
  686  22/02/22 21:12:20 systemctl restart awtrix.service
  692  28/02/22 16:55:43 systemctl status awtrix.service
  703  28/02/22 17:09:20 systemctl status awtrix.service
  713  04/03/22 14:46:39 systemctl status awtrix.service
  714  04/03/22 14:47:06 systemctl status awtrix.service
  734  24/03/22 17:46:58 systemctl restart awtrix.service 
  739  07/04/22 17:50:25 service awtrix status
  746  07/04/22 17:53:57 service awtrix status
  747  07/04/22 17:54:18 history | grep awtrix