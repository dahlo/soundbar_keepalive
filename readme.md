# Soundbar keepalive
Using SoX v14.4.2 to play a low frequency sound clip that keeps the soundbar from turning off due to inactivity.

# Crontab entry
```bash
# keep soundbar alive
*/10 * * * * XDG_RUNTIME_DIR=/run/user/1000 /usr/bin/play -q ~/soundbar_keepalive/5hz_0.5s.wav
```

