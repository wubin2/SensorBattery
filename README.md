# SensorBattery

components目录路径在：/home/homeassistant/.homeassistant/custom_components或/srv/homeassistant/homeassistant_venv/lib/python3.4/site-packages/homeassistant/components


1、上传附件脚本binarybattery.py和sensorbattery.py到components目录。

2、在configuration.yaml中插入所有使用电池的传感器的Entity ID

3、在groups.yaml里建立电量card，Entity ID为传感器Entity ID_battery
