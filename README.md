# Automated AntiDryness Device

Use the following command for a basic website to monitor watering status

websocketd --port=8080  --staticdir=static/ tail -f /var/log/water.log
