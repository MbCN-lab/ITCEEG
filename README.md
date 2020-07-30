# ITCEEG

This repository is for "Frontoparietal dynamics and value accumulation in intertemporal choice" (Liu et at., submitted). The following describes what the directories indicate.

## ERP
ERP data for each subject. 

## ISPC
ISPC data for each subject and condition. Condition is for experimental choice probability (P<sub>D</sub>). Due to the restrictions, the files were uploaded into two seperate directories. Cond1 corresponds to 0.1 P<sub>D</sub>, Cond2 corresponds to 0.3 P<sub>D</sub>, and so on.

## Behavior
choice-RT data for each subject. Each column represents the following information.

| Column | Description                                                                                   |
|--------|-----------------------------------------------------------------------------------------------|
| subj   | subject ID                                                                                    |
| rt     | response time (unit: millisecond)                                                             |
| resp   | choice response. 0 coded as smaller sooner (SS) option and 1 coded as larger later (LL).      |
| cond   | experimental P<sub>d</sub>. For instance, 0.1 is for choosing LL option with 10% probability. |
| r1     | monetary reward for SS option                                                                 |
| r2     | monetary reward for LL option                                                                 |
| t1     | time delay for SS option                                                                      |
| t2     | time delay for LL option                                                                      |
