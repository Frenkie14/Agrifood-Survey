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

Agrifood Classification
<table>
    <thead>
        <tr>
            <th>Year</th>
            <th>Input</th>
            <th>Methods</th>
            <th>Paper Title</th>
            <th>Pub.</th>
        </tr>
    </thead>
    <tbody align='center'>        
        <tr>
            <td>2014</td>
            <td>ASTER</td>
            <td>SVM+SVM</td>
            <td><a href="https://doi.org/10.3390/rs6065019">Object-based image classification of summer crops with machine learning methods</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>MODIS, Landsat TM, Landsat ETM+</td>
            <td>Improved algorithm to identify flooding and transplanting of paddy rice fields</td>
            <td><a href="https://doi.org/10.1016/j.scitotenv.2016.10.223">Spatiotemporal patterns of paddy rice croplands in China and India from 2000 to 2015</td>
            <td>Science of the Total Environment</td>
        </tr> 
        <tr>
            <td>2014</td>
            <td>Hyperion sensor</td>
            <td>Extreme learning machines(ELM), Optimally pruned ELM(OP-ELM), BayesNet, SVM, 1-NN, C4.5</td>
            <td><a href="https://doi.org/10.1016/j.neucom.2013.03.057">Extreme learning machines for soybean classification in remote sensing hyperspectral images</td>
            <td>Neurocomputing</td>
        </tr> 
        <tr>
            <td>2017</td>
            <td>Landsat 8, Sentinel-1</td>
            <td>MLP, ENN, 1D-CNNs, 2D-CNNs</td>
            <td><a href="https://doi.org/10.1109/LGRS.2017.2681128">Deep learning classification of land cover and crop types using remote sensing data</td>
            <td>IEEE Geoscience And Remote Sensing Letters</td>
        </tr> 
        <tr>
            <td>2018</td>
            <td>Onsite devices, University of Manchester (UoM) system, University of Bonn system, AVIRIS sensor</td>
            <td>ND-SVM, RoSVM, RF</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2017.2788426">Feature-ensemble-based novelty detection for analyzing plant hyperspectral datasets</td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Sentinel-1, Sentinel-2</td>
            <td>Hierarach RF</td>
            <td><a href="https://doi.org/10.3390/rs10101642">Synergistic use of radar Sentinel-1 and optical Sentinel-2 imagery for crop mapping: A case study for Belgium</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices, RADARSAT-2, VENµS</td>
            <td>Conv1D, MLP, LSTM, XGBoost, RF, SVM</td>
            <td><a href="https://doi.org/10.3390/rs12050832">Synergistic use of multi-temporal RADARSAT-2 and VEN𝜇S data for crop classification based on 1D convolutional 
              neural network</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>Landsat 8, Sentinel-2, Onsite devices</td>
            <td>KNN, RF, SVM, GBDT</td>
            <td><a href="https://doi.org/10.1109/ACCESS.2022.3148691">Remote Sensing and Machine Learning Modeling to Support the Identification of Sugarcane Crops</td>
            <td>IEEE Access</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Zhuhai-1, Sentinel-2, Sentinel-1</td>
            <td>DOCC</td>
            <td><a href="https://doi.org/10.1016/j.jag.2021.102598">DOCC: Deep one-class crop classification via positive and unlabeled learning for multi-modal satellite imagery</td>
            <td>International Journal of Applied Earth Observations and Geoinformation</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Sentinel-1</td>
            <td>1D CNNs, LSTM RNNs, GRU RNNs, RF</td>
            <td><a href="https://doi.org/10.3390/rs11222673">Evaluation of three deep learning models for early crop classification using sentinel-1A imagery time series 
              — A case study in Zhanjiang, China</td>
            <td>Remote sensing</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Sentinel-2</td>
            <td>Polynomial-SVM, RBF-SVM, RF, ANN, CART-DT</td>
            <td><a href="https://doi.org/10.1016/j.landusepol.2019.104190">Mapping sugar cane in complex land scapes by integrating multi-temporal Sentinel-2 images and 
              machine learning algorithms</td>
            <td>Land Use Policy</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Landsat Analysis Ready Data</td>
            <td>DeepCropMapping (DCM), Transformer, MLP, RF</td>
            <td><a href="https://doi.org/10.1016/j.rse.2020.111946">Deep Crop Mapping: A multi-temporal deep learning approach with improved spatial generalizability for 
              dynamic corn and soybean mapping</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>DeeplabV3+, PSPNet, SegNet, U-Net</td>
            <td><a href="https://doi.org/10.1155/2021/6687799">Depth semantic segmentation of tobacco planting areas from unmanned aerial vehicle remote sensing images 
              in plateau mountains</td>
            <td>Journal of Spectroscopy</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>ViT B-16, ViT B-32, EfficientNet B0, EfficientNet B1, ResNet 50</td>
            <td><a href="https://doi.org/10.3390/rs14030592">Transformer neural network for weed and crop classification of high resolution UAV images</td>
            <td>Remote sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>HSI-transunet, SegNet, SETR, UNet, TransUNet</td>
            <td><a href="https://doi.org/10.1016/j.compag.2022.107297">HSI-TransUNet: a transformer based semantic segmentation model for crop mapping from 
              UAV hyperspectral imagery</td>
            <td>Computers and Electronics in Agriculture </td>
        </tr>
    </tbody>
