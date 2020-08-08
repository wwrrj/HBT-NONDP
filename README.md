## Using Erfan's Tools


Without Erfan's Scripts all this would be not possible . This tool uses the help from GitHub Actions and Erfan's tool to complete the builds . 

with the help of this tool we will be able to build GSIs much more quickly to meet the users requiremnets. 

Android 9 : 

ColorOS Flyme Generic MIUI Moto Nubia OneUI OxygenOS Pixel Xperia ZUI ZenUI JoyUI  RogUI  VOS 

Android 10:

Generic MIUI OxygenOS Pixel ZenUI ColorOS
                   
                         
                        
                        
   Android 11:                   
Generic Pixel
                                    EXAMPLE;
...........................................................................

    types: [started]
    
env:
  ROM_URL: http://tdrive.manofuranium.workers.dev/xiaomi.eu_multi_HMK20ProMI9TPro_20.8.6_v12-10.zip
  ROM_NAME: MIUI  {just use the exact code"MIUI" , not "MIUIeu "}
  ZIP_NAME: MIUI-helios
  TZ: Asia
jobs:
  build:
    runs-on: ubuntu-latest

    steps:
       - name: Checkout
         uses: actions/checkout

,...................................
