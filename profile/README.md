## hyport

K8s-native Hosting-Plattform für Gameserver. Ein Server, der startet, erreichbar ist und
bei Node-Ausfall in unter einer Minute mit gleicher IP und gleichem Port wieder läuft –
bei höchstens Sekunden Datenverlust.

Nachfolger im Geist von Pterodactyl, aber kein Fork und keine Kopie: eigener Code,
eigenes Modell.

### Was es ausmacht

- **Failover über Nodes hinweg** – die Allocation (IP:Port) bleibt, der Spieler verbindet sich zur selben Adresse.
- **Kontinuierliche, verschlüsselte ZFS-Replikation** auf eine kalte Peer-Kopie auf einer anderen Node.
- **Self-Healing als Pflicht** – jeder mehrstufige Ablauf bekommt Deadline, Stuck-Erkennung und sichere Auto-Reparatur, oder meldet klar.
- **Technische Steuerebene** – kein Billing, kein Shop; Verkaufsportale sprechen die API an.

### Status

In aktiver Entwicklung, noch kein öffentliches Release.
