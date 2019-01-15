# esp8266-led

origin: `https://github.com/espressif/ESP8266_RTOS_SDK/tree/master/examples/peripherals/gpio`

wait 1s ↓  
output is enabled of two gpio pins ↓  
wait 1s ↓  
output isn't enabled of two gpio pins ↓  
wait 1s ↓  
output is enabled of two gpio pins ↓  
loop...  

↓ change  

output is enabled of first gpio pin  
output isn't enabled of second gpio pin ↓  
wait 3s ↓  
output isn't enabled of first gpio pin  
output is enabled of second gpio pin ↓  
wait 3s ↓  
output is enabled of first gpio pin  
output isn't enabled of second gpio pin ↓  
loop...

```bash
make menuconfig
make flash
```
