## what fork does this use
````
tmerten/spotify-ripper
└── SolidHal/spotify-ripper
    └── wolfmanx/spotify-ripper
        └── scaronni/spotify-ripper
            └── putty182/spotify-ripper
````

## docker volume layout
````
/config
├── config.ini
├── playlists.txt
└── spotify_appkey.key

/music
└── *
````

## run
````
docker run -it -v "${PWD}/config:/config" -v "${PWD}/music:/music" putty182/spotify-ripper
````
