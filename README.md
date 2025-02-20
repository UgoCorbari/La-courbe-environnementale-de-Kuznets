# La-courbe-environnementale-de-Kuznets
La Courbe Environnementale de Kuznets, le cas de la Chine pour la période 1990-2020.

Pour mon premier projet d'économétrie sous R, mon groupe et moi-même avons travaillé sur l'analyse de la validité de la courbe environnementale de Kuznets (ECK) pour la Chine sur la période 1990-2020. La théorie de Kuznets suggère une relation en U inversé entre le développement économique et la dégradation environnementale : dans un premier temps, la croissance entraîne une hausse des émissions polluantes, puis, à un certain niveau de richesse, ces émissions diminuent grâce à des politiques environnementales et des avancées technologiques.

Données et méthodologie :
Les données proviennent du site Our World In Data et incluent :
Variable expliquée : émissions de gaz à effet de serre (GES) par habitant (en tonnes d’équivalent CO₂).
Variable explicative : PIB par habitant (en dollars constants de 2015).
Un modèle économétrique quadratique de la forme suivante est utilisé pour tester la relation :
GES =β0+β1⋅PIB+β2⋅PIB^2+e

où β2 négatif indiquerait la présence d’un U inversé conforme à l’ECK.

Résultats

L’estimation sous R révèle une forte corrélation entre le PIB et les émissions de GES. Cependant, l’analyse graphique montre une relation globalement croissante sans inflexion claire. Les résultats économétriques confirment une significativité statistique des coefficients, avec un R2 ajusté de 97,08 %, suggérant un bon ajustement du modèle.

Conclusion

Bien que le coefficient du PIB² soit négatif et significatif, la période étudiée pourrait être trop courte pour observer un pic des émissions. De plus, la Chine étant encore en phase d’industrialisation rapide, la transition vers une réduction des émissions reste incertaine. Cette étude soulève ainsi la question du rôle des politiques environnementales et des évolutions technologiques dans l’atténuation des impacts climatiques du développement économique.
