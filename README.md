# NEXUS
**FOR THE PYTHON CODE**
Open Terminal or Command Prompt:

On Windows: Press Win + R, type cmd, and press Enter.
On macOS: Press Cmd + Space, type Terminal, and press Enter.
On Linux: Open your preferred terminal application.
Navigate to the Directory: Use the cd command to navigate to the directory containing the generate_payment_slips.py file.

Copy the code below
cd path/to/your/directory
Install pandas (optional): If you want the script to save the payment slips to a CSV file, install the pandas package using pip.

Copy the code below
pip install pandas
Run the Python Script: Execute the script by typing the following command in the terminal:

Copy the code below
python generate_payment_slips.py
View the Output:

The script will print payment slip details in the terminal.
If pandas is installed, a file named payment_slips.csv will be created in the same directory.



**FOR THE R CODE**
Open R or RStudio:

If using RStudio, open the application.
If using R, open your terminal and type R to start the R session.
Set Working Directory: Set the working directory to the folder containing your R script.

Copy the code below:
setwd("path/to/your/directory")
Install jsonlite: If you haven’t already, install the jsonlite package which is required by the VSCode R extension.


Copy the code below:
install.packages("jsonlite")
Run the R Script: Source the script using the source command:


Copy the code below:
source("generate_payment_slips.R")
View the Output:

Payment slip details will be printed in the R console.
A CSV file named payment_slips.csv will be saved in the working directory.
