# hadoop-config-files
Hadoop Config Files
<b>on slave:</b>
added and configured java and hadoop
added config files from master
added tmp/dfs/name and tmp/dfs/data files and sudo chmod 777 them all including folders
changed path of tmp/dfs/name and tmp/dfs/data for slave in hdfs-site.xml
format datanode : delete current file from tmp/dfs/data and tmp/dfs/name
<b>on master: </b>
allow users hduser
passwordauthentication yes
ssh and copy
slave file : hostname usman-probook
worker file: master and slave hostnames
fotmat name node : delete current file from tmp/dfs/name and tmp/dfs/data
start-dfs.sh
