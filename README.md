## Général

- `!fc {viewer}` Affiche le statut de follow de `viewer`.  
- `!uptime` Affiche l'uptime de la session actuelle.  
- `!viewers` Affiche le nombre de viewers.  
- `!commands` / `!commandes` Affiche les commandes disponibles.  
- `!host` Affiche du lien ClickToHost! .  

### Streamer
- `!uptime_goal start {X}` Démarrage d'un objectif d'uptime de `X` heures.  
- `!uptime_goal stop` Arrêt de l'objectif.  
- `!disable_wizebot` Désactive le bot, ne retourne aucun message.  
[Réactiver Wizebot](https://panel.wizebot.tv/dashboard)  

### Viewer
- `!quote` Citation aléatoire parmi celles enregistrées.  
- `!quote add {text}` Création d'une nouvelle citation.
- `!quote purge` Purge des citations en attente.
- `!quote list` Liste toutes les citations.

### Modérateur  
- `!kick {viewer} {X}` Exclure de `viewer`pour `X` minutes.  
Si `X` n'est pas précisé, `viewer` sera exclu pendant 3 minutes par défaut.   
- `!ban {viewer}` Bannir `viewer` indéfiniment.  
- `!clean {viewer}` Supprimer tous les messages de `viewer`.  
- `~~~~~~ Warnings`
- `!warning {viewer} {reason}` / `!w {viewer} {reason}` Donne un avertissement à `viewer` avec comme message `reason`.  
- `!warning_reset {viewer}` / `!wr {viewer}` Supprime les avertissements donnés à `viewer`.    
- `~~~~~~ Permits`  
- `!permit {viewer} {length}` Donne un permis de `length` temps à `viewer` pour un seul et unique lien.  
`length` peut être un `nombre` (minutes), `session` pour la session de stream ou `perma` pour un permis permanent.  
- `~~~~~~ Modes`  
- `!subon` / `!suboff` Active / Désactive le mode Subscriber-Only.  
- `!follon` / `!folloff` Active / Désactive le mode Follower-Only.  
- `~~~~~~ Quotes`
- `!quote del {id}` Supprime la citation dont l'ID correspond à `id`.  
- `!quote val {id}` / `!quote ref {id}` Valide / Refuse la citation en attente correspondant à `id`.  
`id` peut être un ID de citation en attente ou le `viewer`.  


## SongRequest  

- [Lecteur SR](https://tools.wizebot.tv/song_request/)  

### Viewer  
- `!sr {link}` Ajoute le titre correspondant à `Lien` dans la liste de lecture.  
`link` peut être un titre de vidéo, un lien youtube ou un identifiant de vidéo youtube.   
- `!currentsong` Affichage du titre du morceau actuellement joué.  
- `!getsong` Obtenir, par message privé, le lien du morceau actuellement joué.  

### Modérateur  
- `!delsong {ID}` Suppression du titre correspondant à `ID`.  
Si `ID` n'est pas précisé, le morceau actuel sera supprimé, ce qui revient à utiliser `!skipsong`.  
- `!skipsong` Passe le morceau actuel.  
- `!startsong` Démarrage du SongRequest.  
- `!stopsong` Arrêt du SongRequest.  

