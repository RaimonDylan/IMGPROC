# Traitement d’image
## TP N° 5 : Segmentation par attributs de texture


* 1 - Afficher l'image normalisée entre 0 et 64. Qu'observe-t-on ? Conclusion.

Meh 



* 2 - 
  * 2 - a. Calculer les valeurs moyennes des deux images attributs. Conclusion.
  
  ```matlab
  m_1 = mean(mean(texture1));
  m_2 = mean(mean(texture2));
  ```
  * 2 - b. Afficher les histogrammes des deux images attributs. On utilise pour cela la fonction hist(). Conclusion ?
* 3 -
  * 3 - a. En utilisant la fonction otsu() fournie calculer l'image segmentée de texture3.tif
  * 3 - b. Segmentation supervisée. 
  * Calculer la valeur moyenne et l'écart type de l'attribut
  * Calculer l'image binaire par seuillage