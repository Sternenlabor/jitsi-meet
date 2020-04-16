# Kompilieren

```bash
λ npm i
λ sass css\main.scss css\all.css
```

# Dateien auf Server schieben

```bash
λ scp css/all.css Andre@mumble.sternenlabor.de:/home/Andre/all.css
λ scp static\welcomePageAdditionalContent.html Andre@mumble.sternenlabor.de:/home/Andre/welcomePageAdditionalContent.html
λ scp interface_config.js Andre@mumble.sternenlabor.de:/home/Andre/interface_config.js
```

# Anschließend auf Server ins richtige Verzeichnis kopieren

```bash
Andre@Server:~$ sudo cp all.css /usr/share/jitsi-meet/css/all.css
Andre@Server:~$ sudo cp welcomePageAdditionalContent.html /usr/share/jitsi-meet/static/welcomePageAdditionalContent.html
Andre@Server:~$ sudo cp interface_config.js /usr/share/jitsi-meet/interface_config.js
```
