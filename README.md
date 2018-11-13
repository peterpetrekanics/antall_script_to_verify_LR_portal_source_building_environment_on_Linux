# antall_script_to_verify_LR_portal_source_building_environment_on_Linux

# This linux specific bash script helps users in building Liferay Portal source code
# 
# The script works only with: Liferay on a Tomcat bundle; with the Ant build tool; with a MySQL database
#
# The script can:
# - check tomcat version 
# - the folder where the source will be built to
# - the current contents of the destination folder
# - check the current git repository 
# - check the current liferay version
# - check the gradle.properties file settings
# - display a desktop notification once the build process has finished
# 
# The script must be executed from the Liferay Portal git repository's local folder
# Tested on: Ubuntu 16.04 on 13 Nov 2018