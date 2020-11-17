# Test ReactNative HappyRenting

### Tout d’abord, quelques brèves informations
Voici un ensemble d'exercices que nous aimerions que tu réalises. Comme il existe de nombreuses façons d'aborder chaque exercice, il est important de comprendre que nous ne cherchons pas une réponse précise. Chaque exercice servira simplement de base pour une discussion où nous pourrons apprendre sur ton processus de pensée et de choix concernant leur mise en œuvre.

Quelques lignes directrices :

- Tu créeras un dépôt avec des branches distinctes (nommées en conséquence) pour chacun des exercices.
- Pour les besoins de ces exercices, tu pourras utiliser `create-react-native-app` ou `expo-cli` pour créer rapidement une nouvelle application React Native, ou tout simplement directement avec `react-native`.

Cela dit, bonne chance !

```javascript
const cities = [
  { id: 1, name: 'New York', country: 'United States' },
  { id: 2, name: 'London', country: 'England' },
  { id: 3, name: 'Berlin', country: 'Germany' },
  { id: 4, name: 'Paris', country: 'France' },
  { id: 5, name: 'Madrid', country: 'Spain' },
  { id: 6, name: 'Rome', country: 'Italy' },
  { id: 7, name: 'Brussels', country: 'Belgium' },
  { id: 8, name: 'Lisbonne', country: 'Portugal' }
]
```

## Exercice 1

Étant donné le tableau (voir ci-dessus) qui consiste en des objets contenant des informations concernant certaines villes, nous avons besoin de ton aide pour envelopper le nom et le pays d'origine de chaque ville dans une FlatList dans l’écran principal de l’application.

## Exercice 2

Splendide ! Mais... Curieux que nous sommes, nous aimerions également savoir quand quelqu’un clique sur une ville spécifique dans la liste. Un `console.warn()` fera l’affaire, mais tu peux aussi t'amuser si tu connais un moyen rapide d’afficher les clics.

## Exercice 3

Cette fois-ci, nous devons mettre en œuvre une fonctionnalité qui nous permet de filtrer la liste affichée des villes en fonction de leurs pays d'origine. L’exigence est qu’un utilisateur soit autorisé à sélectionner plusieurs emplacements à filtrer. Comment gèéres-tu cela?

## Exercice 4

Redux time ! Comment réimplanter l’exercice 3 avec Redux (pour le "state management") ?
