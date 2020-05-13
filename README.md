# Zephyrus G14 Linux

--------

## Specs

Model: `GA401IV-BR9N6`
Kernel: `linux 5.6.11.arch1-1`
BIOS: `???`

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
| Audio                     |                  |            | ❓      | 
| Microphone                |                  |            | ❓      | 
| Touchpad                  |                  |            | ❓      | 
| Power management 	        |                  |            | ❓      | 
| Bluetooth 	            |                  |            | ❓      |  
| ROG Button                |                  |            | ❓      | 
| Media Keys                |                  |            | ❓      | 
| Brightness Keys           |                  |            | ❓      | 

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

## Exploratory Sites
### Reviews
https://arstechnica.com/gadgets/2020/04/linux-on-laptops-asus-zephyrus-g14-with-ryzen-9-4900hs/
https://www.reddit.com/r/linuxhardware/comments/g2n8wn/asus_zephyrus_g14_the_first_few_hours_on_linux/

### Issues
https://adoredtv.com/rog-zephyrus-g14-battery-life-investigation-poor-battery-life-issue-diagnosed/

### Specs
https://www.ultrabookreview.com/37852-asus-zephryus-g14-ryzen-9-4900hs/
https://www.ultrabookreview.com/36081-asus-rog-zephyrus-g14-ga401iv-review/
https://www.ultrabookreview.com/35985-amd-ryzen-4900h-4900hs-laptops/