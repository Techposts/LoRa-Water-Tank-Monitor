# Self-Hosting TankSync

**Full, current guide → [Self-Host Guide (wiki)](https://github.com/Techposts/TankSync/wiki/Self-Host-Guide).**

TankSync is local-first. The hub's web UI, LoRa reception, LED/buzzer, OTA, and the
Home Assistant integration all work with **no cloud at all**. You can run the entire
telemetry stack on your own infrastructure — your own **Mosquitto MQTT broker** +
**Home Assistant** — with zero dependency on `mqtt.smartghar.org`.

> **What "self-host" means here.** The hosted cloud dashboard (the PWA at
> `tanksync.smartghar.org`) is a separate **proprietary** product — its server source is
> **not** in this open-source repo, so there is no cloud app to build/self-host from here.
> Self-hosting means pointing the hub at **your own MQTT broker + Home Assistant**. You
> keep every on-hub feature and the full HA integration; you give up only the hosted PWA.

See the [Self-Host Guide](https://github.com/Techposts/TankSync/wiki/Self-Host-Guide) for
the step-by-step (Mosquitto config, HA setup, fully-offline operation).
