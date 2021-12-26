# Athom ESPHome konfigurace

Tento repozitář obsahuje konfigurace pro ESPHome do https://athom.tech zařízení.

Pokud zařízení hlásí nedostatek volného místa, musí se nejdíve nahrát `ESP8266_MINI.bin`.
- mini is a transit firmware, after running, it will generate a hotspot of "ESP_UPDATE_XXXXXX"
- Connect to the hotspot and visit `http://192.168.4.1/update` in the browser
- Upload updated ESPHome firmware

# Migrating to Tasmota

- Select firmware upgrade, upload `tasmota.bin.gz` and click Update, Please don't choose tasmota.bin!!!
- Download Tasmota firmware here http://ota.tasmota.com/tasmota/release/tasmota.bin.gz

# Migrating from Tasmota

- Prvně zadat v konzoli Tasmoty příkaz `SetOption78 1`.
- Select firmware upgrade, upload `tasmota-minimal.bin` and click start upgrade
- Select the firmware upgrade again, upload the firmware of ESPHome and click to start upgrade
- Download ESPHome firmware here https://github.com/tarontop/athom-configs/actions
