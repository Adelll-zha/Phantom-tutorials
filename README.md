# Paramètres Globaux de l'Application

## Introduction
Ce document décrit les paramètres globaux utilisés dans l'application. Ces paramètres sont cruciaux pour configurer et ajuster le comportement de l'application en fonction des besoins spécifiques.

## Paramètres Globaux

### fov_x_global
- **Description** : Définit le champ de vision horizontal.
- **Utilisation** : Ce paramètre contrôle l'angle de vision horizontal capturé par le système.

### fov_y_global
- **Description** : Définit le champ de vision vertical.
- **Utilisation** : Ce paramètre contrôle l'angle de vision vertical capturé par le système.

### center_x_global
- **Description** : Coordonnée X du centre du champ de vision.
- **Utilisation** : Permet de définir la position horizontale du centre de l'image ou de la scène capturée.

### center_y_global
- **Description** : Coordonnée Y du centre du champ de vision.
- **Utilisation** : Permet de définir la position verticale du centre de l'image ou de la scène capturée.

### intensity_global
- **Description** : Intensité ou sensibilité de la détection.
- **Utilisation** : Contrôle la réactivité du système, par exemple dans la détection de mouvements ou d'objets.

### delay_global
- **Description** : Délai entre chaque cycle de traitement.
- **Utilisation** : Utilisé pour ajuster la fréquence de traitement ou de capture.

### lower_color_h_global
- **Description** : Limite inférieure de la détection de couleur pour la teinte (H).
- **Utilisation** : Définit la valeur minimale pour la détection de couleurs spécifiques dans l'image.

### lower_color_s_global
- **Description** : Limite inférieure de la détection de couleur pour la saturation (S).
- **Utilisation** : Définit la valeur minimale pour la détection de couleurs spécifiques dans l'image.

### lower_color_v_global
- **Description** : Limite inférieure de la détection de couleur pour la valeur (V).
- **Utilisation** : Définit la valeur minimale pour la détection de couleurs spécifiques dans l'image.

### upper_color_h_global
- **Description** : Limite supérieure de la détection de couleur pour la teinte (H).
- **Utilisation** : Définit la valeur maximale pour la détection de couleurs spécifiques.

### upper_color_s_global
- **Description** : Limite supérieure de la détection de couleur pour la saturation (S).
- **Utilisation** : Définit la valeur maximale pour la détection de couleurs spécifiques.

### upper_color_v_global
- **Description** : Limite supérieure de la détection de couleur pour la valeur (V).
- **Utilisation** : Définit la valeur maximale pour la détection de couleurs spécifiques.

### threshold_global
- **Description** : Seuil utilisé dans le traitement d'image.
- **Utilisation** : Détermine la sensibilité du système pour détecter des changements ou des contours.

### maxlen_global
- **Description** : Longueur maximale pour certaines structures de données, comme les files d'attente ou les buffers.
- **Utilisation** : Utilisé pour limiter la quantité de données stockées ou traitées à la fois.

### micro_correction_global
- **Description** : Ajustement fin pour corriger de petites erreurs.
- **Utilisation** : Améliore la précision du système en apportant de légères corrections automatiques.

### yt_global
- **Description** : Tolérance de détection sur l'axe X.
- **Utilisation** : Ajuste la marge d'erreur acceptée pour la détection sur l'axe horizontal (X).

### tolerance_global
- **Description** : Tolérance pour les tremblements sur l'axe X.
- **Utilisation** : Contrôle la tolérance du système face aux tremblements ou aux petits mouvements involontaires sur l'axe X.

### min_contour_area_global
- **Description** : Aire minimale des contours détectés.
- **Utilisation** : Filtre les petits objets ou bruits en ne conservant que les contours d'une certaine taille.

### max_contour_area_global
- **Description** : Aire maximale des contours détectés.
- **Utilisation** : Limite la détection aux objets de taille raisonnable.

### transfert_global
- **Description** : Paramètre contrôlant le transfert de données ou d'états.
- **Utilisation** : Gère la manière dont les informations sont échangées ou appliquées au sein du système.

### current_sens_global
- **Description** : Sensibilité actuelle du système.
- **Utilisation** : Ajuste la réactivité du système aux entrées ou aux changements détectés.

### current_dpi_global
- **Description** : DPI (dots per inch) actuel utilisé par le système.
- **Utilisation** : Définit la résolution ou la sensibilité des mouvements.

### target_dpi_global
- **Description** : DPI cible.
- **Utilisation** : Sert à recalibrer ou ajuster la précision en fonction de la cible.

### zoom_factor_global
- **Description** : Facteur de zoom actuel.
- **Utilisation** : Détermine le niveau de zoom appliqué à une image ou une scène.

### max_zoom_factor_global
- **Description** : Facteur de zoom maximum permis par le système.
- **Utilisation** : Limite le zoom pour éviter des distorsions ou des pertes de qualité.

## Conclusion
Les paramètres globaux jouent un rôle essentiel dans la configuration et le contrôle de l'application. En ajustant ces paramètres, les utilisateurs peuvent personnaliser le comportement du système pour répondre à des besoins spécifiques.
