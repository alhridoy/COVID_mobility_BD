# COVID_mobility_BD


Google mobility data to assess the effectiveness of NPis undertaken by Government of Bangladesh.
![Bangladesh_mobility](https://user-images.githubusercontent.com/25701826/132393977-87ad5bbc-68dc-4570-ad97-eb977a2fb19e.png)

Remarks: Nation-wide lockdown in 2020 worked on reducing human mobility in Bangladesh. However,Lockdown in 2021 did not work well!

Correlation between COVID-19 cases and mobility 

Since incubation period of COVID-19 is 14 days mobiility data has been lagged by 14 days to asses the correlation 


<img width="800" alt="corr" src="https://user-images.githubusercontent.com/25701826/132397876-b183c7d4-7c68-41a6-bdf4-79f0085399e5.png">
 


Reamarks: 
Only grocery and pharmacy and parks mobility weekly correlated with covid cases


Prediction effective reproduction number using mobility: A machine learning method

Methods: 

1.Linear regression,Support vector machine(regression), Random forest and Artificial neural network has been  used to forecast effective reproduction number(Rt)  in Bangladesh using mobility data.

2.Rt was estimated by EpiEstim pakages of R software 
3.Rt values was lagged by 14 days siince known incubation period of COVID-19 is 7-14 days 
4.ANN outperformed others algorithms
5.3 layers of ANNs have been used with 150,150 and 60 nodes.

#Prediction with ANN 


<img width="727" alt="ANN" src="https://user-images.githubusercontent.com/25701826/132464391-b3979b55-faa4-4053-85cc-b0186820d36b.png">



RMSE of machine learning algorithms

<img width="635" alt="RMSE" src="https://user-images.githubusercontent.com/25701826/132465468-44ec83ba-d0b4-4ad6-bcf4-1aebef336ef3.png">

