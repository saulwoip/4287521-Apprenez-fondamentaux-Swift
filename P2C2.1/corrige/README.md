### 🔍 **Explication complète du code ligne par ligne**  

var maDateDeNaissance = 1992
var laDateDeNaissanceDeBarack = 1961

if maDateDeNaissance < laDateDeNaissanceDeBarack {
    print("Je suis un jeune premier !")
} else {
    print("J'ai plus d'expérience qu'un président !")
}

Voici une **explication détaillée** de **chaque ligne** du code, en expliquant **ce que Swift fait** et **ce que signifie chaque écriture**.

---

### ✅ **Code et explication ligne par ligne :**  

```swift
var maDateDeNaissance = 1992
```
#### 🔎 **Explication :**  
- **`var`** : Mot-clé qui permet de déclarer une **variable modifiable**.  
- **`maDateDeNaissance`** : Variable qui représente **ton année de naissance**.  
- **`= 1992`** : Affectation de la valeur **1992**.  
- **Type inféré** : `Int` (nombre entier).  

---

```swift
var laDateDeNaissanceDeBarack = 1961
```
#### 🔎 **Explication :**  
- **`var`** : Variable modifiable.  
- **`laDateDeNaissanceDeBarack`** : Variable représentant **l’année de naissance de Barack Obama**.  
- **`= 1961`** : Affectation de la valeur **1961**.  
- **Type inféré** : `Int`.  

---

```swift
if maDateDeNaissance < laDateDeNaissanceDeBarack {
```
#### 🔎 **Explication :**  
- **`if`** : Déclaration d’une **condition**.  
- **`maDateDeNaissance < laDateDeNaissanceDeBarack`** :  
  - Vérifie si `1992` (**ma date de naissance**) est **inférieure** à `1961` (**celle de Barack Obama**).  
  - **Faux**, car `1992` est **supérieur** à `1961`.  
- Si la condition était vraie, le code **dans les `{}` serait exécuté**.  

---

```swift
    print("Je suis un jeune premier !")
```
#### 🔎 **Explication :**  
- **Cette ligne est ignorée** car la condition précédente est **fausse**.  

---

```swift
} else {
```
#### 🔎 **Explication :**  
- **`else`** est exécuté uniquement si la condition dans `if` est **fausse**.  
- Comme `1992 < 1961` est **faux**, on passe dans cette partie du code.  

---

```swift
    print("J'ai plus d'expérience qu'un président !")
```
#### 🔎 **Explication :**  
- **Affichage d’un message** car on est dans le `else`.  
- La console affiche :  
  ```
  J'ai plus d'expérience qu'un président !
  ```

---

### 🏆 **Résumé du fonctionnement général du code**
1. **Déclaration de variables** avec deux années de naissance (`1992` et `1961`).  
2. **Comparaison avec une condition `if`** :  
   - Si `maDateDeNaissance` est plus petit que `laDateDeNaissanceDeBarack` → affiche `"Je suis un jeune premier !"`.  
   - Sinon (`else`) → affiche `"J'ai plus d'expérience qu'un président !"`.  
3. **Comme 1992 n’est pas inférieur à 1961, c’est l’instruction `else` qui s’exécute**.  

---

### 🚀 **Ce que tu as appris avec cette explication**
✔️ **Déclaration et utilisation de variables (`var`)**  
✔️ **Utilisation des types numériques (`Int`)**  
✔️ **Les conditions `if` et `else` en Swift**  
✔️ **Comparaison avec les opérateurs relationnels (`<`, `>`, `<=`, `>=`)**  
✔️ **Affichage de messages conditionnels avec `print()`**  

Avec cette explication, **tu comprends totalement le fonctionnement du code !** 🎯🔥
