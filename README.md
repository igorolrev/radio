
# Lyrics



# Example service:
    URL API: ic.lyrics.ks
[![N|Solid](https://github.com/igorolrev/radio/raw/master/Images/openInRadio.png)](radioxapp://lyrics=ic.lyrics.ks)

# Example APISEEDS 
    URL API: https://orion.apiseeds.com/api/music/lyric/
- https://orion.apiseeds.com/documentation/lyrics
[Get your FREE Api Key](https://orion.apiseeds.com/)

# Example Other API
    URL :url/:artist/:track or :url/:artist/:track?apikey=:key
- output JSON #1:
```json
    {
        "result": {
            "track": {
                "text": "TEXT",
            }
        }
    } 
```
- output JSON #2:
```json
    {
        "lyric": "TEXT",
        "err":"none"
    }
```
