# Modelling the Ebola Virus Epidemic Based on Agent-based Model
## Description
This is an agent-based model of the epidemic infectious progression of Ebola virus disease. It can be used to explore the role of the human remains in the Ebola infectious progression, and how significant the presence of human remains influences the infectious progression under different environmental conditions.
## Parameter Settings
A number of parameters help shape the progress of the disease in this model:
**Initial infected rate:** Initial probability of being infected. Equals to the I0 in the equation, giving the model a group of initial infectious human individuals for furthersimulation.
**Transmission probability:** The transmission probability is the probability that, given a contact between infectious human individuals and a susceptible human individual,successful transfer of the infectious agent will occur so that the susceptible individuals get infected(Halloran). Equals to the β1 and β2 in the mathematical equations, the β1 and β2 have the same value in this research.
**Population:** The total population within the containers.
**Death rate:** The probability of dying after being infected by Ebola. Equals μ in the mathematical equations. Here it is the death rate for an agent in one day, as the agents
will choose to die or recover from after the recovery days. As this research is not focused on a specific type of Ebola virus, the final death rate is selected to be in the range from 25% to 90% (on average around 50%), as reported by Who Ebola virus disease report (Who, 2021). The daily death rate is for an agent in one day. However, as the agents will choose to die or recover from after the recovery days (7 days), the final death rate should equal:
**Progression period mean:** Incubation period. The average number of days wheninfected individuals begin to have symptoms means they could infect other susceptible
individuals from then on.
**Progression period standard:** Standard deviation of progression period.
**Recover days mean:** Average number of days until recovery.
**Recover days standard:** Standard deviation of recovery days.
**Eliminated days mean:** Average number of days when the dead people will be buried,
which means they are eliminated from the infection simulation.
**Eliminated days standard:** Standard deviation of eliminated days.

