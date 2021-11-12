# NoteBlockAPI
This is a modified version of the offical NoteblockAPI.

#### Modifications:
- Shadeable

#### Usage:
```java
Song song = NBSDecoder.parse(file);
songPlayer = new RadioSongPlayer(song);
for(Player online : Bukkit.getOnlinePlayers()) {
  songPlayer.addPlayer(online);
}
songPlayer.setPlaying(true);
```

`file` Is the location of the nbs file (Java File)

Original:
https://github.com/koca2000/NoteBlockAPI