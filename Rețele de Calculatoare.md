#subdomeniu 
## 1. Activități Principale (Grila Denning)

- **Teorie**: Modele formale de comunicare (Modelul de referință OSI și TCP/IP), teoria grafurilor aplicată în algoritmii de rutare (ex: Dijkstra pentru OSPF), teoria cozilor (queuing theory) pentru gestionarea congestiei și a traficului de pachete.
    
- **Experiment**: Simularea rețelelor la scară largă, măsurarea lățimii de bandă, a latenței și a ratei de pierdere a pachetelor sub stres, testarea noilor protocoale IoT în medii de comunicare wireless (ex: interferențe semnal).
    
- **Design**: Proiectarea topologiilor de rețea (stea, inel, mesh), dezvoltarea de protocoale de comunicare (HTTP/3, IPv6), implementarea conceptelor moderne precum Software-Defined Networking (SDN).
    

## 2. Relații cu alte subdomenii

- **Depinde de**: [[Sisteme de Operare]] (care implementează fizic stiva TCP/IP și gestionează placa de rețea) și [[Arhitectura Calculatoarelor]] (hardware-ul din spatele routerelor și switch-urilor).
    
- **Influențează puternic**: [[Cybersecurity]] (orice atac vine prin rețea; necesită firewall-uri și criptare VPN) și reprezintă fundația absolută pentru [[Sisteme Distribuite]] și Cloud Computing (unde o aplicație este spartă pe sute de servere care trebuie să comunice între ele).
    

## 3. Probleme Importante și Deschise

- **Probleme Importante**: Scalabilitatea adreselor de rețea (tranziția lentă la IPv6), asigurarea calității serviciului (QoS) pentru aplicații sensibile la timp (apeluri video, gaming).
    
- **Probleme Deschise**:
    
    - **Rețele 6G și Ultra-Low Latency**: Cum reducem latența la fracțiuni de milisecundă și menținem conexiunea stabilă pentru mașini autonome la viteze mari sau chirurgie robotică la distanță.
        
    - **Securitatea și Scalabilitatea IoT**: Cum gestionezi miliarde de dispozitive interconectate (Internet of Things) care au o putere de procesare prea mică pentru a rula protocoale complexe de criptare.
        

## 4. Dimensiunea Globală

- **Persoane importante**:
    
    - **Vint Cerf** și **Bob Kahn** (părinții Internetului, creatorii suitei de protocoale TCP/IP).
        
    - **Tim Berners-Lee** (inventatorul World Wide Web și a protocolului HTTP).
        
    - **Radia Perlman** (inventatoarea algoritmului Spanning Tree Protocol, fără de care rețelele locale ar colapsa din cauza buclelor de date).
        
- **Foruri/Conferințe**:
    
    - **ACM SIGCOMM** (cea mai prestigioasă conferință globală de networking).
        
    - **IEEE INFOCOM** (conferința internațională pentru comunicații între calculatoare).
        

## 5. Dimensiunea Locală (FMI UVT)

- **Profesori/Cercetători**:
    
    - [[Conf. Dr. Marian Neagul]] (expert în Cloud Computing, sisteme distribuite și rețele).
        
    - [[Conf. Dr. Florin Fortiș]] și [[Conf. Dr. Ciprian Pungilă]] (implicați în cursurile de infrastructură și masteratul de Securitate Cibernetică, care e strâns legat de rețele).
        
- **Materii relevante la UVT**:
    
    - Rețele de Calculatoare (Licență, Anul 2).
        
    - Cloud Computing și Sisteme Distribuite.
        
    - Infrastructură și servicii pentru rețele (Master).
        
- **Foruri locale**: Colaborările facultății cu giganți telecom din Timișoara (Nokia, Alcatel-Lucent) pentru laboratoare și practică pe echipamente de rețea reale