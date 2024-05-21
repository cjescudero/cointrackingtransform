# cointrackingtransform
This script processes and transforms the historical gains and losses exported from Quantfury into a format compatible with CoinTracking. It reads all Excel files from a specified directory, cleans and converts the data, and organizes it according to CoinTracking’s requirements. The script ensures that all transactions are correctly categorized as either profits or losses, includes necessary metadata, and sorts the data chronologically. Finally, it outputs the transformed data into a new Excel file with a consolidated and properly formatted trade table.

## Usage

python Quantfury_to_CoinTracking_PnL.py

To use this script, place all the Quantfury history Excel files into a folder named “Hystorty from Quantfury”. The script will read all files in this folder, process and transform the data into a format compatible with CoinTracking, and then save the consolidated and sorted results into a single Excel file named “Quantfury_CoinTracking_data.xlsx”.
