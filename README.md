# Cisco SNTC DataMiner
This is a sample python script that will extract all the SNTC data for all customers within a single partner. 
It will gather the JSON data and convert it to CSV files for injecting into any platform that can digest a CSV file.

To utilize this script follow the below steps:
1. Have your Cisco Services API Keys handy.
2. Ensure Python 3.10 or higher is installed and working properly
3. Download this script into a directoy of its own.
4. Execute the script to create a config.ini file in the same directory the script was run from
5. Edit the config.ini file and enter your Services API keys and make any changes you want as noted in the config.ini file
6. Execute the script again to start the data mining process
