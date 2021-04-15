# POO---Basics-Part-3-Abstraction
💪 Challenge 🛣 On the road again
    Créer une classe abstraite HighWay possédant les propriétés suivantes :
        currentVehicles (array),
        nbLane (int) et
        maxSpeed (int),
    Créer les getters et setters correspondants au propriétés ci-dessus,
    Faire hériter les classes finales
        MotorWay (4 voies, 130km/h),
        PedestrianWay (1 voie, 10km/h)et
        ResidentialWay (2 voies, 50km/h).
    Ajouter à la classe HighWay une méthode abstraite addVehicle() prenant en paramètre un objet de type Vehicle.
    implémenter la méthode pour qu’elle ajoute le véhicule au tableau $currentVehicles, uniquement si ce dernier est autorisé sur ce type de voie. Ainsi, pour MotorWay, addVehicle($car) ajoutera bien une voiture au tableau, tandis que addVehicle($bike) ne le fera pas, car il n’est pas possible de rouler en vélo sur une autoroute. Les règles attendues sont les suivantes:
        motorway : tout type de voiture
        ResidentialWay : tout type de véhicule
        PedestrianWay : Bike et Skateboard uniquement
        
        ✔️ Critères de validation

    Les classes HighWay (abstraites) et MotorWay, PedestrianWay, ResidentialWay (finales) sont toutes les quatres créées, l’héritage et les propriétés/méthodes attendues sont présentes, ainsi que les valeurs par défaut.
    La classe HighWay possède une seule méthode abstraite, addVehicle(), implémentée de manière différente dans chacune de ses classes filles, en fonction des types de véhicules autorisés.

