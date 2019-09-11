# Corrosion-AutoClave-Testing
Calculate MPYs and Standard Deviation in coupons installed in AutoClave. 

An autoclave is pressure chamber used to carry out industrial and scientific processes requiring elevated temperature and pressure different from ambient air pressure. Autoclaves are used in medical applications for sterilization and in the chemical industry for coatings and vulcanization. An autoclave is usually cylindircal but it can be any shape and size.

# AutoClaves in oil and gas industry

In oil and gas production, it is common to find water along with the produced fluids. The water produced has a high concentration of salt. This is called a brine. This brine induces severe corrosion to metal equipment used to extract oil and gas. In addition to the brine, there is also the presence of corrosive gases. The most common being hydrogen sulfide, and carbon dioxide. 
Corrosion inhibitors as well as Scale inhibitors are some of the chemicals oil companies use in order to slow down the corrosion rate of equipment. I order to select the appropriate chemical for the specific downhole/tubing conditions, experimental testing is required. Here is where AutoClaves come in to play. 

AutoClaves can simulate the temperature and pressures found downhole and in the tubing. This allows for an accurate approximation of “field conditions” to test the desired chemicals. 
This GUI focuses on the results after the test completions of three autoclaves.  GUI created using Tkinter and Python. 

# Here is the information that is needed for the data analysis:

CO2 pressure, RMP (speed the coupons will be rotating inside the autoclave), density of coupons, surface area of coupons.
Liters of Brine to pour in autoclaves, percent oil in autoclaves, products to be tested and ppm of products. 
Initial weight of coupons (before test), final weight of coupons (after test)

# Summary of test:

Before the test begins, coupons (small metal samples that are the same material as the tubing/metal used in the field) are weighted and placed inside the autoclave. All parameters are set and the autoclaves are sealed then the test starts. The test will run for a selected period of time. Once the test is done, the coupons are cleaned and re-weighted. 

# Equations used: 

RPM to linear velocity:	v = RMP * radius * 0.10472
Weight Loss = Initial Weight – Final Weight 
MPY (Mils penetration per year) = (22,300 * Weight Loss)/(density * area * time[days])
Population Standard Deviation (can be found by searching online)

# First Page
![alt text](https://github.com/cerdamario13/Corrosion-AutoClave-Testing/blob/master/AutoClave_FirstPage_Github.png)

# Second Page
![alt text](https://github.com/cerdamario13/Corrosion-AutoClave-Testing/blob/master/AutoClave_SecondPage_Github.png)

