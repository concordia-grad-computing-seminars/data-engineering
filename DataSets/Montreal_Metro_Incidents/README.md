# Montreal metro incidents

## Source
[https://www.donneesquebec.ca/recherche/dataset/vmtl-incidents-du-reseau-du-metro](https://www.donneesquebec.ca/recherche/dataset/vmtl-incidents-du-reseau-du-metro)

# Dictionnaire de données
```
    Numero d'incident (Numérique) : Numéro unique qui identifie chaque incident

    Type d'incident (Liste de valeur) : Identification du type d'incident
        T:Train
        S:Station

    Cause primaire (Liste de valeur) : Cause primaire déterminée suite à l'analyse de l'incident
        Clientèle
        Matériel roulant
        Équipements fixes
        Exploitation trains
        Autres

    Cause secondaire (Liste de valeur) : Cause secondaire déterminée suite à l'analyse de l'incident
        Blessée ou malade
        Méfait volontaire
        Nuisance volontaire
        Clientèle
        MPM-10
        MR-73
        Véhicule de travaux
        Service de la voie
        Service aux trains
        Service aux stations
        Service TCPE
        Équipements fixes
        Ligne 1,2,4,5
        Centre de contrôle
        Exploitation trains
        Causes externes
        Contrats Réno-Stations
        Contrats Réno-Système
        Contrats MPM10
        Pers. / Équipement STM
        Pers. / Équipement Externe
        Autres

    Symptome (Liste de valeur) : Cause initiale attribuée au moment de l'incident
        Clientèle
        Matériel roulant
        Équipements fixes
        Exploitation trains
        Feu, fumée, odeur, produit, etc…

    Ligne (Liste de valeur) : Nom de la ligne sur laquelle a eu lieu l'incident
        1:Ligne verte
        2:Ligne orange
        4:Ligne jaune
        5:Ligne bleue

    Numéro de tournée (Numérique) : Numéro de tournée du train associé à l'incident, # indique qu'il n'y a pas de tournée associée
    Date du jour (Alpha) (Date et/ou heure) : Jour civil de l'incident

    Heure de l'incident (Date et/ou heure) :

        Pour les incidents trains: Heure de début du délai (service clientèle) pour l'incident (et non l'heure de début de l'incident).

        Pour les incidents station: Heure de début de l'incident.

    Heure de reprise (Date et/ou heure) :

        Pour les incidents trains: Heure de fin du délai (service clientèle) pour l'incident (et non l'heure de fin de l'incident).

        Pour les incidents station: Heure de fin de l'incident.

    Jour du mois (Date et/ou heure) : Jour du mois de l'incident
    Véhicule (Numérique) : Numéro de la voiture du train impliqué dans l'incident ou # advenant qu'il n'y a pas de voiture impliquée.
    Porte de voiture (numéro) (Texte variable) : Numéro de la ou des portes impliquées dans l'incident (1 à 8 et toutes) ou # advenant qu'il n'y a pas de porte en cause
    Type de Matériel (Liste de valeur:73;10) : Type de matériel roulant (MR-73 ou MPM-10)
    CAT (Booléen) : Indicateur de coupure d'alimentation de traction (1:oui/0:non)
    Dommage matériel (Booléen) : Indicateur de possibilité de dommage au train (1:oui/0:non)
    KFS (Booléen) : Indicateur de l'utilisation du frein d'urgence par la clientèle (1:oui/0:non)
    Porte (Booléen) : Indicateur de l'implication d'une porte dans l'incident (1:oui/0:non)
    Urgence métro (Booléen) : Indicateur de l'implication de l'équipe urgence métro à la demande de la salle de contrôle (1:oui/0:non)
    Code de lieu (Texte variable) : Lieu de l'incident
    Évacuation (Texte variable) : Indicateur de l'évacuation d'une voiture, d'un train, d'une station ou d'une station et d'un train, # indique qu'il n'y a pas d'évacuation pour cet incident.
    Année civile (Date et/ou heure) : Année de l'incident
    Année civile/mois (Date et/ou heure) : Année/mois de l'incident
    Jour calendaire (Date et/ou heure) : Jour calendaire de l'incident
    Jour de la semaine (Date et/ou heure) : Jour de la semaine de l'incident
    Mois calendrier (Date et/ou heure) : Mois calendrier de l'incident
```