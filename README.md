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

## The ROG Button
If it's possible to hijack the rog button, my current plans are to use PRIME to change the fan profiles to be more gaming focused and enable the dGPU. Another press would turn on silent mode and disable the iGPU.

Initial thoughts might be:
| Mode      | dGPU | iGPU | Notes
|-----------|:----:|:----:|------
| Standard  |      | X    | *default* Silent Fan Profile
| Gaming    | X    |      | Gaming Profile (maybe like "Turbo" mode on armory)
| Powersave |      | X    | Silent Fan Profile + cpu downclock

## Fan Profiles
Need to determine the default fan profile speeds in windows, and alternatively
the fan speed profiles in ASUS Armory.

**Example:**
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
