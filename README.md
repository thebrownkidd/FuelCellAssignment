# FuelCellAssignment

This problem had a very weak correlation between the target and features and thus was very difficult to model. It is highly likely that this dataset was generated using the random module
The correlation score of F0 with Target is: -0.050695505296193225

The correlation score of F1 with Target is: 0.004134735605715825

The correlation score of F2 with Target is: 0.01369835332918546

The correlation score of F3 with Target is: -0.043393139384464374

The correlation score of F4 with Target is: -0.04140873629750461

The correlation score of F5 with Target is: 0.02994861095452157

The correlation score of F6 with Target is: -0.021208267537185074

The correlation score of F7 with Target is: 0.02396602983457102

The correlation score of F8 with Target is: -0.09155621835659718

The correlation score of F9 with Target is: 0.008111413165597409

The correlation score of F10 with Target is: -0.10340123822846961

The correlation score of F11 with Target is: 0.005355915839672036

The correlation score of F12 with Target is: 0.0010432739735408787

The correlation score of F13 with Target is: -0.005606167859236927

The correlation score of F14 with Target is: -0.002231487767003861


Note that the target is target4 as per the assignment

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Model</th>
      <th>MSE Error</th>
      <th>MAE Error</th>
      <th>Accuracy</th>
      <th>R2 Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>ArpitSModel</td>
      <td>0.000424</td>
      <td>0.015987</td>
      <td>0.457182</td>
      <td>0.983652</td>
    </tr>
  </tbody>
</table>
</div>
<break>
This Was achieved during a lab assessment conducted here: https://github.com/psrana/Lab-and-Assignment-2024
The following was the Test result, Red = Predicted, Blue = True Value

![image](https://github.com/user-attachments/assets/9e483279-fc5c-4a48-9a3b-adafabe79223)


<break>

This was achieved using the folllowing model architecture:


  
    (0): Linear(in_features=15, out_features=10, bias=True)
    
    (1): LeakyReLU(negative_slope=0.01, inplace=True)
    
    (2): Linear(in_features=10, out_features=8, bias=True)
    
    (3): LeakyReLU(negative_slope=0.01, inplace=True)
    
    (4): Linear(in_features=8, out_features=3, bias=True)
    
    (5): LeakyReLU(negative_slope=0.01, inplace=True)
    
    (6): Linear(in_features=3, out_features=2, bias=True)
    
    (7): LeakyReLU(negative_slope=0.01, inplace=True)
    
    (8): Linear(in_features=2, out_features=1, bias=True)
    
    (9): Sigmoid()
    
