
<Center><title>Bienvenue sur le site de Jakob </title><center>

<body> 
<H1>Bienvenue sur mon site</H1>
<img src="https://th.bing.com/th/id/OIP.9ZCoY26vWmM5iIgAPJXdFgHaDt?w=323&h=174&c=7&r=0&o=5&dpr=1.3&pid=1.7"  width="900" height="500">

<br>
</body>
<body>
    <h1>Webradio Party</h1>

    <p>Click on the play button to play a sound:</p>
    
    <script src="https://shoutstream.co.uk/player-min.js"></script>
    <script id="radioFloPlayer">
    radioFloPlayer.embed({
    'url': 'https://broadcast.shoutstream.co.uk:8006/stream',
    'station-name': 'Webradio',
    'autoplay': true,
    'skin': 'dark',
    'width': 300
     });
     </script>
     <body>
        <style>
            body {
              background-color: #18aeaef1;
            }
          </style>
     </body>
     


!DOCTYPE html><html lang=en><head><title>Impostor</title><meta name=viewport content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no"><meta name=description content="A spaceship is travelling in endless space, and its crew is trying to survive. There is an impostor among them and they need to stay on guard. They need to be aware of empty rooms, and be ready for an attack when left alone with someone else, what if that someone is the impostor. The Impostor wants to kill everyone and will stop at nothing, even if it means sabotaging the ship. He is cunning and sneaky. He can hide in dark corners and wait for his victim, or suddenly jump out of a ventilation shaft and attack from behind. It is difficult to identify him among the crew members, unless he makes a mistake. You wouldn&#39;t do that, would you, Impostor?"><meta name=keywords content=#top,#survival,#spaceship,#mafia,arcade><meta property=og:type content=website><meta property=og:title content=Impostor><meta property=og:description content="A spaceship is travelling in endless space, and its crew is trying to survive. There is an impostor among them and they need to stay on guard. They need to be aware of empty rooms, and be ready for an attack when left alone with someone else, what if that someone is the impostor. The Impostor wants to kill everyone and will stop at nothing, even if it means sabotaging the ship. He is cunning and sneaky. He can hide in dark corners and wait for his victim, or suddenly jump out of a ventilation shaft and attack from behind. It is difficult to identify him among the crew members, unless he makes a mistake. You wouldn&#39;t do that, would you, Impostor?"><meta property=og:image content=https://img.gamedistribution.com/9abe6af0fbb440b98a3e24bf7fb0636a-512x512.jpeg><meta property=og:url content=https://html5.gamedistribution.com/9abe6af0fbb440b98a3e24bf7fb0636a/ ><link rel=canonical href=https://html5.gamedistribution.com/9abe6af0fbb440b98a3e24bf7fb0636a/ ><link rel=manifest href=manifest_1.5.16.json><link rel=preconnect href=https://html5.api.gamedistribution.com><link rel=preconnect href=https://game.api.gamedistribution.com><link rel=preconnect href=https://pm.gamedistribution.com><script type=text/javascript>if ('serviceWorker' in navigator) {
    navigator
      .serviceWorker
      .register(`/sw_1.5.16.js`)
      .then(function () {
        console.log('SW registered...');
      })
      .catch(err => {
        console.log('SW not registered...', err.message);
      });
  }</script><script type=application/ld+json>{
  "@context": "http://schema.org",
  "@type": "Game",
  "name": "Impostor",
  "url": "https://html5.gamedistribution.com/9abe6af0fbb440b98a3e24bf7fb0636a/",
  "image": "https://img.gamedistribution.com/9abe6af0fbb440b98a3e24bf7fb0636a-512x512.jpeg",    
  "description": "A spaceship is travelling in endless space, and its crew is trying to survive. There is an impostor among them and they need to stay on guard. They need to be aware of empty rooms, and be ready for an attack when left alone with someone else, what if that someone is the impostor. The Impostor wants to kill everyone and will stop at nothing, even if it means sabotaging the ship. He is cunning and sneaky. He can hide in dark corners and wait for his victim, or suddenly jump out of a ventilation shaft and attack from behind. It is difficult to identify him among the crew members, unless he makes a mistake. You wouldn&#39;t do that, would you, Impostor?",
  "creator":{
    "name":"DRA"
    
    },
  "publisher":{
    "name":"GameDistribution",
    "url":"https://gamedistribution.com/games/impostor"
    },
  "genre":[
      "#top",
      "#survival",
      "#spaceship",
      "#mafia",
      "arcade"
  ]
}</script><style>html{height:100%}body{margin:0;padding:0;background-color:#000;overflow:hidden;height:100%}#game{position:absolute;top:0;left:0;width:0;height:0;overflow:hidden;max-width:100%;max-height:100%;min-width:100%;min-height:100%;box-sizing:border-box}</style></head><body><iframe id=game frameborder=0 allow=autoplay allowfullscreen seamless scrolling=no></iframe><script type=text/javascript>(function () {
    function GameLoader() {
      this.init = function () {
        this._gameId = "9abe6af0fbb440b98a3e24bf7fb0636a";
        this._container = document.getElementById("game");
        this._loader = this._getLoaderData();
        this._hasImpression = false;
        this._hasSuccess = false;
        this._insertGameSDK();
        this._softgamesDomains = this._getDomainData();
      };

      this._getLoaderData = function () {
        return {"enabled":true,"sdk_version":"1.15.2"};
      }

      this._getDomainData = function(){
        return [{"name":"minigame.aeriagames.jp","id":4217},{"name":"localhost:8080","id":4217},{"name":"minigame-stg.aeriagames.jp","id":4217}];
      }

      this._insertGameSDK = function () {
        if (!this._gameId) return;

        window["GD_OPTIONS"] = {
          gameId: this._gameId,
          loader: this._loader,
          onLoaderEvent: this._onLoaderEvent.bind(this),
          onEvent: this._onEvent.bind(this)
        };

        (function (d, s, id) {
          var js,fjs = d.getElementsByTagName(s)[0];
          if (d.getElementById(id)) return;
          js = d.createElement(s);
          js.id = id;
          js.src = "https://html5.api.gamedistribution.com/main.min.js";
          fjs.parentNode.insertBefore(js, fjs);
        })(document, "script", "gamedistribution-jssdk");
      };

      this._loadGame = function (options) {

        if (this._container_initialized) {
          return;
        }

        var formatTokenURLSearch = this._bridge.exports.formatTokenURLSearch;
        var extendUrlQuery = this._bridge.exports.extendUrlQuery;
        var base64Encode = this._bridge.exports.base64Encode;
        const ln_param = new URLSearchParams(window.location.search).get('lang');

        var data = {
          parentURL: this._bridge.parentURL,
          parentDomain: this._bridge.parentDomain,
          topDomain: this._bridge.topDomain,
          hasImpression: options.hasImpression,
          loaderEnabled: true,
          host: window.location.hostname,
          version: "1.5.16"
        };

        var searchPart = formatTokenURLSearch(data);
        var gameSrc = "//html5.gamedistribution.com/rvvASMiM/9abe6af0fbb440b98a3e24bf7fb0636a/index.html" + searchPart;
        this._container.src = gameSrc;

        this._container.onload = this._onFrameLoaded.bind(this);

        this._container_initialized = true;
      };

      this._onLoaderEvent = function (event) {
        switch (event.name) {
          case "LOADER_DATA":
            this._bridge = event.message.bridge;
            this._game = event.message.game;
            break;
        }
      };

      this._onEvent = function (event) {
        switch (event.name) {
          case "SDK_GAME_START":
            this._bridge && this._loadGame({hasImpression: this._hasImpression});
            break;
          case "AD_ERROR":
          case "AD_SDK_CANCELED":
            this._hasImpression = false || this._hasSuccess;
            break;
          case "ALL_ADS_COMPLETED":
          case "COMPLETE":
          case "USER_CLOSE":
          case "SKIPPED":
            this._hasImpression = true;
            this._hasSuccess = true;
            break;
        }
      };

      this._onFrameLoaded=function(event){
        var container=this._container;
        setTimeout(function(){
          try{
            container.contentWindow.focus();
          }catch(err){
          }
        },100);
      }
    }
    new GameLoader().init();
  })();</script></body></html>
