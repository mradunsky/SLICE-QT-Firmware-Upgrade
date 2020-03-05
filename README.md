# SLICE-QTC-Firmware-Upgrade
Repository for the latest released firmware for the SLICE-QTC

## Requires 
  Vescent SLICE-PC-GUI application available at:
  
  https://github.com/Vescent/SLICE-PC-GUI/blob/master/SLICE-GUI-Windows-1-17.zip
## Instructions
  __NOTE: Upgrading from Version S1.24_QTC1.38 will erase all device settings an parameters. Record them externally prior to updating firmware!__
  
  Left click on SLICE_firmware_update.docx and then click 'Download' to download the instructions for use.

  Left click on the upgrade package (SC-x-xx-QT-x-xx.zip) and then click 'Download' to download the firmware package to your hard drive.
  
  The two files in the .zip file need to be placed in the folder described in the instructions. DO NOT RENAME THEM!
## Configuration S1.174_QTC1.50
 1. Temperature Setpoint resolution is now 0.1 mK
 2. Fixes measured temperature corruption issue when using a non-zero Steinhart-Hart C coefficient.
 3. Fixes meter lockup when invalid Steinhart-Hart coefficients are entered
 4. Implements ***IDN?** Serial API command
   
       Returns:
    
       __Vescent Photonics, SLICE-`<model>`, `<serial number>`, `<System Controller FW Version>`, `<ICE2 FW Version>`__
       
  5. Allows exiting a rotary knob edit by touching outside of the active rotary edit box
  6. Fixes occasional -0.0 display on error readout
  7. Adds automatic shutdown with error summary when device maximum power is exceeded.
  8. Adds **Setpoint Relative** external input mode which allows adjustment of the base temperature setpoint from the main or channel summary screen
  
