<div align="center">

<h1>Empowering Agrifood System with Artificial Intelligence: A Survey of the Progress, Challenges and Opportunities</h1>


Tao Chen<sup>1 </sup>, Liang Lv<sup>1 </sup>, Di Wang<sup>2 </sup>, Jing Zhang<sup>3 ∗</sup>, Yue Yang<sup>1 </sup>, Zeyang Zhao<sup>1 </sup>, Chen Wang<sup>1 </sup>, Xiaowei Guo<sup>1 </sup>, Hao Chen<sup>1 </sup>, Qingye Wang<sup>1 </sup>, Yufei Xu<sup>3 </sup>, Qiming Zhang<sup>3 </sup>, Bo Du<sup>2 </sup>, Liangpei Zhang<sup>2 </sup>, Dacheng Tao<sup>3 </sup>

<sup>1</sup> China University of Geosciences, <sup>2</sup> Wuhan University,  <sup>3</sup> The University of Sydney.

<sup>∗</sup> Corresponding author

</div>

<p align="center">
  <a href="#architectures">Architectures</a> |
  <a href="#opportunities">Opportunities</a>
</p >


<figure>
<div align="center">
<img src=agri_ar_text_shopping.png width="100%">
</div>
<figcaption align = "center"><b>Fig.-AI models enable reading agrifood product information. The results are obtained by <a href="https://github.com/ViTAE-Transformer/DeepSolo">DeepSolo</a> with <a href="https://github.com/ViTAE-Transformer/ViTAE-Transformer">ViTAEv2</a>. </b></figcaption>
</figure>

## Architectures

[Data Source, Storage and Preprocessing](https://Frenkie14.github.io/Agrifood-survey-mindmap/mindmap_dataset.html)

[Applications for Data and Method Selection](https://Frenkie14.github.io/Agrifood-survey-mindmap/mindmap_application.html)


<table>
    <thead>
        <tr>
            <th>Sub-direction</th>
            <th>Citeration</th>
            <th>Year</th>
            <th>Input</th>
            <th>Methods</th>
            <th>Accuracy Indicators</th>
            <th>Pub.</th>
        </tr>
    </thead>
    <tbody align='center'>        
        <tr>
            <th rowspan="7">Agrifood classification</th>
            <td>[142]</td>
            <td>2014</td>
            <td>ASTER</td>
            <td>SVM+SVM</td>
            <td>Correct Classification Rate (CCR) : 89%; Overall Sensitivity: 82%; Overall User Accuracy: 86%; Averaged Sensitivity of woody crops: 79%; Averaged User’s Accuracy of woody crops: 81%;
              Averaged Sensitivity of herbaceous crops: 84%; Averaged User’s Accuracy of herbaceous crops: 88%</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>[226]</td>
            <td>2017</td>
            <td>MODIS, Landsat TM, Landsat ETM+</td>
            <td>Improved algorithm to identify flooding and transplanting of paddy rice fields</td>
            <td>R^2：0.25</td>
            <td>Science of the Total Environment</td>
        </tr> 
        <tr>
            <td>[130]</td>
            <td>2014</td>
            <td>Hyperion sensor</td>
            <td>Extreme learning machines(ELM), Optimally pruned ELM(OP-ELM), BayesNet, SVM, 1-NN, C4.5</td>
            <td>ELM(70 bands): OA: 0.882432, MAE: 0.117568, Kappa: 0.830018; OP-ELM(25 bands): OA: 0.832, MAE: 0.167, Kappa: 0.762; BayesNet(25 bands): OA: 0.636, MAE: 0.192, Kappa: 0.484;
              SVM(25 bands): OA: 0.675, MAE: 0.259, Kappa: 0.547; 1-NN(25 bands): OA: 0.679, MAE: 0.128, Kappa: 0.555; C4.5(25 bands): OA: 0.506, MAE: 0.314, Kappa: 0.026</td>
            <td>Neurocomputing</td>
        </tr> 
        <tr>
            <td>[92]</td>
            <td>2017</td>
            <td>Landsat 8, Sentinel-1</td>
            <td>MLP, ENN, 1D-CNNs, 2D-CNNs</td>
            <td>MLP: OA: 88.7%; ENN: OA: 92.7%; 1D-CNNs: OA: 93.5%; 2D-CNNs: OA: 94.6%</td>
            <td>IEEE Geoscience And Remote Sensing Letters</td>
        </tr> 
        <tr>
            <td>[5]</td>
            <td>2018</td>
            <td>Onsite devices, University of Manchester (UoM) system, University of Bonn system, AVIRIS sensor</td>
            <td>ND-SVM, RoSVM, RF</td>
            <td>average accuracy： ND-SVM (all wavelengths): 85.62%; ND-SVM (CFS feature selection): 56.86%; ND-SVM (feature ensemble): 91.70%; RoSVM: 88.84%; RF: 88.07%</td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>[189]</td>
            <td>2018</td>
            <td>Sentinel-1, Sentinel-2</td>
            <td>Hierarach RF</td>
            <td>OA: 82%, Kappa: 0.77</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>[101]</td>
            <td>2020</td>
            <td>Onsite devices, RADARSAT-2, VENµS</td>
            <td>Conv1D, MLP, LSTM, XGBoost, RF, SVM</td>
            <td>Conv1D: OA: 96.72%, Kappa: 0.95; MLP: OA: 96.14%, Kappa: 0.94; LSTM: OA: 93.65%, Kappa: 0.90; XGBoost: OA: 95.45%, Kappa: 0.93; RF: OA: 95.92%, Kappa: 0.94;
              SVM: OA: 96.06%, Kappa: 0.94</td>
            <td>Remote Sensing</td>
        </tr>
    </tbody>
</table>
