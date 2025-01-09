# Cisco-Switch-Config  

`?` : Liste les commandes dans le mode actuel.  
`show` :  Liste les consultations possibles du mode actuel.  
`enable` : Monter en privilege. Petites commandes accessibles.  
`(#) configure` : Niveau de privilège > "enable".   
=> `configure terminal` : Mode configuration du terminal.  
`exit` : redescendre d'un niveau en privilèges.  
`end` : sort complètement des niveaux de privilèges.  
`(#) show running-config` : Montre la Config en cours (ne marche pas en mode configuration).  
`(#) show interfaces` : Peu pratique comme affichage.  
`(#) show interfaces | include Fas` : affiche les interfaces commençant par "Fas".  
`(#) show ip interfaces brief` : toutes les interfaces physiques de la machine.  

vlan1 configuré par défaut et contient tous les ports dessus.  

`(config #) hostname saiph` : renomme le switch en "saiph".  
`copy running-config startup-config` : Enregistre la config actuelle sur la config startup.  
`(config)# ip domain-name stars.local` : crée un nom de domaine.  
`(config)# interface fastethernet 0/1` : Paramètre l'interface fastethernet 0/1.  
`(config)# interface range fastethernet 0/1-24` : Paramètre les interfaces de fastethernet 0/1 à 0/24.  
`(config-if-range)# switchport mode access` : Envoi les ports en switchport mode access. Permet de ne pas être accessible de l'extérieur.  
`(#) vlan 399` : crée le vlan 399.  
`(config-if-range)#switchport access vlan 399`: 

