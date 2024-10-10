```mermaid
sequenceDiagram
    actor Attacker
    Attacker->>Botnet: Creates
    Note over Botnet: resides in  devices controlled by attacker
    Botnet->>Web Server: Connects to server
    Firewall->>Web Server: stores connections
    Note over Firewall: can't protect against DDoS
    Note over Web Server: crashes
```
