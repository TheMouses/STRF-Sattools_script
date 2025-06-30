# STRF-Sattools_script
.sh files so you can easily switch between the environments for STRF and SatTools. These files will set the proper environment variables for each toolkit.

1. Doanlowd both .sh files and place them in the home folder

# 2. Make executable
chmod +x ~/sattools-env.sh
chmod +x ~/strf-env.sh

# 3 Edit .bashrc file in home folder 

At the bottom of the file paste 
  #STRF-Sattools_script
source ~/strf-env.sh
  
source ~/sattools-env.sh

# 4 run 
 source ~/.bashrc


# To switch between enviorments run strfenv or satenv
run strfenv or satenv
