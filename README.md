
Upgrade, compile, flash
```
pip3 install --pre -U esphome
pio upgrade
esphome compile fanitizer.yaml
esphome upload fanitizer.yaml --device 192.168.70.249
```