# CMM_Dashboards
Code to combine and plot CMM data for calibration cubes

# Plotting of CMM data

To use this make sure you have jupyter notebook installed. 

Save CMM data folder in CM_Data folder 
  - Make sure files look like "CMM *job* *Machine* *ddmmyyyy*" seperated by space (e.g. CMM PT9979 KOM19 24052024)

Do not touch the openjob folder 

Open "Run_CMM_Dashboard.ipynb" with jupyter

If you have not used this script before change the statement "First_time = True"
Change it back to "False" after you run it once to not install the packages everytime

Run the whole script by clicking "Kernel" and "Restart & Run all"
The script should now launch a "Heatmaps" and a "Capabilities" plot and produce an excel file with all results
The files can be found in the "Data" folder

Further questions: contact camilla.clement.borre@lego.com 

