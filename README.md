# Project Inception - Distributed System

To combat the pandemic of coronavirus Covid-19, experts in Public Health call for a virus tracking system to stop the spread of the virus in public areas.

The basic idea of the tracking system is to set all public in-door spaces as controlled areas. Typical examples of such areas are restaurants, pubs, shops, museums, schools, offices, cinemas, theatres, airports, waiting rooms of bus stations, public transportation vehicles (like buses, taxis, airplane, ferry boats, trains), etc. Every individual person enters such a space must be recorded of the period of time that the individual stayed in the area.

When a person is tested positive on Covid-19 virus, those individuals have stayed in a same controlled area within 2 days and had an overlap of the period more then 15 minutes1 should be informed to self-isolate for 14 days2 and recommended to take a Covid-19 test. Those required to self-isolate are not allowed to enter any controlled area before the completion of self-isolation or be tested negative on Covid-19.

A computer application is to be developed to operate such a tracking system effectively. The basic ideas of the computer application are summarised as follows.

(1) Each individual will be issued a so-called “Crownpass” that contains
• a photo of the pass holder, and
• a 2D bar code as the pass holder’s digital identifier.

The Crownpass should be easy to obtain through a website in a process similar to online self check-in to a flight.
(2) The system will store a covid-19 infection state of the pass holder, which can be in one of the following three different states:
• Green: No Covid-19 infection;
• Amber: Suspected to be infected by Covid-19;
• Red: Confirmed infection by Covid-19.

Each individual must have no more than one valid Crownpass state at any time.

(3) An owner of a controlled area should be able to easily install a mobile APP to scan the 2D bar code of Crownpass when a person enters the area and leaves the
area. The APP should be able to tell if the state of a pass holder is in the Green state, and only allows the Green pass holders to enter the area. The data about
when and who enters and leaves an area must be sent to the central computer system running on the Cloud.

(4) A controlled area must also have a set capacity for the number of persons allowed to be in the area at the same time. The APP should be able for the area owner to set the capacity and to control the number of persons in the area by keeping a record on how many persons in the area at any time and prevent overloading the
area.

(5) When a person is tested positive on Covid-19 virus, the Crownpass state of the person will become Red. Moreover, those in close contact in the controlled areas
within two days will be informed that they are required of self-isolation and their Crownpass state becomes Amber.

(6) When a person is tested negative on Covid-19, the Crownpass state of the person will be reset to be Green.

(7) The central computer system should provide the Disease Control Centres of local and central governments with data on the total number of confirmed cases of
Covid-19 infections in a geographic area, such as a city or a town, so that a regional lockdown decision can be made promptly based on accurate data. It should also enable the real time detection of specific controlled areas of high infection rates. In such a case, the controlled area should be informed to close for a set period of time and to disinfect the area before it can re-open.

(8) The police officers should be equipped with an APP installed on their mobile computing devices to enable issuing self-isolation orders to individuals who violets social distancing rules, which will change the Crownpass state to Amber. It will also enable the police officers to check the setting of controlled areas, such as the capability of the area.

