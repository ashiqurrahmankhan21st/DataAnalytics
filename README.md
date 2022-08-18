# DataAnalytics
# IPE 6107, Data Analytics, Project

Data Set Name: A RMG Factory Downtime Data Set of Single Piece Flow Production Lines (Two Data Sets will be Used

Dimension: 3952 * 8

Features: Date, Line_No, Responsible_Department, Problem_Name, M/C_ID, Problem_Start_Time, Problem_End_Time, Total_Downtime (Min)

Descriptions: 

There are multiple reasons for downtime. There are solid definations of
"Downtime" and "Loss time", that is not our focus. This DataSet contains M/C Break Downs time, Needle Breakdown Time, etc & Resposible Department and Reason behind the Downtime.

Date                      datetime64[ns]
Line_No                           object
Responsible_Department            object
Problem_Name                      object
M/C_ID                            object
Problem_Start_Time        datetime64[ns]
Problem_End_Time          datetime64[ns]
Total_Downtime (Min)             float64
dtype: object


Possible Findings will be:

1) Reason that causes maximum downtime (or increasing WIP of a work station)
2) What is reason that is responsible for most of the breakdown time of a day
3) At which portion of the Working Hour breakdown happens most
4) At which portin of the week/month breakdown causes most
5) Machines that coause maximum Breakdowns; that can be replaced or take some preventive measures to reduce Downtime

Note: Other findings may be added in future

 Ⓒ This DataSet is useable for this Project only. No farther use.
