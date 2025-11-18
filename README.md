## Instructions

1. Ensure you have your Enphase System with Micro Inverters setup and running via [(Enphase Envoy Integration)](https://www.home-assistant.io/integrations/enphase_envoy/).
2. Ensure you have setup and configured the [(Forecast.Solar Integration )](https://www.home-assistant.io/integrations/forecast_solar/).
3. Add the sections from [configuration.yaml](./configuration.yaml) into your Home Assistant configuration.yaml - note you may need to massage this if you already have a sensor section.
4. Ensure the Forecast.Solar sensor "Estimate Power Production - Now" is showing as sensor.power_production_now
5. Setup the dashboards - adjusting the sennsors to match yours again as per above.
6. Change the following sensors to match your sensors in all files:
   - sensor.inverter_1000000000xx
   - sensor.inverter_2000000000xx
   - sensor.envoy_100000000001_current_power_production

## License

This repository is licensed under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to share and adapt the material for **non-commercial purposes**, as long as you  
**provide attribution** and **use the same license** on any derivative works.

See the [LICENSE](./LICENSE) file for the full text.
