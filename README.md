# ECO475 Thesis
 Code, Data, and Writeups for my capstone econometrics research project

Description copied and abridged from full paper. Full paper [here](Writeups/ECO475_Paper-1.pdf). The paper was written in Winter 2022/Spring 2023

 ## Introduction
Transportation is one of the largest sources of greenhouse gas emissions, accounting for 27% of
greenhouse gas emissions in the US in 2020. Out of all transportation emissions, 57% is
attributable to light-duty vehicles.1 Other pollutants from Internal Combustion Engines such as
Particulate Matter, Nitrogen Oxides, and Carbon Monoxide are linked to adverse health outcomes
such as asthma, reduced lung function, and cardiac and pulmonary mortality. Thus the
electrification of transportation, particularly personal electric vehicles (EVs), can
reduce carbon emissions and improve population health outcomes. However, despite sales doubling
from 2020, EVs only made up 10% of global new vehicle sales in 2021. While EV sales have a
strong upward trend, it is still in the early stages of widespread adoption by the general public.
Given the numerous positive externalities of EV adoption, many national governments have
implemented incentive programs ranging from individual purchase subsidies to large spending
packages for battery and charging infrastructure. Additionally, factors affecting consumer
adoption of EVs are a subject of ongoing study. This paper will focus on estimating the effect of
political partisanship on EV adoption in the US using panel data while controlling for other factors
explored in the literature.

## Data
The primary dataset utilized for this paper is a monthly county-level panel of vehicle populations
published by the State of Washington Department of Licensing. The dataset is grouped by vehicle
class (passenger versus truck) and drivetrain (battery-electric, hybrid-electric, and non-electric),
and covers the time from January 2017 to December 2022.
Other variables include county-level demographic data (population, education, income, and
poverty) published by the Economic Research Service of the US Department of Agriculture,
monthly fuel (gasoline) price data published by the US Energy Information Administration, and
county-level fueling/charging station numbers published by the Alternative Fuels Data Center of
the US Department of Energy. Most importantly, county partisanship is measured by election
returns in the 2016 and 2020 federal elections published by the MIT Election Data Lab. State-level
governor and legislature partisanship data for regression controls are published by the National Governors Association
and Ballotpedia respectively.
