💳 Système de Détection de Fraude Contextuel (ML)

Le Défi : Identifier des fraudes ultra-minoritaires (0,17 %) sans bloquer les clients légitimes (le dilemme de la "transaction à 1€ au métro").

Points Clés du Projet :

    Feature Engineering Avancé : Création de variables de vélocité temporelle et transformation du temps cyclique (sin/cos) pour capturer les comportements suspects.

    Stratégie Data : Utilisation du split stratifié et de SMOTE (équilibrage à 10 %) pour amplifier le signal de fraude sans créer d'overfitting.

    Modélisation : Pipeline industriel avec XGBoost, optimisé sur l'AUPRC (0.84) plutôt que l'accuracy.

    Vision Produit : Architecture conçue pour l'intégration en temps réel avec un système d'authentification dynamique (Step-up).

Outils : Python, Scikit-Learn, XGBoost, SMOTE, Joblib.
