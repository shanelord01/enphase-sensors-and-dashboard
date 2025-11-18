## Instructions

1. Ensure you have your Enphase System with Micro Inverters setup and running via [Enphase Envoy Integration](https://www.home-assistant.io/integrations/enphase_envoy/).
2. Ensure you have setup and configured the [Forecast.Solar Integration](https://www.home-assistant.io/integrations/forecast_solar/).
3. Add the sections from [configuration.yaml](./configuration.yaml) into your Home Assistant configuration.yaml - note you may need to massage this if you already have a sensor section.
4. Ensure the Forecast.Solar sensor "Estimate Power Production - Now" is showing as sensor.power_production_now
5. Setup the dashboards - adjusting the sennsors to match yours again as per above.
6. Change the following sensors to match your sensors in all files:
   - sensor.inverter_1000000000xx
   - sensor.inverter_2000000000xx
   - sensor.envoy_100000000001_current_power_production

## Screenshots
<img width="484" height="202" alt="solar-curtailment-card" src="https://github.com/user-attachments/assets/c03d1c56-079f-40ee-a9f7-4c5b312f313d" />
<img width="1039" height="1211" alt="solar-curtailment-dashboard" src="https://github.com/user-attachments/assets/3c3bdd8f-b017-462f-a690-770bdbf863e4" />

## License

This repository is licensed under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to share and adapt the material for **non-commercial purposes**, as long as you  
**provide attribution** and **use the same license** on any derivative works.

See the [LICENSE](./LICENSE) file for the full text.
