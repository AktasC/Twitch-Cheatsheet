# Général

## Bot
- `!disable_wizebot` Désactive le bot, ne retourne aucun message.  
[Réactiver Wizebot](https://panel.wizebot.tv/dashboard)

## Modération  
- `!kick {viewer} {X}` Exclure de `viewer`pour `X` minutes.  
Si `X` n'est pas précisé, `viewer` sera exclu pendant 3 minutes par défaut.   
- `!ban {viewer}` Bannir `viewer` indéfiniment.
- `!subon` Active le mode Subscriber-Only.  
- `!suboff` Désactive ce mode.  
- `!follon` Active le mode Follower-Only.  
- `!folloff` Désactive ce mode.  




# SongRequest  
- [Lecteur SR](https://tools.wizebot.tv/song_request/)  

### Viewer  
- `!sr {lien}` Ajoute le titre correspondant à `Lien` dans la liste de lecture.  
`lien` peut être un nom de vidéo, un lien youtube ou un identifiant de vidéo youtube.   
- `!currentsong` Affichage du titre du morceau actuellement joué.  
- `!getsong` Obtenir, par message privé, le lien du morceau actuellement joué.  

### Modérateur  
- `!delsong {ID}` Suppression du titre correspondant à `ID`.  
Si `ID` n'est pas précisé, le morceau actuel sera supprimé, ce qui revient à utiliser `!skipsong`.  
- `!skipsong` Passe le morceau actuel.  
- `!startsong` Démarrage du SongRequest.  
- `!stopsong` Arrêt du SongRequest.  

