# rapport-de-stage
Il s'agit d'un rapport de stage qui se concentre sur l'évaluation de l'impact social de l'aide à domicile sur les décès et les hospitalisations dans les structures de UNA Nord. 
Pour cela une enquête a été réalsée sur ces deux sujets auprès des structures de la fédération UNA Nord. Pour cela un modèle MCO a été utilisé 
log_deces~log_age+genre+hiver+ete+printemps+communes_riche+communes_pauvres+villages+petites_villes+villes+confinement
log_hospi~log_age+genre+log_tps+hiver+ete+printemps+communes_riche+communes_pauvres+villages+petites_villes+villes+confinement
Ces modèles sont corrigés par la méthode des moindres carrés ordinaires.
Ainsi, durant le confinement le nombre de décès a augmenté 
A l'inverse, le nombre d'hospitalisation a baissé 
