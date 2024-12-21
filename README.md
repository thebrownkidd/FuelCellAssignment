# FuelCellAssignment

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
    
