## Cooperative Manipulation of an Unknown Payload with Concurrent Mass and Drag Force Estimation


This is the matlab/simulink code for 2019 CDC paper below

## Cite the paper as: 

## LaTEX
@article{thapa2019cooperative,
  title={Cooperative Manipulation of an Unknown Payload with Concurrent Mass and Drag Force Estimation},
  author={Thapa, Sandesh and Self, Ryan V and Kamalapurkar, Rushikesh and Bai, He},
  journal={IEEE Control Systems Letters},
  year={2019},
  publisher={IEEE}
}

## APA
Thapa, S., Self, R. V., Kamalapurkar, R., & Bai, H. (2019). 
Cooperative Manipulation of an Unknown Payload With Concurrent Mass and Drag Force Estimation. 
IEEE Control Systems Letters, 3(4), 907-912.


## Running the code 
Please run the following code. 


### Requirements
- MATLAB/Simulink 2020 a 
```
mkdir LCSS_2019
cd ~/LCSS_2019
mkdir Plots_LCSS 
cd ..
git clone git@github.com:sandeshthapa/LCSS_2019_Concurrent_Learning.git
Run_force_Att_Controller.m 
```
   Please follow the instructions inside the script and run each sub-script once. 

## Results 

### Simulation Cases

#### Go to Force_Att_Controller_Separated.slx
#### Load -subsystem in simulink 
#### Inside "PayloadForceController" block 
#### change the cases to Constant  and Time varying velocities (Case are provded but commented out)


### Constant Velocity 


#### Linear Velocity 
![](https://github.com/sandeshthapa/LCSS_2019_Concurrent_Learning/blob/main/Plots_LCSS/VelLoadBCaseA.png)

#### Drag forces Estimation 
![](https://github.com/sandeshthapa/LCSS_2019_Concurrent_Learning/blob/main/Plots_LCSS/ThetacTildeBCaseA.png)

#### Contact force acting on the payload 
![](https://github.com/sandeshthapa/LCSS_2019_Concurrent_Learning/blob/main/Plots_LCSS/f1dTildeBCaseA.png)




### Time Varying Velocity 


#### Linear Velocity 
![](https://github.com/sandeshthapa/LCSS_2019_Concurrent_Learning/blob/main/Plots_LCSS/VelLoadB.png)

#### Drag forces Estimation 
![](https://github.com/sandeshthapa/LCSS_2019_Concurrent_Learning/blob/main/Plots_LCSS/ThetacTildeB.png)

#### Contact force acting on the payload 
![](https://github.com/sandeshthapa/LCSS_2019_Concurrent_Learning/blob/main/Plots_LCSS/f1dTildeB.png)



### Contact
thapasandesh1@gmail.com

