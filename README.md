# Serdes Equalizer

Given a specified channel insertion loss, this spreadsheet calculates a precise first guess for the optimal filter coefficients for SerDes's continuous time linear equalizer (CTLE) and feedforward equalizer (FFE). The SI designer or the lab engineer can start preset sweep around the values obtained from this calculator.


**User Guide**

1- Input the S21 parameter of the channel vs Frequency in columns: AS, AU, and AV			

![image](https://github.com/user-attachments/assets/2b3c4176-50f7-4619-b259-69c06553b9c6)

2- Enter the bitrate in cell: B7			

![image](https://github.com/user-attachments/assets/3f41821f-66f0-4316-935e-e1a56e3f7bbc)

3- Input FFE FSR and Tap Settings, CTLE Transfer function, and VGA gain.					

![image](https://github.com/user-attachments/assets/943fa043-4547-438c-9817-9656afd4f507)


4- Observe the charts:
- First 3 charts shows the FFE, CTLE, and VGA frequency responses
- Chart 4 shows the channel and equalized channel
- Chart 5 and 6 shows the input and output pulse spectrum and waveforms
    
![image](https://github.com/user-attachments/assets/4995d3a8-215e-4d2c-b8bd-437c137c8764)



