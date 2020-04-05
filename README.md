### Použití
1. Nahrát složku jako resource a spustit v __config.lua__
2. Otevři __esx_status/client/main.lua__
3. Najdi ±71. řádek: __TriggerEvent('esx_status:onTick', GetStatusData(true))__
4. Přepiš na novou hodnotu: __TriggerEvent('esx_statushud:onTick', GetStatusData(true))__
5. Otevři __esx_basicneeds/client/main.lua__ a přepiš řádky __±43__ a __±49__ na hodnotu __false__
     - Původní: **return true**
     - Nová: **return false**

Zdroj: *Původní resource není můj, pouze je upraven vzhled.*

### Obrázek
![alt text](https://cdn.discordapp.com/attachments/696442851848093756/696454083586031737/20200403164438_1.jpg)
