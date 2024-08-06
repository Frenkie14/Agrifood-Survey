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
            <td>ELM, OP-ELM, BayesNet, SVM, 1-NN, C4.5</td>
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
            <td>DCM, Transformer, MLP, RF</td>
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
            <td>RFR, SLR</td>
            <td><a href="https://doi.org/10.3389/fpls.2022.890892">Improving Estimation of Winter Wheat Nitrogen Status Using Random Forest by Integrating 
              Multi-Source Data Across Different Agro-Ecological Zones</a></td>
            <td>Frontiers in Plant Science</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV, Onsite devices</td>
            <td>ANN, SVM, RF</td>
            <td><a href="https://doi.org/10.1016/j.isprsjprs.2018.11.015">Modeling alpine grassland forage phosphorus based on hyperspectral remote sensing
              and a multi-factor machine learning algorithm in the east of Tibetan Plateau,China</td>
            <td>ISPRS Journal of Photogrammetry and Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>Sentinel-2, Landsat-8</td>
            <td>OPTRAM, TOTRAM</td>
            <td><a href="https://doi.org/10.1016/j.rse.2017.05.041">The optical trapezoid model: A novel approach to remote sensing of soil moisture 
              applied to Sentinel-2 and Landsat-8 observations</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2013</td>
            <td>Onsite devices</td>
            <td>DDA</td>
            <td><a href="https://doi.org/10.1002/wrcr.20495">Development of a deterministic downscaling algorithm for remote sensing soil moisture 
              footprint using soil and vegetation classifications</td>
            <td>Water Resources Research</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>NN, GLM, GBM, DRF</td>
            <td><a href="https://doi.org/10.1016/j.rse.2021.112434">Estimation of root zone soil moisture from ground and remotely sensed soil information 
              with multi sensor data fusion and automated machine learning</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>PLSR, kNN, RFR, BPNN</td>
            <td><a href="https://doi.org/10.1016/j.agwat.2022.107530">Estimation of soil moisture content under high maize canopy coverage from UAV multimodal 
              data and machine learning</td>
            <td>Agricultural Water Management</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>RADARSAT-2</td>
            <td>PCC, SVM-RFE, RF, SVR, GBRT</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2021.3067890">Estimating soil moisture over winter wheat fields during growing season using machine-learning methods</td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Manned aircraft</td>
            <td>LM, RF, NN, SVMR, SVML, GBM, CU</td>
            <td><a href="https://doi.org/10.1016/j.compag.2018.07.016">Integration of high resolution remotely sensed data and machine learning techniques for spatial prediction of soil properties and corn yield</td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Landsat-8</td>
            <td>SLR, PLSR, SVM, ANN, OK</td>
            <td><a href="https://doi.org/10.3390/rs11141683">Prediction of soil organic carbon based on Landsat 8 monthly NDVI data for the Jianghan Plain in Hubei Province, China</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2014</td>
            <td>UAV</td>
            <td>PROSAIL</td>
            <td><a href="https://doi.org/10.1016/j.jag.2013.05.007">Inversion of the PROSAIL model to estimate leaf area index of maize, potato, and sunflower fields from unmanned aerial vehicle hyperspectral data</td>
            <td>International Journal of Applied Earth Observation and Geoinformation</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>PLSR, ANN, RF, SVM</td>
            <td><a href="https://doi.org/10.3390/rs13152956">Estimation of paddy rice nitrogen content and accumulation both at leaf and plant levels from UAV hyperspectral imagery</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>SVR, ELM, RF</td>
            <td><a href="https://doi.org/10.1007/s11119-022-09901-7">An assessment of multi-view spectral information from UAV-based color-infrared images for improved estimation of nitrogen nutrition status in winter wheat</td>
            <td>Precision Agriculture</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>SMAPVEX-12</td>
            <td>SVR, RF, GBDT, XGBoost</td>
            <td><a href="https://doi.org/10.3390/agronomy11071363">Deep learning-based estimation of crop biophysical parameters using multi-source and multi-temporal remote sensing observations</td>
            <td>Agronomy</td>
        </tr>
        <tr>
            <td>2012</td>
            <td>Manned aircraft</td>
            <td>LME regression, RF, SVR, Cu</td>
            <td><a href="https://doi.org/10.1016/j.rse.2012.07.006">Forest biomass estimation from airborne LiDAR data using machine learning approaches</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV</td>
            <td>MLR, SVM, ANN, RF</td>
            <td><a href="https://doi.org/10.1186/s13007-019-0394-z">Modeling maize above-ground biomass based on machine learning approaches using UAV remote-sensing data</td>
            <td>Plant Methods</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV</td>
            <td>OLS, SVM, BP, RF</td>
            <td><a href="https://doi.org/10.3390/rs11222678">Estimating maize above-ground biomass using 3D point clouds of multi-source unmanned aerial vehicle data at multi-spatial scales</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2016</td>
            <td>HJ satellite</td>
            <td>SVR, ANN, RF</td>
            <td><a href="https://doi.org/10.1016/j.cj.2016.01.008">Estimation of biomass in wheat using random forest regression algorithm and remote sensing data</td>
            <td>The Crop Journal</td>
        </tr>
        <tr>
            <td>2015</td>
            <td>UAV</td>
            <td>K-means, Rk-means, SSSVM, KNN, LINSVM, SVM</td>
            <td><a href="https://doi.org/10.1016/j.asoc.2015.08.027">A semi-supervised system for weed mapping in sunflower crops using unmanned aerial vehicles and a crop row detection method</td>
            <td>Applied Soft Computing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>CNN+BA, CNN+PSO, CNN+MAML</td>
            <td><a href="https://doi.org/10.3389/fpls.2021.735230">Weed density extraction based on few-shot learning through UAV remote sensing RGB and multispectral images in ecological irrigation area</td>
            <td>Frontiers in Plant Science</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>EfficientNet, ResNet, ViT</td>
            <td><a href="https://doi.org/10.3390/rs14030592">Transformer neural network for weed and crop classification of high resolution UAV images</td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Onsite devices</td>
            <td>LDA, K-NN, SVM</td>
            <td><a href="https://doi.org/10.1016/j.rse.2021.112350">Spectroscopic detection of rice leaf blast infection from asymptomatic to mild stages with integrated machine learning and feature selection</td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2012</td>
            <td>Laboratory conditions</td>
            <td>MLR, PLSR</td>
            <td><a href="https://doi.org/10.1016/j.compag.2012.03.006">Detecting powdery mildew of winter wheat using leaf level hyperspectral measurements</td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>SVR, MLR</td>
            <td><a href="https://doi.org/10.1016/j.compag.2018.10.009">Evaluation of citrus gummosis disease dynamics and predictions with weather and inversion based leaf optical model</td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>ND-SVM, RoSVM</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2017.2788426">Feature-ensemble-based novelty detection for analyzing plant hyperspectral datasets</td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>Onsite devices</td>
            <td>SDA, FDA, kNN</td>
            <td><a href="https://doi.org/10.1016/j.compag.2017.01.017">Field detection of anthracnose crown rot in strawberry using spectroscopy technology</td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>HOG, SURF, GLCM, ANN, SVM</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2020.03.016">Effect of directional augmentation using supervised machine learning technologies: A case study of strawberry powdery mildew detection</td>
            <td>Biosystems Engineering</td>
        </tr>
    </tbody>
</table>


Agrifood Yield Prediction
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
            <td>2020</td>
            <td>UAV</td>
            <td>PLSR, RFR, SVM, DNN-F1, DNN-F2</td>
            <td><a href="https://doi.org/10.1016/j.rse.2019.111599">Soybean yield prediction from UAV using multimodal data fusion and deep learning</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
    </tbody>
</table>
