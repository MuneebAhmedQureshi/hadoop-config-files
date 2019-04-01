# hadoop-config-files <br>
Hadoop Config Files <br>
# on master: <br>
allow users hduser from command line<br>
passwordauthentication yes bashrc<br>
ssh and copy <br>
added and configured java and hadoop <br>
add hostnames to hosts file in /etc folder in root
slave file usr/local/hadoop/etc: hostname usman-probook <br>
worker file usr/local/hadoop/etc: master and slave hostnames <br>
fotmat name node : delete current file from usr/local/tmp/dfs/name and usr/local/tmp/dfs/data <br>
start-dfs.sh <br>
# on slave: <br>
added and configured java and hadoop <br>
added config files from master <br>
add hostnames to /etc/hosts file
added usr/local/tmp/dfs/name and usr/local/tmp/dfs/data files and sudo chmod 777 them all including folders <br>
changed path of tmp/dfs/name and tmp/dfs/data for slave in hdfs-site.xml <br>
format datanode : delete current file from tmp/dfs/data and tmp/dfs/name <br>
