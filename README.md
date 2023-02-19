## Conseils de codage Java 8/11 | Spring Boot
Dans ce repo, nous allons voirs quelques conseils de codage Java pour écrire un meilleur code et des fonctionnalités Java que nous pouvons utiliser pour résoudre des problèmes courants.

*Notez que je suis toujours dans le processus d'apprentissage - probablement sans fin :)-*

- Utilisez la boucle `for-each` pour parcourir les collections et les tableaux. Il s'agit d'une fonctionnalité disponible depuis Java 5.
- Utilisez des `streams` pour traiter les données de manière fonctionnelle et efficace. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez la classe `Optional` pour éviter les exceptions de pointeur null. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez les `expressions lambda` pour définir des fonctions anonymes. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez les `method references` pour faire référence aux méthodes existantes. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez les `functional interfaces` pour définir le comportement fonctionnel. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez l' `API Date and Time` (ex: LocalDate, Instant) pour améliorer la gestion de la date et de l'heure. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez l' annotation `@FunctionalInterface` pour spécifier une interface fonctionnelle. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez la classe `Base64` pour encoder et décoder les données Base64. Cette fonctionnalité a été introduite dans Java 8.
- Utilisez le mot clé `var` pour déclarer des variables avec des types inférés. Cette fonctionnalité a été introduite dans Java 11. Pas encore largement utilisée par tout le monde !
- Utilisez l'instruction `switch` avec des objets String. Cette fonctionnalité a été introduite dans Java 7 et améliorée dans Java 14. Utilisez Switch pour moins de cas uniquement.
- Utilisez la méthode factory `List.of()` pour créer une liste immuable (non modifiable). Cette fonctionnalité a été introduite dans Java 9.
- Utilisez les méthodes factory `Map.of()` et `Map.ofEntries()` pour créer des cartes immuables. Cette fonctionnalité a été introduite dans Java 9.
- Utilisez les `Parallel Streams` pour effectuer des opérations en parallèle. Cette fonctionnalité vous permet de diviser une grande collection de données en plus petits morceaux et de les traiter simultanément, ce qui peut améliorer considérablement les performances de votre code.
- Utilisez l'interface fonctionnelle `Predicate` pour créer une fonction réutilisable qui teste si une entrée donnée satisfait ou non à une certaine condition.
- Utilisez l'interface fonctionnelle `Consumer` pour créer une fonction réutilisable qui exécute une action sur une entrée donnée.
- Utilisez l'interface fonctionnelle `Supplier` pour créer une fonction réutilisable qui renvoie une valeur sans prendre aucune entrée.
- Utilisez la classe `StringBuilder` au lieu de concaténer des chaînes à l'aide de l'opérateur `+`. La concaténation de chaînes à l'aide de l'opérateur `+` crée un nouvel objet chaîne à chaque fois, ce qui peut être inefficace lorsqu'il est effectué fréquemment ou avec de grandes quantités de données. La classe `StringBuilder` vous permet de créer efficacement des chaînes en réutilisant un seul objet et en lui ajoutant de nouveaux caractères.
- Utiliser des **interfaces** pour découpler des objets : les interfaces permettent aux objets de communiquer entre eux sans avoir une connaissance directe du fonctionnement interne de l'autre. Cela peut aider à réduire les dépendances entre les objets et rendre le système plus flexible.
- Utiliser l'**injection de dépendances** pour gérer les relations entre objets : l'injection de dépendances est une technique qui permet aux objets de recevoir leurs dépendances de l'extérieur, plutôt que de les créer en interne. Cela peut aider à découpler les objets et à rendre le système plus modulaire et testable.
- Utilisez les **design patterns** pour gérer les dépendances : les Design patterns tels que le decorator pattern et le adapter pattern peuvent aider à dissocier les objets et à réduire le nombre de dépendances entre eux.
- **Évitez de créer des relations inutiles entre les objets** : déterminez si une relation entre deux objets est réellement nécessaire et évitez de créer des relations qui ne sont pas nécessaires.
- **Utiliser la délégation au lieu de l'héritage** : l'héritage crée une relation forte entre deux classes, ce qui peut rendre difficile le changement d'une classe sans affecter l'autre. La délégation, en revanche, permet à un objet de déléguer des tâches à un autre objet, ce qui peut aider à dissocier les deux objets et à réduire les dépendances.
- **Suivez le principe de responsabilité unique** : le principe de responsabilité unique stipule qu'une classe ne devrait avoir qu'une seule raison de changer. En suivant ce principe, vous pouvez contribuer à réduire le nombre de dépendances entre les objets et rendre le système plus modulaire et plus facile à modifier.

En suivant ces conseils, nous créeons un système plus modulaire, maintenable, plus facile à comprendre et à entretenir, plus facile à modifier et à réutiliser, plus testable et plus facile d'isoler les composants individuels pour les tests.
Cela peut améliorer la flexibilité et l'extensibilité du système.

*Bon apprentissage... Bon codage...*

[Source d'article](https://medium.com/@fullstacktips/20-essential-tips-for-writing-quality-code-in-java-8-and-11-f8c0f13aa13b)