# Discord bot

A Discord bot using Youtube, Twitter, Spotify, Google Translate, Open Weather Map & PokeAPI APIs.

## Available commands

### Youtube

Retrieves a search result for videos, channels, playlists and lives.

```
!youtube React conf 2019

!youtube pop playlist

!youtube sport live
```

### Spotify

Retrieves a search result for musics, artists and albums.

```
!spotify Smash Mouth - All Star
```

* Option !type : optionnal parameter to specify the result type ('track', 'artist' & 'album').

```
!spotify Kygo !type artist
```

### Open Weather Map

Provides weather data for the sepcfied location with a 5 days forecast.

```
!weather Santa Monica
```

### Google Translate

Translates the provided string in english, auto detecting the source language.

```
!translate Bonjour
```

* Option !lang : optionnal parameter to specify a source language from a country code ISO ALPHA-2.

```
!translate Bonjour !lang es
```

### Twitter

Tweets content using @FalconIsep account.

```
!twitter !tweet This is not a tweet 
```

Retrieves search result for @FalconIsep.

```
!twitter !stream 
```
