# FTIR_fittingtool_v2.63
The second generation of FTIR data fitting tool. 

The program uses the knowledge of thin film filters which studied the physics behind EM waves propagating inside an optical system. 
The influence on the EM wave by each layer is represented using an optical transfer matrix (characteristic matrix).  
For example: H.A. Macleod, Thin-Film Optical Filters(1969), chapter2. 


System requirement: 

Mac OS/ Windows / Linux (Not tested)

python 3.4 +

The following packages need to be installed before running the program: 

matplotlib, numpy, PyQtChart and mysqlclient. Install using pip is recommended.  
  
  
How to run it: 

Download the whole package to local, and then run "FTIR_fittingtool_2_class.py". 


For any questions, please contact pman3@uic.edu.


© 1, 2018 Peihong Man. 


Special Thanks: Dr. Yong Chang. 


Update log: 

v2.63.

Some minor changes to cooperate with the Toolbox. 
            
v2.62.

Optimized window arrangement. 

Optimized color handling for embed purpose. 

v2.61.

Fixed an issue where the program cannot be opened from cmd directly. 

Fixed an issue where it may raise an error message due to materials data overflow. 

v2.60.

This update is focused on performance and stability improvements. 

A lot of features are packed in v2.5. v2.6 will be more stable and with less bugs. 

v2.59.

Now one can calculate extinction coefficient k(k is not T-dependant.)

Extinction coefficient k of ZnSe, ZnS, Ge and BaF2 are adjusted based on real FTIR data. 

Added option to use ideal extinction coefficient k in "Settings". 

Added "input data type" option. "Settings" UI is optimized.

Added options for absorption axis scale. The scale automatically change when k is used instead.

"Angle" option is now moved to "settings". 

Optimized a few log output. Colored log output.

Optimized code for "cal_k" function. Now it will not show error message when lambda is out of range.

Fixed a few small bugs. 

Help file is updated to represent the current version. 
            
v2.58.

Added configurations to the configuration file. Now you have the option to remember all settings in "settings".

Added function to prevent click button during calculation. 

Added unicode characters for alpha. 

Customized color theme. 

v2.57:

Added wavenumber/wavelength/energy/composition calculator.

Optimized coding for faster calculation.

Added "Load background" warning for opening file from SQL.

v2.56:

Added "Abort mission" function. 

Added function to prevent user from clearing all data during calculation. 

v2.55:

Added interactive help for a lot of buttons and labels. 

Optimized UI for windows. 

Fixed two small bugs. 

Added GuessANumber. Click bottom left corner. 

v2.54:

Added "Open from SQL" function. (Ryan)

Added new Qt based dialog window to load from sql servers. (Ryan)

Simplified a chunk of initializing code for creating datastructures for reference files.(Ryan)
 
Added unicode characters for -1 and mu where appropriate. (Ryan)

Added "Blind calculation" in settings. Blind calculation runs faster. 

Added interactive help for buttons.

Added total time calculation to the logs. 

v2.53:

Added live graph for "Show Trans" function. 

Added live graph for "Fit Trans" function. 

Added live graph for "Cal a" function. 

v2.52:

Now the program can fit the cutoff curve. See help file for details. 

Now the MCT absorption calculation function is T-dependent. 

Optimized UI buttons. 

Added new layer structure: VLWIR SL.

v2.51:

Added T-dependent refractive index for ZnSe, BaF2 and Ge.

Now one can calculate absorption coefficient for multiple absorption layers. 

Optimized UI for Windows.

Fixed a bug where the default preload structure cannot be loaded.

v2.50:

Temperature is introduced into the fitting tool. Added temperature in "settings".

Added material data fro Si3N4, air. 

Added one more substrate option: Air. 

Extended the total number of layers can be added from 16 to 22. 

Modified "Clear" function. 

Modified "Calculate absorption" function. 

Modified "Calculate MCT absorption" function. 

Added function to prevent two structures stack together. 

Toolbar buttons are optimized to fit in more function buttons. 

Now the newest added layer will shw on top instead of bottom. 
    
v2.40:

Added material data for ZnSe, BaF2, Ge and ZnS for FPI project.

Added settings function.

Added saveresult function.


