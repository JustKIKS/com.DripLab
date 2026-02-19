# 💻 DripLab – Site E-commerce WordPress

<img src="/src/img/macDripLab.png" width="450" />

**DripLab** : Plateforme e-commerce **WordPress + WooCommerce** complète avec landing page interactive en **3D**. Infrastructure LAMP configurée manuellement sur Debian 12.

> 🛍️ **Site e-commerce full-featured** | 🎨 **Landing 3D** | 🖥️ **Serveur LAMP custom**

## 📦 Stack Technique

| Frontend                        | Backend           | Infrastructure |
| ------------------------------- | ----------------- | -------------- |
| HTML/CSS/JS + **Three.js** (3D) | **WordPress 6.x** | **Debian 12**  |
| **WooCommerce**                 | **PHP 8.2+**      | **Apache 2**   |
| Design Responsive               | **MariaDB**       | **Git**        |

---

## 🛠️ Installation

Infrastructure LAMP complète configurée manuellement sur Debian 12 via UTM (Mac).

**Services déployés** :

- ✅ Apache2 + modules rewrite & SSL
- ✅ MariaDB avec base `my_database`
- ✅ PHP 8.2+ avec extensions complètes
- ✅ WordPress 6.x avec WooCommerce

**Configuration réseau** : NAT mode sur UTM, IP statique via `/etc/network/interfaces`

```bash
# Sauvegarde base de données
sudo mysqldump -u user -p my_database > backup.sql
```

---

## 🛒 E-Commerce WordPress + WooCommerce

### Produits & Catalogue

| Produit                  | Description             | Prix   | Statut   |
| ------------------------ | ----------------------- | ------ | -------- |
| T-Shirt DripLab Standard | 100% coton, logo brodé  | 29.99€ | ✅ Actif |
| Hoodie DripLab Limited   | Coton/polyester premium | 79.99€ | ✅ Actif |
| Casquette Debug Mode     | Brodée, réglable        | 19.99€ | ✅ Actif |

### Fonctionnalités Implémentées

- 🛒 Catalogue produits complet
- 💳 Tunnel de paiement fictif (mode test)
- 👤 Gestion des comptes clients
- 📦 Système de commandes fonctionnel
- 📊 Dashboard WooCommerce

---

## 🎨 Landing Page 3D

**Technologie** : Three.js pour modèle 3D interactif

- Modèle 3D rotatif du robot DripLab
- Animations fluides et responsive
- Intégration seamless avec WordPress
- Experience utilisateur premium

---

## 🔧 Défis Techniques Relevés

✅ Configuration réseau NAT sur UTM  
✅ Résolution de conflits IP statiques dans `/etc/network/interfaces`  
✅ Sauvegarde complète DB avec `mysqldump`  
✅ Intégration Three.js dans WordPress  
✅ Déploiement Git avec Personal Access Token

---

## ⭐ Bonus & Optimisations

🔒 **Sécurité** : SSL/TLS Let's Encrypt  
⚡ **Performance** : WP Super Cache + compression gzip  
🎨 **Design** : Thème WordPress custom + modèle 3D  
📱 **Responsive** : Mobile-first design

---

## 📸 Galerie & Démos

| Section                | Capture                          | Notes                  |
| ---------------------- | -------------------------------- | ---------------------- |
| 🏠 Landing Page 3D     | ![Landing 3D](/src/img/img1.png) | Modèle 3D interactif   |
| 📖 Histoire de DripLab | ![Landing 3D](/src/img/img2.png) | Histoire & Projet      |
| 🛍️ Catalogue Produits  | ![Landing 3D](/src/img/img3.png) | 6 produits WooCommerce |
| 🛍️ Produits Détaillés  | ![Landing 3D](/src/img/img5.png) | Produit personnalisé   |

---

**Made With Luv by LVKA** 🎨💻
