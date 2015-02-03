heads_ide
============

Initial infrastructure for building the heads IDE bundle


Configure the Apama Studio inside the HEADS IDE for Windows
After installing Apama, the user has two environment variables: APAMA_HOME and APAMA_WORK. 
These are set with the Apama Command Prompt.
Example values are:
APAMA_HOME=C:\Program Files\SoftwareAG\Apama 5.1
APAMA_WORK=D:\Users\<your user id>\SoftwareAG\ApamaWork_5.1
Open <HEADS IDE folder>\plugins\com.apama.studio.install_<version>\resources\install.properties in a text editor. 
Replace the strings @APAMA_HOME@ and @DEFAULT_APAMA_WORK@ with the corresponding values.
Save the file and start HEADS IDE. The values from install.properties are read on every start of the HEADS IDE.
The values are shown on the preference page Apama --> MonitorScript Variables.
