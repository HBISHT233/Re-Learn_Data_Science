# Install the Anaconda
Open the link https://www.anaconda.com/download/success and choose the Anaconda for various operating system
Install it like any other software that you may have
![Install the Anaconda]("Re-Learn_Data_Science\Images\Screenshot (150).png")

# Setting up environment
For easy setup i have attached the config file for anaconda (data.yml). The configuration file includes all the necessary 
libraries which you will need in learning Data science
## Step-1
Search for Anaconda prompt in your Start menu and open it up
![Step-1]("Re-Learn_Data_Science\Images\Screenshot (151).png")

## Step-2
navigate to the directory where you have download the (data.yml) configuration file

## step-3
Run the command
'''bash
conda env create -f data.yml

This will start installing all the necessary libraries for you environment setup
![Step-3]("Re-Learn_Data_Science\Images\Screenshot (152).png")
![Step-3]("Re-Learn_Data_Science\Images\Screenshot (153).png")

# Run environment
'''bash
conda activate data
To activate the environment

'''bash
conda deactivate
To deactivate your environment
![Run environment]("D:\my_github\Re-Learn_Data_Science\Images\Screenshot (155).png")