# Energy-consumption
Measure of energy consumption 
MEASURE OF ENERGY CONSUMPTION
INTRODUCTION:	
            Today electrical energy is the basic need of human beings .It is the prime mover of the many of the electrical components. The future is based on the electricity so we need to save it, because they will not available for long days. “ENERGY CONSUMPTION INDICATOR” mainly aims at households to bring their electricity bill down with the help of the energy consumption alert system and also alert for power factor, as well as frequency. Energy meters being deployed at homes and industries are used for reading the power, i.e. energy being consumed.
 APPLICATION:
➡ Economic Savings: Monitoring energy consumption in households allows us to identify which appliances and devices consume the most energy in our homes. By knowing this information, we can use them more efficiently and reduce our electricity consumption, which translates into long-term economic savings. Additionally, we can identify possible energy leaks and solve them in time, avoiding unnecessary expenses on the electricity bill.
➡ Reduction of Carbon Footprint: Energy consumption is one of the main emitters of greenhouse gases, which are the main culprits of climate change. By reducing our electricity consumption, we are reducing our carbon footprint and contributing to the fight against climate change.
➡More Responsible Use of Natural Resources: Electricity is generated from natural resources such as oil, natural gas, and coal. These resources are limited, and their extraction and processing have a negative impact on the environment. By monitoring and reducing our electricity consumption, we are making the resources safe.


 

PROJECT OVERVIEW:
        Of the total consumption for 2022, 44% was used in transport, 29% in industry (including non-energy uses), and 20% in the residential, services, and agriculture sector. The remainder is consumed in power plants (1%) and in the hydrocarbon industry (6%)..
 PYTHON LIBRARIPSUTILES REQUIRED:



CODING:
import  psutil
def measure_energy_consumption():
     energy_before = psutil.sensors_battery().percent
    # Perform the task or operation for which you want to measure energy  consumption
    # ...
    # ...
    energy_after = psutil.sensors_battery().percent
    energy_consumed = energy_before - energy_after
    return energy_consumed

# Example usage
consumed_energy = measure_energy_consumption()
print(f"Energy consumed: {consumed_energy}%")


ADVANTAGES:
Energy savings.
Energy security.
Energy prices.
Energy access.
Health and wellbeing.
Air Quality.
Emissions savings.
Household savings.

DISADVANTAGES:
        The environmental problems directly related to energy production and consumption       include air pollution, climate change, water pollution, thermal pollution, and solid waste disposal. The emission of air pollutants from fossil fuel combustion is the major cause of urban air pollution.
