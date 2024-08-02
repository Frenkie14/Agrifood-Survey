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
            <th rowspan="15">Agrifood classification</th>
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
        <tr>
            <td>[108]</td>
            <td>2022</td>
            <td>Landsat 8, Sentinel-2, Onsite devices</td>
            <td>KNN, RF, SVM, GBDT</td>
            <td>Landsat 8: KNN: Recall: 0.83, Precision: 0.84, F1-score: 0.83; RF: Recall: 0.90, Precision: 0.92, F1-score: 0.91; SVM: Recall: 0.69, Precision: 0.75, F1-score: 0.71;
              Gradient Boosting: Recall: 0.91, Precision: 0.91, F1-score: 0.91; Sentinel-2: KNN: Recall: 0.96, Precision: 0.96, F1-score: 0.96; RF: Recall: 0.92, Precision: 0.98, F1-score: 0.94;
              SVM: Recall: 0.93, Precision: 0.71, F1-score: 0.75; GBDT: Recall: 0.87, Precision: 0.89, F1-score: 0.87</td>
            <td>IEEE Access</td>
        </tr>
        <tr>
            <td>[95]</td>
            <td>2021</td>
            <td>Zhuhai-1, Sentinel-2, Sentinel-1</td>
            <td>DOCC</td>
            <td>F1-score_Winter wheat: zhuhai-1: 87.37, Sentinel-2: 92.84, Sentinel-1: 88.72; F1-score_Rapeseed: zhuhai-1: 87.66, Sentinel-2: 77.2, Sentinel-1: 90.3</td>
            <td>International Journal of Applied Earth Observations and Geoinformation</td>
        </tr>
        <tr>
            <td>[235]</td>
            <td>2019</td>
            <td>Sentinel-1</td>
            <td>1D CNNs, LSTM RNNs, GRU RNNs, RF</td>
            <td>1D CNNs: Kappa: 0.942, OA: 0.959; LSTM RNNs: Kappa: 0.931, OA: 0.951; GRU RNNs: Kappa: 0.934, OA: 0.954; RF: Kappa: 0.937, OA: 0.954</td>
            <td>Remote sensing</td>
        </tr>
        <tr>
            <td>[200]</td>
            <td>2019</td>
            <td>Sentinel-2</td>
            <td>Polynomial-SVM, RBF-SVM, RF, ANN, CART-DT</td>
            <td>Polynomial-SVM: OA: 95.20%, Kappa: 0.8870; RBF-SVM: OA: 94.60%, Kappa: 0.8732; RF: OA: 91.30%, Kappa: 0.8011; ANN: OA: 77.55%, Kappa: 0.5757; CART-DT: OA: 91.10%, Kappa: 0.7919</td>
            <td>Land Use Policy</td>
        </tr>
        <tr>
            <td>[210]</td>
            <td>2020</td>
            <td>Landsat Analysis Ready Data</td>
            <td>DeepCropMapping (DCM), Transformer, MLP, RF</td>
            <td>DCM: Kappa: 86.5%; Transformer: Kappa: 86.0%; MLP: Kappa: 85.6%; RF: Kappa: 85.8%</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>[68]</td>
            <td>2021</td>
            <td>UAV</td>
            <td>DeeplabV3+, PSPNet, SegNet, U-Net</td>
            <td>DeeplabV3+: mIoU: 94.36, mPA: 96.09; PSPNet: mIoU: 91.18, mPA: 94.41; SegNet: mIoU: 93.92, mPA: 96.08; U-Net: mIoU: 94.73, mPA: 96.54</td>
            <td>Journal of Spectroscopy</td>
        </tr>
        <tr>
            <td>[153]</td>
            <td>2022</td>
            <td>UAV</td>
            <td>ViT B-16, ViT B-32, EfficientNet B0, EfficientNet B1, ResNet 50</td>
            <td>ViT B-16: µF1-score: 0.994, µLoss: 0.656; ViT B-32: µF1-score: 0.992, µLoss: 0.672; EfficientNet B0: µF1-score: 0.987, µLoss: 0.735; EfficientNet B1: µF1-score: 0.989, µLoss: 0.720;
              ResNet 50: µF1-score: 0.992, µLoss: 0.716</td>
            <td>Remote sensing</td>
        </tr>
        <tr>
            <td>[135]</td>
            <td>2022</td>
            <td>UAV</td>
            <td>HSI-transunet, SegNet, SETR, UNet, TransUNet</td>
            <td>HSI-transunet: OA: 86.05%, Kappa: 0.8347; SegNet: OA: 43.61%, Kappa: 0.5415; SETR: OA: 69.47%, Kappa: 0.7267; UNet: OA: 76.07%, Kappa: 0.7131; TransUNet: OA: 78.64%, Kappa: 0.7456</td>
            <td>Computers and Electronics in Agriculture </td>
        </tr>
    </tbody>
</table>
