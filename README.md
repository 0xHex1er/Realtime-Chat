Realtime App Chat         
=================
<br>
<b>Ruby On Rails / Node.js / Redis Server/ SocketCluster / Loadbalancer.js
<br>
<br><br>

<h3>How to run project


1. Open Project Directory
```
$ cd Realtime-Chat
```
2. Start Rails Server
```
$ rails s -p 3000 -b 0.0.0.0
```
3. Start Redis Server (Open new terminal)
```
$ redis-server
```
4. Start SocketCluster and Create Socket (Open new terminal and open project directory)
```
$ node server.js
```
5. Start Loadbalancer (Open new terminal and open project directory)
```
$ loadbalancer start --config config.json
```

#### Open Browser ----> localhost:7999
##### port : 7999  < Default port of socketcluster  >
**** You can set default port of socketcluster in file ----> config.json ***** 