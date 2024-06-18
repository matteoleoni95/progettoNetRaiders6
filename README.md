La nostra macchina Metasploitable presenta un servizio vulnerabile sulla porta 1099 – Java RMI.
 Si richiede allo studente di sfruttare la vulnerabilità con Metasploit al fine di ottenere una sessione di Meterpreter sulla macchina remota. 
I requisiti dell’esercizio sono: 
- La macchina attaccante (KALI) deve avere il seguente indirizzo IP: 192.168.11.111ù
- La macchina vittima (Metasploitable) deve avere il seguente indirizzo IP: 192.168.11.112
- Una volta ottenuta una sessione remota Meterpreter, lo studente deve raccogliere le seguenti evidenze sulla macchina remota: 
1) configurazione di rete. 
2) informazioni sulla tabella di routing della macchina vittima.

Extra facoltativo: 
Esercizio Extra Usa il modulo exploit/linux/postgres/postgres_payload per sfruttare una vulnerabilità nel servizio PostgreSQL di Metasploitable 2.
Esegui l'exploit per ottenere una sessione Meterpreter sul sistema target. Escalation di privilegi e backdoor:-
- Una volta ottenuta la sessione Meterpreter, il tuo compito è eseguire un'escalation di privilegi per passare da un utente limitato a root utilizzando solo i mezzi forniti da msfconsole.
- Esegui il comando getuid per verificare l'identità dell'utente corrente. Usa il modulo post di msfconsole per identificare potenziali vulnerabilità locali che possono essere sfruttate per l'escalation di privilegi.
- Esegui l’exploit proposti e verifica ogni vulnerabilità trovata dal modulo sopracitato.
- Per ogni vulnerabilità test l'escalation di privilegi eseguendo nuovamente getuid o tentando di eseguire un comando che richiede privilegi di root.
- sempre usando msfconsole installa una backdoor e dimostra che puoi accedere ad essa in un momento successivo.

 Suggerimento criptico: ricorda che sei nella sessione del procione e quindi fai attenzione agli architetti.


 Gli screenshot dell'esercizio sono numerati, in ordine di esecuzione. Buona visione.
