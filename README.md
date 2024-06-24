# JMT-simulation
Java Modelling Tools (JMT) is a free open source suite consisting of six tools for performance evaluation, capacity planning, workload characterization, and modelling of computer and communication systems. 

#Objectives
This project involves using JMT (Java Modeling Tools) to analyze and optimize the operations of a hospital that operates 24/7. The analysis focuses on patient flow, discharge rates, and resource utilization within different triage units of the hospital.

#Key Analysis and Findings
In-patient Admissions:

Calculation: In-patients enter the hospital through the InP-Triage unit. With one server handling approximately 170,212 patients per week, it averages to a new patient every 2.5 minutes.
In-patient Discharges:

Calculation: The hospital discharges about 88,892 in-patients per week. The outflow differs from the inflow as 20% of patients are transferred to HcP-Triage, with an average weekly discharge rate of approximately 21,300 patients.
HCP Patient Hospital Stay:

Calculation: Using the throughput index, with a sample size of 29,803 and an average of 0.0498, each HCP patient spends an average of 5.98E5 minutes in the hospital.
NCP Patient Hospital Stay:

Calculation: Analyzing 25,600 samples with an average of 0.0583, each NCP patient spends approximately 439,108.06 minutes in the hospital.
Utilization of Triage Units:

InP Triage Utilization: 73% (max utilization)
ICUY Triage Utilization: 24% (max utilization)
Indices Used: Utilization ranges from 0 (idle) to 1 (max utilization).
NCP Patient Examination Wait Time:

Calculation: With an average waiting time of 53,900 minutes and 75,552 samples, each InP patient waits approximately 0.72 minutes to be examined.
NCP Patient Pre-tablet Wait Time:

Calculation: With 20 servers, the queue time is zero at the initial station but creates a bottleneck at the next station, averaging to a maximum queue time of 8 minutes during nurse history verification.
ICU Triage Waiting Patients:

Calculation: On average, 0.2990 minutes are spent per patient waiting in the ICU triage, ensuring efficient emergency handling with minimal queue time.
Conclusion
This project successfully applies JMT to simulate and analyze hospital operations, providing insights into patient flow, resource utilization, and efficiency improvements. The findings highlight areas for potential optimization, ensuring effective management of hospital resources and improved patient care.
