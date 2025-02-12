### 🔍 **Explication complète du code ligne par ligne**  

// Les repas
print("Joe a passé \(45*3*365*42) minutes à table")

// La différence d'âge
print("La différence d'âge moyenne entre Joe et ses enfants est de \((1996+1992)/2-1979) ans")

// Le salaire
print("Joe a gagné \((33000-23000) * 2) euros de plus sur 2 ans en devenant developpeur iOS")


Voici une **explication détaillée** de **chaque ligne** du code, en expliquant **ce que Swift fait** et **ce que signifie chaque écriture**.

---

### ✅ **Code et explication ligne par ligne :**  

```swift
// Pour vérifier le résultat dans la console, on utilise des print(), ensuite suivi de l'appuie sur le bouton "Run" en bas à droite
// Ex : print(1 + 1)
// Ensuite, vous pouvez appuyer sur la question pour valider le résultat
```
#### 🔎 **Explication :**  
- Cette section est un **commentaire**.  
- Un commentaire commence par `//` en Swift.  
- Les commentaires **ne sont pas exécutés par le programme**.  
- Ici, on explique comment utiliser la fonction `print()` pour afficher des résultats dans la console.  

---

```swift
// Les repas
print("Joe a passé \(45*3*365*42) minutes à table")
```
#### 🔎 **Explication :**  
- **`print()`** est une fonction intégrée de Swift qui affiche du texte ou des valeurs dans la console.  
- **Chaîne de caractères (`String`)** : `"Joe a passé \(...) minutes à table"`  
- **Interpolation de chaîne** : `\(...)` permet d'inclure un calcul directement dans le texte.  
- **Calcul** :  
  - `45` → minutes par repas  
  - `3` → repas par jour  
  - `365` → jours par an  
  - `42` → années  
- **Multiplication (`*`)** : Swift effectue d'abord le calcul `45 * 3 * 365 * 42`  
- **Le résultat est inséré dans la chaîne** grâce à `\(...)` et sera affiché dans la console.  

---

```swift
// La différence d'âge
print("La différence d'âge moyenne entre Joe et ses enfants est de \((1996+1992)/2-1979) ans")
```
#### 🔎 **Explication :**  
- **Interpolation de chaîne** : `\((1996+1992)/2-1979)` insère le résultat du calcul dans la phrase.  
- **Calcul détaillé** :  
  - `1996 + 1992` → Addition des années de naissance des enfants de Joe.  
  - `(...) / 2` → Division par 2 pour obtenir **l'année moyenne de naissance**.  
  - `- 1979` → Soustraction de l'année de naissance de Joe pour obtenir **la différence d'âge**.  
- **Swift suit les priorités des opérations** :  
  - Addition en premier `(1996 + 1992) = 3988`  
  - Division ensuite `3988 / 2 = 1994`  
  - Soustraction `1994 - 1979 = 15`  
- **Le résultat est inséré dans la phrase et affiché** dans la console.  

---

```swift
// Le salaire
print("Joe a gagné \((33000-23000) * 2) euros de plus sur 2 ans en devenant developpeur iOS")
```
#### 🔎 **Explication :**  
- **Interpolation de chaîne** : `\((33000-23000) * 2)` insère le résultat du calcul dans la phrase.  
- **Calcul détaillé** :  
  - `(33000 - 23000)` → Différence de salaire avant et après devenir développeur iOS.  
  - `(...) * 2` → Multiplie par 2 pour calculer **l'augmentation sur 2 ans**.  
- **Swift suit les priorités des opérations** :  
  - Soustraction d'abord `(33000 - 23000) = 10000`  
  - Multiplication `10000 * 2 = 20000`  
- **Le résultat est inséré dans la phrase et affiché** dans la console.  

---

### 🏆 **Résumé du fonctionnement général du code**
1. **Utilisation de `print()`** pour afficher des phrases avec des calculs intégrés.  
2. **Interpolation de chaîne** `\(expression)` permet d’insérer directement des calculs dans une chaîne de caractères.  
3. **Priorités des opérations** respectées automatiquement par Swift.  
4. **Utilisation des opérateurs mathématiques** `+`, `-`, `*`, `/` pour effectuer des calculs dynamiques.  

---

### 🚀 **Ce que tu as appris avec cette explication**
✔️ **Comment utiliser `print()` pour afficher des informations en Swift**  
✔️ **Comment insérer des calculs directement dans des chaînes de caractères (`\(...`)**  
✔️ **Les priorités des opérations mathématiques en Swift**  
✔️ **Comment Swift interprète et évalue les expressions mathématiques**  

Avec cette explication, **tu comprends totalement ce que fait le code !** 🎯🔥
