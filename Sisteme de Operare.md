
#subdomeniu 
## Activități Principale (Grila Denning)

- **Teorie**: Modele matematice pentru concurență (semafoare, mutex-uri), teoria așteptării (queuing theory) pentru planificarea proceselor (CPU scheduling), modele de prevenire a blocajelor (Deadlock).
    
- **Experiment**: Măsurarea performanței (throughput, latență) sub sarcini grele de lucru (stress testing), analiza eficienței algoritmilor de caching și a memoriei virtuale (page faults).
    
- **Design**: Proiectarea arhitecturii nucleului (Monolithic Kernel vs. Microkernel), dezvoltarea sistemelor de fișiere (ex: ext4, NTFS), scrierea de drivere pentru componente hardware, implementarea mașinilor virtuale.
    

## 2. Relații cu alte subdomenii

- **Depinde de**: [[Arhitectura Calculatoarelor]] (OS-ul trebuie să înțeleagă la nivel fizic procesorul și memoria) și [[Algoritmi si Structuri de Date]] (kernel-ul folosește arbori și liste pentru a gestiona fișierele și procesele).
    
- **Influențează**: [[Rețele de Calculatoare]] (OS-ul expune stiva TCP/IP), [[Limbaje de Programare]] și [[Cybersecurity]] (prin gestionarea permisiunilor de acces și izolarea proceselor).
    

## 3. Probleme Importante și Deschise

- **Probleme Importante**: Gestionarea eficientă a sistemelor multi-core masive, echilibrul între securitate strictă și performanță rapidă.
    
- **Probleme Deschise**:
    
    - **Izolarea Perfectă (Sandboxing)**: Cum rulăm cod potențial periculos fără să riscăm coruperea întregului sistem (o problemă uriașă în Cloud Computing).
        
    - **OS pentru IoT (Internet of Things)**: Proiectarea unor sisteme de operare extrem de sigure, dar care să ruleze pe dispozitive cu memorie și baterie microscopică (ex: senzori medicali).
        

## 4. Dimensiunea Globală

- **Persoane importante**:
    
    - **Linus Torvalds** (creatorul Linux).
        
    - **Ken Thompson** & **Dennis Ritchie** (creatorii UNIX).
        
    - **Andrew Tanenbaum** (creatorul MINIX și autorul „bibliei” de Sisteme de Operare).
        
- **Foruri/Conferințe**:
    
    - **SOSP** (Symposium on Operating Systems Principles).
        
    - **OSDI** (Operating Systems Design and Implementation).
        

## 5. Dimensiunea Locală (FMI UVT)

- **Profesori/Cercetători**:
    
    - [[Conf. Dr. Florin Fortiș]] (titular clasic pentru cursul de Sisteme de Operare).
        
    - [[Conf. Dr. Marian Neagul]] (specializat în Cloud Computing și Sisteme Distribuite).
        
- **Materii relevante la UVT**:
    
    - Sisteme de Operare (Anul 1/2).
        
    - Programare Concurentă.
        
    - Cloud Computing / Sisteme Distribuite.
        
- **Foruri locale**: Institute e-Austria Timișoara (implicat în proiecte de grid computing și sisteme distribuite).