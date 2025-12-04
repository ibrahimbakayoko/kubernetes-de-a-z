# Lab3 – Services & Networking
Architecture réseau du cluster Kubernetes

Bienvenue dans le **Lab3 – Services & Networking** !  
Dans ce troisième lab, vous allez explorer comment **exposer une application dans Kubernetes** et comprendre les mécanismes réseau qui permettent aux Pods de communiquer entre eux et avec l’extérieur.  
Vous apprendrez à utiliser les différents types de Services, à comprendre le rôle de kube-proxy et à tester l’accès interne et externe à vos applications.  
À la fin du lab, vous saurez créer, configurer et tester différents Services Kubernetes pour rendre vos applications accessibles ⚡

---

### Objectifs pédagogiques
- Comprendre le rôle des Services Kubernetes  
- Découvrir les types de Services : ClusterIP, NodePort, LoadBalancer, ExternalName  
- Explorer le fonctionnement de kube-proxy et la gestion du routage  
- Exposer une application via un Service et tester l’accès interne/externe  
- Savoir nettoyer les ressources créées lors du lab  

---

### ⚙️ Pré-requis
- `kubectl` installé et configuré  
- Un cluster Kubernetes local opérationnel (k3d, Minikube ou k3s)  
- (Optionnel) Helm pour les labs suivants  

---

## Ce que vous allez faire
- Créer un Service simple pour exposer une application  
- Tester un Service de type ClusterIP avec port-forward  
- Découvrir les Services NodePort et LoadBalancer  
- Comprendre le rôle de kube-proxy dans le routage du trafic  
- Vérifier l’accès interne et externe à une application Nginx  
- Nettoyer les ressources en fin de lab  

---

## 🚀 Démarrage rapide
```bash
git clone https://github.com/ibrahimbakayoko/kubernetes-de-a-z.wiki.git
cd lab3-service
kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml
```
## 📚 Documentation complète   
Retrouvez toutes les étapes détaillées, schémas et explications dans le Wiki du projet 📂 Accès complet   
Wiki : https://lnkd.in/eFYtQCAv   
GitHub : https://lnkd.in/edud6wXX

## 🧭 Prochaines étapes ➡️ Lab4 – ConfigMaps & Secrets

➡️ Lab5 – Volumes & Persistences

➡️ Lab6 – StatefulSets & Applications avec état

👤 Auteur : Brahima BAKAYOKO   
📍 Achères, Île-de-France   
💼 Auteur du Lab Kubernetes – Services & Networking   
📫 Contact : ibra.bakayoko82@gmail.com  