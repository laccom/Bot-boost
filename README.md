# 📜 INSTRUCTIONS D’UTILISATION – TOKEN JOINER

![image](https://github.com/user-attachments/assets/6249f571-e836-425c-8ae0-2c40881767b9)

## 🔧 PRÉREQUIS
1. Avoir Node.js installé 👉 [https://nodejs.org/](https://nodejs.org/)
2. Installer les dépendances du projet (une seule fois) :  
   Ouvre un terminal dans le dossier du script, puis tape :  
   ```> npm install```

## 🌐 CRÉER UNE CLÉ API 2CAPTCHA
1. Va sur 👉 [https://2captcha.com/](https://2captcha.com/)
2. Crée un compte ou connecte-toi.
3. Va dans ton **tableau de bord (Dashboard)**.
4. Recharge ton compte (minimum **0.50$** recommandé).
5. Récupère ta **clé API** dans la section **API Key** *(c’est une longue chaîne de caractères)*.  
   ➤ Elle sera demandée lors du premier lancement du script.

## 🔐 OBTENIR UNE CLÉ D’ACCÈS AU SCRIPT  
Pour utiliser Token Joiner, une **clé d’accès** est obligatoire.  
Cette clé est **liée à ton appareil (HWID)** et permet d’activer le script.

Pour l’obtenir :  
1. Va sur 👉 [sellauth  (ce lien)](https://laccom-bst.mysellauth.com/product/token-joiner) 
2. Achète une **clé Token Joiner** pour **5 €**  
3. La clé te sera envoyée automatiquement.  

➤ Elle te sera demandée **lors du premier lancement**.

## 📂 FICHIERS À CONFIGURER

### 1. `tokens.txt`
- Crée ce fichier à la racine si ce n’est pas déjà fait.  
- Colle dedans **un token Discord valide par ligne**.

### 2. `config.json`
- Pas besoin de le créer manuellement.  
- Lors du **premier lancement**, le script va te demander :
  - ta **clé d'accès au script**
  - ta **clé API 2Captcha**
  - le **code d’invitation Discord** (ex: `abc123` sans `discord.gg/`)

## 📦 LANCER LE SCRIPT
1. Ouvre un terminal dans le dossier du script.  
2. Tape la commande :  
```> node index.js```

## 🔚 FIN
Merci d’utiliser **TokenJoiner** 💻  
Développé par **laccom** ✨