</table>

Agrifood Growth Monitoring
<table>
    <thead>
        <tr>
            <th>Year</th>
            <th>Input</th>
            <th>Methods</th>
            <th>Paper Title</th>
            <th>Pub.</th>
        </tr>
    </thead>
    <tbody align='center'>        
        <tr>
            <td>2022</td>
            <td>Onsite devices</td>
            <td>RFR, Simple Linear Regression（SLR）</td>
            <td><a href="https://doi.org/10.3389/fpls.2022.890892"> Improving Estimation of Winter Wheat Nitrogen Status Using Random Forest by Integrating 
              Multi-Source Data Across Different Agro-Ecological Zones</a></td>
            <td>Frontiers in Plant Science</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV, Onsite devices</td>
            <td>ANN, SVM, RF</td>
            <td><a href="https://doi.org/10.1016/j.isprsjprs.2018.11.015">.Modeling alpine grassland forage phosphorus based on hyperspectral remote sensing
              and a multi-factor machine learning algorithm in the east of Tibetan Plateau,China</td>
            <td>ISPRS Journal of Photogrammetry and Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>Sentinel-2, Landsat-8</td>
            <td>OPtical TRApezoid Model (OPTRAM), Thermal-Optical TRAapezoid Model (TOTRAM)</td>
            <td><a href="https://doi.org/10.1016/j.rse.2017.05.041">.The optical trapezoid model: A novel approach to remote sensing of soil moisture 
              applied to Sentinel-2 and Landsat-8 observations</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2013</td>
            <td>Onsite devices</td>
            <td>Deterministic Downscaling Algorithm (DDA)</td>
            <td><a href="https://doi.org/10.1002/wrcr.20495">.Development of a deterministic downscaling algorithm for remote sensing soil moisture 
              footprint using soil and vegetation classifications</td>
            <td>Water Resources Research</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>NN, Generalized Linear Model (GLM), Gradient Boosting Machine (GBM), Distributed Random Forest (DRF)</td>
            <td><a href="https://doi.org/10.1016/j.rse.2021.112434">.Estimation of root zone soil moisture from ground and remotely sensed soil information 
              with multi sensor data fusion and automated machine learning</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>PLSR, KNN, RFR, BPNN</td>
            <td><a href="https://doi.org/10.1016/j.agwat.2022.107530">.Estimation of soil moisture content under high maize canopy coverage from UAV multimodal 
              data and machine learning</td>
            <td>Agricultural Water Management</td>
        </tr>
    </tbody>
</table>
