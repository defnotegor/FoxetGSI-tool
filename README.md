Ready-made gsi images: https://github.com/FoxetGSI/FoxetGSI-release

# English

## Requirements
    We reccomend a computer wituh 8 GB or more RAM, Linux Mint 22.1 Cinnamon or Ubuntu 20.04, hexa core CPU.
    Python3-pip and ofc, Python
    
## How to use

### Download tools
```
git clone --recurse-submodules https://github.com/defnotegor/FoxetGSI-tool.git
cd FoxetGSI-tool
```

### For setting up this tool
    sudo bash setup.sh
    sudo bash update.sh

### Generating GSI from stock firmware URL
Example: for making OxygenOS of oneplus 7 pro firmware, you can use this command
```
sudo bash url2GSI.sh https://oxygenos.oneplus.net/OnePlus7ProOxygen_21.O.07_OTA_007_all_1905120542_fc480574576b4843.zip OxygenOS
You can also use this to make GSI from local directory
sudo bash url2GSI.sh /home/defnotegor/Downloads/OnePlus7ProOxygen_21.O.07_OTA_007_all_1905120542_fc480574576b4843.zip
```
check url2GSI.sh for more info
