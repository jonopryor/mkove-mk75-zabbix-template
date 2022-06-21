# mkove-mk75-zabbix-template
Zabbix 4.0 HTTP Agent Template for mkove MK75 12V Battery Monitor

## Items
Volts
Amps
SOC
Watts

## Triggers (Set to information only, customize as desired)
BATTERY IS FULLY CHARGED
BATTERY IS NOT FULLY CHARGED
Charge rate is exceeding {$MAXCHARGEAMPS} amps
Discharge rate is exceeding {$MAXDISCHARGEAMPS} amps
Over Voltage
SOC is less than 15%
SOC is less than 25%
SOC is less than 50%
SOC is less than 75%
Using more power than generated over previous 2 hours.
Using more power than generated over previous 7 days.
Using more power than generated over previous 12 hours.
Using more power than generated over previous 24 hours.

## TODO
- Upgrade Template to Zabbix 6.0LTS
- Develop predictive forecasting triggers

## Battery Monitor Information - 
https://www.mkove.com/mk75-battery-monitor/

