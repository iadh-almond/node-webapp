analyzing.py :
  inovoque l'API Text Analysis et renvoie un fichier JSON avec les résultats
  
ranking.py :
  créé l'index Cognitive Search sur la base d'un fichier JSON et upload les données dans cet index

⚠️⚠️⚠️ POUR L'INSTANT CES FICHIERS N'INTERAGISSENT PAS AVEC LE BLOB, ILS SONT CODÉS POUR ÊTRE UTILISÉS LOCALEMENT (à changer dès que possible)


back_end.py :
  interroge Cognitive Search pour créer les fichiers JSON utilisés par la webapp. Ces fichiers sont placés dans un file storage
  