# Zephyrus G14 Linux

## Specs
Model: `GA401IV-BR9N6`
Kernel: `linux 5.6.11.arch1-1`

--------

✔️ = Working
⚠️ = Working, with issues
⭕ = Not Working
❓  = Not Tested

| Device                    | Name             | Driver/Ver | Status  | Notes
| ------------------------- | ---------------- | ---------- | :------:| ----- 
| iGPU  	                | Radeon Vega      |            | ❓      | 
| dGPU                  	| Nvidia RTX™ 2060 |            | ❓      | 
| HDMI                      |                  |            | ❓      | 
| Wireless                  | Intel AX20       |            | ❓      | 
| Audio                     | ???              |            | ❓      | 
| Touchpad                  | ???              |            | ❓      | 
| Power management 	        |                  |            | ❓      | 
| Bluetooth 	            | ???              |            | ❓      |  


## Fan Profiles
1. Determine the default fan profile speeds

Example:
### Windows Base
| RPM   | °C  | %  | Notes    
|-------|-----|----|------       
| 1000  | 32  | 20 |
| 2000  | 32  | 40 |
| 3000  | 32  | 60 |
| 4000  | 32  | 80 |
| 5000  | 32  | 10 |

## Exploratory Notes
1. USB-C may be connected to the dGPU - Port/Charging May not work when disabled.
