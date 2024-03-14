# Dito-e-Feito_nc
katas for the celebred connection linux tool

last practice: 14/03/24 14:00


Dito 1) Open the 1111 port in listening mode

Dito 2) Open the 1111 port in listening mode, with verbose

Dito 3) 

a) In the server: Open the 1111 port in listening mode, with verbose;

b) In a "client" machine, connect to the "server";

c) Say "hello" from client and answer "world" from server.


===== ======= =============== ============ ========= ========


Feito 1) nc -lp 1111

Feito 2) nc -lvp 1111

Feito 3) 

a) nc -lvp 1111

b) nc 192.168.zzz.yyy 1111 (from here a terminal to chat is avaiable)


===== ======= =============== ============ ========= ========


Forms of connections:

browser (ip + port)

scan apps (like wifiMan)

nmap comands (like nmap -sV -p [port] [host])


