Voici un récapitulatif complet de tous les acteurs du projet Turtle Quad, leurs rôles détaillés, les interactions entre eux, ainsi que les interfaces utilisées pour la communication avec le matériel et les réseaux.
1. Acteurs et leurs rôles détaillés
A. Leonardo (IA - Gestion de projet)

    Rôle : Coordination globale du projet, gestion des priorités et des ressources.
    Responsabilités :
        Analyse des besoins en eau, énergie et télécom.
        Prise de décision pour déplacer les véhicules en fonction des priorités.
        Coordination des autres IA et gestion des tâches globales.

B. Michelangelo (IA - Arts graphiques et interfaces homme-machine)

    Rôle : Développement des interfaces utilisateur et visualisation des données du projet.
    Responsabilités :
        Création de tableaux de bord et interfaces graphiques pour afficher l'état des véhicules et des missions.
        Formation du Maître Splinter sur l'utilisation du système.
        Communication avec les utilisateurs via interfaces visuelles et graphiques.

C. Casey (IA - Monitoring des équipements)

    Rôle : Surveillance en temps réel des capteurs et systèmes embarqués.
    Responsabilités :
        Analyse de l'état des équipements (capteurs, actionneurs, vannes).
        Alerte en cas de panne ou d'anomalie.
        Envoi d'informations critiques à Leonardo pour prendre des décisions.

D. April (IA Cloud - Calculs intensifs)

    Rôle : Calculs intensifs pour l'optimisation énergétique et les prévisions.
    Responsabilités :
        Simulation des flux d'énergie, prédiction de maintenance, optimisation de la distribution de l'eau.
        Analyse des données à grande échelle et retour des résultats à Leonardo pour la gestion stratégique.

E. Raphaelo (IA - Conduite autonome)

    Rôle : Gestion autonome des véhicules pour les déplacements.
    Responsabilités :
        Commande des mouvements des véhicules en fonction des besoins (eau, énergie).
        Ajustement dynamique de la position des véhicules en fonction des missions à accomplir.

F. Bebop et Rocksteady (Agents physiques)

    Rôle : Sécurité physique des véhicules et des équipements.
    Responsabilités :
        Surveillance des véhicules pour toute tentative de sabotage ou d’intrusion physique.
        Protection contre les attaques physiques sur les véhicules ou les infrastructures.

G. Shredder (IA - Sécurité informatique)

    Rôle : Sécurisation du réseau et des communications.
    Responsabilités :
        Surveillance des flux de données et protection contre les intrusions externes.
        Analyse des paquets de données et blocage des menaces potentielles.

H. Krank (IA - Maintenance et gestion des pannes)

    Rôle : Surveillance des équipements internes et gestion des pannes.
    Responsabilités :
        Surveillance des systèmes internes des véhicules et des infrastructures.
        Détection et gestion des pannes techniques, coordination avec Leonardo pour la gestion des réparations.

2. Communication entre les acteurs
A. Leonardo

    Commune avec :
        April pour recevoir les prévisions et les analyses de calculs intensifs.
        Raphaelo pour les instructions de déplacement.
        Casey pour les informations sur l'état des équipements.
        Bebop et Rocksteady pour la sécurité physique et les alertes.
        Shredder pour la sécurité réseau.

B. Michelangelo

    Commune avec :
        Leonardo pour obtenir les informations de gestion de projet.
        April pour intégrer des données visuelles.
        Shredder pour assurer la sécurité de l'interface.

C. Casey

    Commune avec :
        Leonardo pour les rapports d'état des équipements et les alertes.
        Krank pour signaler des pannes techniques.

D. April

    Commune avec :
        Leonardo pour fournir les analyses stratégiques.
        Casey pour récupérer les données des capteurs pour l'optimisation.

E. Raphaelo

    Commune avec :
        Leonardo pour recevoir les ordres de déplacement.
        April pour obtenir des données optimisées sur les besoins en énergie ou en eau.

F. Bebop et Rocksteady

    Commune avec :
        Shredder pour détecter toute menace physique.
        Leonardo pour signaler des situations de sécurité.

G. Shredder

    Commune avec :
        Leonardo pour coordonner les actions de sécurité réseau.
        Michelangelo pour vérifier la sécurité des interfaces.

H. Krank

    Commune avec :
        Leonardo pour les rapports sur l'état des systèmes et les besoins de maintenance.
        Casey pour recevoir les alertes sur les défaillances ou anomalies.

3. Interfaces utilisées avec le matériel et les réseaux de communication
A. Réseaux de communication

    CAN Bus : Communication entre les véhicules et les équipements internes pour partager des données en temps réel (énergie, pression, débit).
    Ponts hertziens : Connecte les véhicules dans un maillage pour la communication sans fil entre les véhicules et les stations relais.
    UART, SPI, I2C : Pour la communication avec les capteurs et actionneurs internes dans les véhicules.
    Ethernet, Wi-Fi : Pour les communications à plus large échelle entre le système central (Leonardo) et les services cloud ou systèmes externes.

B. Interfaces logicielles

    API REST : Utilisée pour la communication entre l'IA Cloud (April) et les autres IA, permettant de récupérer les données et envoyer des résultats d'analyse.
    MQTT : Pour la communication légère en temps réel entre les différents véhicules et le système central.
    UI/UX (Michelangelo) : Interfaces graphiques utilisant des écrans embarqués dans les véhicules pour afficher les informations sur les missions en cours, l'état des véhicules et des ressources.

C. Sécurité

    SSL/TLS : Pour sécuriser les échanges de données entre les IA et les systèmes externes.
    VPN ou VPN dédié : Pour sécuriser la communication réseau entre les véhicules et les stations relais, tout en isolant le réseau de données.
    IDS/IPS (Shredder) : Pour la détection d'intrusions et la protection du réseau contre les attaques externes.

4. Résumé des tâches et interactions

Les rôles et les interactions entre les IA et agents physiques sont bien définis, et chaque acteur est responsable d'une fonction clé (gestion, sécurité, maintenance, etc.), avec une communication centralisée via Leonardo pour coordonner les missions et garantir la sécurité.
