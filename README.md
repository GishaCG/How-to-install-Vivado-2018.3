# How-to-install-Vivado-2018.3
Installing Vivado 2018.3 WebPACK in Ubuntu

Need > 7.90 GB memory space           //Make sure you have it

Step 1: Go to : https://www.xilinx.com/support/download.html

Step 2: Go to Vivado Design Suite - HLx Editions - 20xx.x  Full Product

Step 3: Click on Vivado HLx 20xx.x: WebPACK and Editions - Linux Self Extracting Web Installer (BIN - xxx.xx MB)

Step 4: Sign in into your Xilinx account (or) Create one

Step 5: (a) If you already have an account Click "Download" at the end of the page
        (b) If you are creating a new account>>Open registered Email>>Activate account>>Download
        
Step 6: Save File to "Downloads"      // Or to any loaction

Step 7: Go to Files >> Downloads >> Right Click >> Open in Terminal

Step 8: Type $ "sudo ./Xilinx_Vivado_SDK_Web_2018.3_1207_2324_Lin64.bin" 

                                      // Installing in sudo otherwise it could not automatically 
                                          create folder Xilinx in tools
Step 9: It will auto automatically open Vivado Installer >> Next

Step 10: Tick all 3 boxes (End user License, WebTalk & Third party) >> Next

Step 11: Select the products needed >> Next

Step 12: Tick Create program group entries and create desktop shortcut >> Next

Step 13: Click Install        //It will downloaded, Install and do Final Processing
                              // Mine was installed in tools/Xilinx
                              // Take approximately 1 hour

Step 14: After installation open Terminal

Step 15: Type: $ source /tools/Xilinx/Vivado/20xx.x/settings64.sh

Step 16: Type vivado >> Enter
