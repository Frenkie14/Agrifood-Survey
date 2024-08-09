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

## MindMaps

[Data Source, Storage and Preprocessing](https://Frenkie14.github.io/Agrifood-survey-mindmap/mindmap_dataset.html)

[Applications for Data and Method Selection](https://Frenkie14.github.io/Agrifood-survey-mindmap/mindmap_application.html)

## Related Works Sorted by Applications

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
            <td><a href="https://doi.org/10.1016/j.scitotenv.2016.10.223">Spatiotemporal patterns of paddy rice croplands in China and India from 2000 to 2015</a></td>
            <td>Science of the Total Environment</td>
        </tr> 
        <tr>
            <td>2014</td>
            <td>Hyperion sensor</td>
            <td>ELM, OP-ELM, BayesNet, SVM, 1-NN, C4.5</td>
            <td><a href="https://doi.org/10.1016/j.neucom.2013.03.057">Extreme learning machines for soybean classification in remote sensing hyperspectral images</a></td>
            <td>Neurocomputing</td>
        </tr> 
        <tr>
            <td>2017</td>
            <td>Landsat 8, Sentinel-1</td>
            <td>MLP, ENN, 1D-CNNs, 2D-CNNs</td>
            <td><a href="https://doi.org/10.1109/LGRS.2017.2681128">Deep learning classification of land cover and crop types using remote sensing data</a></td>
            <td>IEEE Geoscience And Remote Sensing Letters</td>
        </tr> 
        <tr>
            <td>2018</td>
            <td>Onsite devices, AVIRIS</td>
            <td>ND-SVM, RoSVM, RF</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2017.2788426">Feature-ensemble-based novelty detection for analyzing plant hyperspectral datasets</a></td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Sentinel-1, Sentinel-2</td>
            <td>Hierarach RF</td>
            <td><a href="https://doi.org/10.3390/rs10101642">Synergistic use of radar Sentinel-1 and optical Sentinel-2 imagery for crop mapping: A case study for Belgium</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices, RADARSAT-2, VENµS</td>
            <td>Conv1D, MLP, LSTM, XGBoost, RF, SVM</td>
            <td><a href="https://doi.org/10.3390/rs12050832">Synergistic use of multi-temporal RADARSAT-2 and VEN𝜇S data for crop classification based on 1D convolutional neural network</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>Landsat 8, Sentinel-2, Onsite devices</td>
            <td>KNN, RF, SVM, GBDT</td>
            <td><a href="https://doi.org/10.1109/ACCESS.2022.3148691">Remote Sensing and Machine Learning Modeling to Support the Identification of Sugarcane Crops</a></td>
            <td>IEEE Access</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Zhuhai-1, Sentinel-2, Sentinel-1</td>
            <td>DOCC</td>
            <td><a href="https://doi.org/10.1016/j.jag.2021.102598">DOCC: Deep one-class crop classification via positive and unlabeled learning for multi-modal satellite imagery</td>
            <td>International Journal of Applied Earth Observations and Geoinformation</a></td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Sentinel-1</td>
            <td>1D CNNs, LSTM RNNs, GRU RNNs, RF</td>
            <td><a href="https://doi.org/10.3390/rs11222673">Evaluation of three deep learning models for early crop classification using sentinel-1A imagery time series 
              — A case study in Zhanjiang, China</a></td>
            <td>Remote sensing</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Sentinel-2</td>
            <td>Polynomial-SVM, RBF-SVM, RF, ANN, CART-DT</td>
            <td><a href="https://doi.org/10.1016/j.landusepol.2019.104190">Mapping sugar cane in complex land scapes by integrating multi-temporal Sentinel-2 images and 
              machine learning algorithms</a></td>
            <td>Land Use Policy</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Landsat Analysis Ready Data</td>
            <td>DCM, Transformer, MLP, RF</td>
            <td><a href="https://doi.org/10.1016/j.rse.2020.111946">Deep Crop Mapping: A multi-temporal deep learning approach with improved spatial generalizability for 
              dynamic corn and soybean mapping</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>DeeplabV3+, PSPNet, SegNet, U-Net</td>
            <td><a href="https://doi.org/10.1155/2021/6687799">Depth semantic segmentation of tobacco planting areas from unmanned aerial vehicle remote sensing images 
              in plateau mountains</a></td>
            <td>Journal of Spectroscopy</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>ViT B-16, ViT B-32, EfficientNet B0, EfficientNet B1, ResNet 50</td>
            <td><a href="https://doi.org/10.3390/rs14030592">Transformer neural network for weed and crop classification of high resolution UAV images</a></td>
            <td>Remote sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>HSI-transunet, SegNet, SETR, UNet, TransUNet</td>
            <td><a href="https://doi.org/10.1016/j.compag.2022.107297">HSI-TransUNet: a transformer based semantic segmentation model for crop mapping from 
              UAV hyperspectral imagery</a></td>
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
              and a multi-factor machine learning algorithm in the east of Tibetan Plateau,China</a></td>
            <td>ISPRS Journal of Photogrammetry and Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>Sentinel-2, Landsat-8</td>
            <td>OPTRAM, TOTRAM</td>
            <td><a href="https://doi.org/10.1016/j.rse.2017.05.041">The optical trapezoid model: A novel approach to remote sensing of soil moisture 
              applied to Sentinel-2 and Landsat-8 observations</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2013</td>
            <td>Onsite devices</td>
            <td>DDA</td>
            <td><a href="https://doi.org/10.1002/wrcr.20495">Development of a deterministic downscaling algorithm for remote sensing soil moisture 
              footprint using soil and vegetation classifications</a></td>
            <td>Water Resources Research</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>NN, GLM, GBM, DRF</td>
            <td><a href="https://doi.org/10.1016/j.rse.2021.112434">Estimation of root zone soil moisture from ground and remotely sensed soil information 
              with multi sensor data fusion and automated machine learning</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>PLSR, kNN, RFR, BPNN</td>
            <td><a href="https://doi.org/10.1016/j.agwat.2022.107530">Estimation of soil moisture content under high maize canopy coverage from UAV multimodal 
              data and machine learning</a></td>
            <td>Agricultural Water Management</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>RADARSAT-2</td>
            <td>PCC, SVM-RFE, RF, SVR, GBRT</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2021.3067890">Estimating soil moisture over winter wheat fields during growing season using machine-learning methods</a></td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Manned aircraft</td>
            <td>LM, RF, NN, SVMR, SVML, GBM, CU</td>
            <td><a href="https://doi.org/10.1016/j.compag.2018.07.016">Integration of high resolution remotely sensed data and machine learning techniques for spatial prediction of soil properties and corn yield</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Landsat-8</td>
            <td>SLR, PLSR, SVM, ANN, OK</td>
            <td><a href="https://doi.org/10.3390/rs11141683">Prediction of soil organic carbon based on Landsat 8 monthly NDVI data for the Jianghan Plain in Hubei Province, China</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2014</td>
            <td>UAV</td>
            <td>PROSAIL</td>
            <td><a href="https://doi.org/10.1016/j.jag.2013.05.007">Inversion of the PROSAIL model to estimate leaf area index of maize, potato, and sunflower fields from unmanned aerial vehicle hyperspectral data</a></td>
            <td>International Journal of Applied Earth Observation and Geoinformation</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>PLSR, ANN, RF, SVM</td>
            <td><a href="https://doi.org/10.3390/rs13152956">Estimation of paddy rice nitrogen content and accumulation both at leaf and plant levels from UAV hyperspectral imagery</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>SVR, ELM, RF</td>
            <td><a href="https://doi.org/10.1007/s11119-022-09901-7">An assessment of multi-view spectral information from UAV-based color-infrared images for improved estimation of nitrogen nutrition status in winter wheat</a></td>
            <td>Precision Agriculture</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>SMAPVEX-12</td>
            <td>SVR, RF, GBDT, XGBoost</td>
            <td><a href="https://doi.org/10.3390/agronomy11071363">Deep learning-based estimation of crop biophysical parameters using multi-source and multi-temporal remote sensing observations</a></td>
            <td>Agronomy</td>
        </tr>
        <tr>
            <td>2012</td>
            <td>Manned aircraft</td>
            <td>LME regression, RF, SVR, Cu</td>
            <td><a href="https://doi.org/10.1016/j.rse.2012.07.006">Forest biomass estimation from airborne LiDAR data using machine learning approaches</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV</td>
            <td>MLR, SVM, ANN, RF</td>
            <td><a href="https://doi.org/10.1186/s13007-019-0394-z">Modeling maize above-ground biomass based on machine learning approaches using UAV remote-sensing data</a></td>
            <td>Plant Methods</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV</td>
            <td>OLS, SVM, BP, RF</td>
            <td><a href="https://doi.org/10.3390/rs11222678">Estimating maize above-ground biomass using 3D point clouds of multi-source unmanned aerial vehicle data at multi-spatial scales</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2016</td>
            <td>HJ satellite</td>
            <td>SVR, ANN, RF</td>
            <td><a href="https://doi.org/10.1016/j.cj.2016.01.008">Estimation of biomass in wheat using random forest regression algorithm and remote sensing data</a></td>
            <td>The Crop Journal</td>
        </tr>
        <tr>
            <td>2015</td>
            <td>UAV</td>
            <td>K-means, Rk-means, SSSVM, KNN, LINSVM, SVM</td>
            <td><a href="https://doi.org/10.1016/j.asoc.2015.08.027">A semi-supervised system for weed mapping in sunflower crops using unmanned aerial vehicles and a crop row detection method</a></td>
            <td>Applied Soft Computing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>CNN+BA, CNN+PSO, CNN+MAML</td>
            <td><a href="https://doi.org/10.3389/fpls.2021.735230">Weed density extraction based on few-shot learning through UAV remote sensing RGB and multispectral images in ecological irrigation area</a></td>
            <td>Frontiers in Plant Science</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>UAV</td>
            <td>EfficientNet, ResNet, ViT</td>
            <td><a href="https://doi.org/10.3390/rs14030592">Transformer neural network for weed and crop classification of high resolution UAV images</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Onsite devices</td>
            <td>LDA, K-NN, SVM</td>
            <td><a href="https://doi.org/10.1016/j.rse.2021.112350">Spectroscopic detection of rice leaf blast infection from asymptomatic to mild stages with integrated machine learning and feature selection</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2012</td>
            <td>Laboratory conditions</td>
            <td>MLR, PLSR</td>
            <td><a href="https://doi.org/10.1016/j.compag.2012.03.006">Detecting powdery mildew of winter wheat using leaf level hyperspectral measurements</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>SVR, MLR</td>
            <td><a href="https://doi.org/10.1016/j.compag.2018.10.009">Evaluation of citrus gummosis disease dynamics and predictions with weather and inversion based leaf optical model</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>ND-SVM, RoSVM</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2017.2788426">Feature-ensemble-based novelty detection for analyzing plant hyperspectral datasets</a></td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>Onsite devices</td>
            <td>SDA, FDA, kNN</td>
            <td><a href="https://doi.org/10.1016/j.compag.2017.01.017">Field detection of anthracnose crown rot in strawberry using spectroscopy technology</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>HOG, SURF, GLCM, ANN, SVM</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2020.03.016">Effect of directional augmentation using supervised machine learning technologies: A case study of strawberry powdery mildew detection</a></td>
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
        <tr>
            <td>2019</td>
            <td>Onsite devices</td>
            <td>LR, SVR, ANN, RF, SGB</td>
            <td><a href="https://doi.org/10.3389/fpls.2019.00809">California almond yield prediction at the orchard level with a machine learning approach</a></td>
            <td>Frontiers in Plant Science</td>
        </tr>
        <tr>
            <td>2013</td>
            <td>Onsite devices</td>
            <td>SMF</td>
            <td><a href="https://doi.org/10.1016/j.rse.2012.12.017">MODIS-based corn grain yield estimation model incorporating crop phenology information</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>USDA NASA, MODIS, PRISM</td>
            <td>OLS, LASSO, SVM, RF, AdaBoost, DNN</td>
            <td><a href="https://doi.org/10.3390/rs12081232">Combining multi-source data and machine learning approaches to predict winter wheat yield in the conterminous United States</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2016</td>
            <td>AVHRR, MODIS</td>
            <td>MLR, BNN, MOB</td>
            <td><a href="https://doi.org/10.1016/j.agrformet.2015.11.003">Crop yield forecasting on the Canadian Prairies by remotely sensed vegetation indices and machine learning methods</a></td>
            <td>Agricultural and Forest Meteorology</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>USDA-NASS, SMAP, MODIS</td>
            <td>PLR, KRR</td>
            <td><a href="https://doi.org/10.1016/j.rse.2019.111460">Synergistic integration of optical and microwave satellite data for crop yield estimation</a></td>
            <td>Remote Sensing of Environment</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices, UAV</td>
            <td>LR, MLR, SMLR, PLSR, ANN, RF</td>
            <td><a href="https://doi.org/10.3390/rs12030508">Wheat growth monitoring and yield estimation based on multi-rotor unmanned aerial vehicle</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>MODIS, Onsite devices, SILO</td>
            <td>RF, CU, XB, SVMl, SVMr, MLP, MARS, GP, kNN</td>
            <td><a href="https://doi.org/10.1016/j.isprsjprs.2019.11.008">Estimating wheat yields in Australia using climate records, satellite image time series and machine learning methods</a></td>
            <td>ISPRS Journal of Photogrammetry and Remote Sensing</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>MOD13Q1</td>
            <td>GPR, SVM, RF</td>
            <td><a href="https://doi.org/10.3390/rs12020236">Prediction of winter wheat yield based on multi-source data and machine learning in China</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>DSASI-MADR, ASAP</td>
            <td>LASSO, RF, MLP, SVR, GBR</td>
            <td><a href="https://doi.org/10.1016/j.agrformet.2021.108555">Yield forecasting with machine learning and small data: What gains for grains?</a></td>
            <td>Agricultural and Forest Meteorology</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Onsite devices, NASA LPDAAC, BMO</td>
            <td>STC</td>
            <td><a href="https://doi.org/10.1007/s11119-018-09628-4">An approach to forecast grain crop yield using multi-layered, multi-farm data sets and machine learning</a></td>
            <td>Precision Agriculture</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Onsite devices, Sentinel-2</td>
            <td>MR, RF, SVM</td>
            <td><a href="https://doi.org/10.3390/rs11232873">Monitoring within-field variability of corn yield using Sentinel-2 and machine learning techniques</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>MODIS</td>
            <td>LASSO, RF, XGBoost, LSTM</td>
            <td><a href="https://doi.org/10.3390/rs12010021">Combining optical, fluorescence, thermal satellite, and environmental data to predict county-level maize yield in China using machine learning approaches</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Onsite devices, Landsat, MODIS, CMA</td>
            <td>LASSO, LightGBM, LSTM</td>
            <td><a href="https://doi.org/10.1016/j.agrformet.2021.108666">Integrating satellite-derived climatic and vegetation indices to predict smallholder maize yield using deep learning</a></td>
            <td>Agricultural and Forest Meteorology</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>UAV</td>
            <td>CNN</td>
            <td><a href="https://doi.org/10.1016/j.compag.2019.104859">Crop yield prediction with deep convolutional neural networks</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Sentinel-2, MODIS</td>
            <td>LIN, RID, SVR, GPR, CNN-2D, CNN-3D</td>
            <td><a href="https://doi.org/10.3390/rs13071391">Rice-yield prediction with multi-temporal sentinel-2 data and 3D CNN: A case study in Nepal</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Onsite devices, UAV</td>
            <td>SPAD, CCC, LAI, AGB</td>
            <td><a href="https://doi.org/10.1016/j.fcr.2021.108148">Remote estimation of grain yield based on UAV data in different rice cultivars under contrasting climatic zone</a></td>
            <td>Field Crops Research</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>MODIS</td>
            <td>DT, RF, SVM, LSTM, 2D-CNN, 3DMKGP</td>
            <td><a href="https://doi.org/10.1109/JSTARS.2021.3073149">Exploiting hierarchical features for crop yield prediction based on 3-d convolutional neural networks and multikernel gaussian process</a></td>
            <td>IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>MODIS</td>
            <td>OLS, RF, LSTM</td>
            <td><a href="https://doi.org/10.1016/j.agrformet.2019.107886">Satellite-based soybean yield forecast: Integrating machine learning and weather data for improving crop yield prediction in southern Brazil</a></td>
            <td>Agricultural and Forest Meteorology</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>MODIS, COMS MI, RDAPS, IRRI</td>
            <td>RSCM, FFNN, 1D-CNN, LSTM, 1D-CNN+LSTM, LSTM+1D-CNN</td>
            <td><a href="https://doi.org/10.1016/j.scitotenv.2021.149726">Predicting rice yield at pixel scale through synthetic use of crop and deep learning models with satellite data in South and North Korea</a></td>
            <td>Science of The Total Environment</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>UAV</td>
            <td>Pretrained CNN, CNN-LSTM, ConvLSTM, 3D-CNN</td>
            <td><a href="https://doi.org/10.3390/rs12234000">Crop yield prediction using multitemporal UAV data and spatio-temporal deep learning models</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>AVHRR, SoilGrids</td>
            <td>LSTM-CNN, RF, SVM, LR</td>
            <td><a href="https://doi.org/10.3390/rs12111744">Winter wheat yield prediction at county level and uncertainty analysis in main wheat-producing regions of China with deep learning approaches</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>MODIS</td>
            <td>DT, RF, SVM, LSTM, 2D-CNN, SSTNN</td>
            <td><a href="https://doi.org/10.1016/j.jag.2021.102436">Crop yield prediction from multi-spectral, multi-temporal remotely sensed imagery using recurrent 3D convolutional neural networks</a></td>
            <td>International Journal of Applied Earth Observation and Geoinformation</td>
        </tr>
    </tbody>
</table>


Agrifood Quality Assessment
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
            <td>2018</td>
            <td>Onsite devices</td>
            <td>SVM</td>
            <td><a href="https://doi.org/10.1109/IC3INA.2018.8629534">Comparison of features for strawberry grading classification with novel dataset</a></td>
            <td>IC3INA</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>CNN, AlexNet, GoogLeNet, VGGNet, Xception, MobileNet</td>
            <td><a href="https://doi.org/10.14419/ijet.v7i4.40.24080">Evaluation of deep convolutional neural network architectures for strawberry quality inspection</a></td>
            <td>International Journal of Engineering & Technology</td>
        </tr>
    </tbody>
</table>


Pasture Monitoring and Evaluation
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
            <td>PLS, RF</td>
            <td><a href="https://doi.org/10.1016/j.compag.2021.106614">Estimating pasture quality of Mediterranean grasslands using hyperspectral narrow bands from field spectroscopy by Random Forest and PLS regressions</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>UAV</td>
            <td>GAM, RF</td>
            <td><a href="https://doi.org/10.1016/j.compag.2020.105880">Predicting pasture biomass using a statistical model and machine learning algorithm implemented with remotely sensed imagery</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Sentinel-2, Onsite devices</td>
            <td>MLP</td>
            <td><a href="https://doi.org/10.3390/rs13040603">Estimating pasture biomass using sentinel-2 imagery and machine learning</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Public datasets</td>
            <td>DeepPaSTL</td>
            <td><a href="https://doi.org/10.3390/agronomy11112245">DeepPaSTL: Spatio-temporal deep learning methods for predicting long-term pasture terrains using synthetic datasets</a></td>
            <td>Agronomy</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Onsite devices, UAV</td>
            <td>ANN, SVM, RF</td>
            <td><a href="https://doi.org/10.1016/j.isprsjprs.2018.11.015">Modeling alpine grassland forage phosphorus based on hyperspectral remote sensing and a multi-factor machine learning algorithm 
              in the east of Tibetan Plateau, China</a></td>
            <td>ISPRS Journal of Photogrammetry and Remote Sensing</td>
        </tr>
    </tbody>
</table>


Animal Individual Monitoring
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
            <td>2018</td>
            <td>Onsite devices</td>
            <td>Fisherface, VGG-Face+SVM, CNN</td>
            <td><a href="https://doi.org/10.1016/j.compind.2018.02.016">Towards on-farm pig face recognition using convolutional neural networks</a></td>
            <td>Computers in Industry</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Onsite devices</td>
            <td>AlexNet, VGG16, ResNet50, MobilNet V2, GoogLeNet</td>
            <td><a href="https://doi.org/10.1371/journal.pone.0307252">Individual dairy cow identification based on lightweight convolutional neural network</a></td>
            <td>Plos One</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>Public datasets</td>
            <td>AP-10K</td>
            <td><a href="https://doi.org/10.3390/rs13040603">Ap-10k: A benchmark for animal pose estimation in the wild</a></td>
            <td>Arxiv Preprint</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>FCN, SDS</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2018.10.005">High-accuracy image segmentation for lactating sows using a fully convolutional network</a></td>
            <td>Biosystems Engineering</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>Fast R-CNN</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2019.11.013">Automatic recognition of lactating sow postures by refined two-stream RGB-D faster R-CNN</a></td>
            <td>Biosystems Engineering</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>ImageNet, NADIS, Pixabay, Flickr, Gettyimages</td>
            <td>AlexNet, LeNet, VGG16, DenseNet-201, Inception-v3, ResNet-50, DarkNet</td>
            <td><a href="https://doi.org/10.1016/j.compag.2020.105528">Automated sheep facial expression classification using deep transfer learning</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>VGG-16</td>
            <td><a href="https://doi.org/10.1088/1742-6596/1453/1/012054">Cattle face recognition method based on parameter transfer and deep learning</a></td>
            <td>Journal of Physics: Conference Series</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>YOLOV3+LSTM, YOLOV3+BLSTM, YOLOV3+GRU, YOLOV3+Stacked LSTM, YOLOV3+SVM, YOLOV3+KNN, YOLOV3+DTC</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2019.11.017">Lameness detection of dairy cows based on the YOLOv3 deep learning algorithm and a relative step size characteristic vector</a></td>
            <td>Biosystems Engineering</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>MS COCO datasets</td>
            <td>ViTPose</td>
            <td><a href="https://github.com/ViTAE-Transformer/ViTPose">Vitpose: Simple vision transformer baselines for human pose estimation</a></td>
            <td>NeurIPS</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>Onsite devices</td>
            <td>Fully automatic computer vision system</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2017.08.011">Implementation of an automatic 3D vision monitor for dairy cow locomotion in a commercial farm</a></td>
            <td>Biosystems Engineering</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>Public datasets</td>
            <td>GMFlow</td>
            <td><a href="https://github.com/haofeixu/gmflow">GMflow: Learning optical flow via global matching</a></td>
            <td>CVPR</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>Onsite devices, MODIS</td>
            <td>GLM, GAM, RF, GBM, NNET, MARS, FDA, CT, SVM, NB, ADA</td>
            <td><a href="https://doi.org/10.1016/j.actatropica.2022.106542">Exploration of machine learning models to predict the environmental and remote sensing risk factors of haemonchosis in sheep flocks of Rajasthan, India</a></td>
            <td>Acta Tropica</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>EFMYOLOv3, SSD, YOLOv3</td>
            <td><a href="https://doi.org/10.1016/j.compag.2020.105754">Automatic recognition of dairy cow mastitis from thermal images by a deep learning detector</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>Fast-RCNN-VGG16, YOLOv3-Darknet53</td>
            <td><a href="https://doi.org/10.1016/j.compag.2020.105627">Deep learning-based hierarchical cattle behavior recognition with spatio-temporal information</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>CNN</td>
            <td><a href="https://doi.org/10.1016/j.biosystemseng.2020.03.013">Assessment of dairy cow heat stress by monitoring drinking behaviour using an embedded imaging system</a></td>
            <td>Biosystems Engineering</td>
        </tr>
        <tr>
            <td>2015</td>
            <td>Laboratory conditions</td>
            <td>PNN</td>
            <td><a href="https://doi.org/10.1016/j.meatsci.2014.09.001">Classification of fresh and frozen-thawed pork muscles using visible and near infrared hyperspectral imaging and textural analysis</a></td>
            <td>Meat Science</td>
        </tr>
        <tr>
            <td>2016</td>
            <td>GeoEye, SWISSTOPO</td>
            <td>CNN</td>
            <td><a href="https://doi.org/10.1109/TGRS.2016.2545919">Detection of fragmented rectangular enclosures in very high resolution remote sensing images</a></td>
            <td>IEEE Transactions on Geoscience and Remote Sensing</td>
        </tr>
    </tbody>
</table>


Fishing Area Identification And Prediction
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
            <td>GF-2</td>
            <td>HDCUNet, FCN-8s, SegNet, U-Net, TS</td>
            <td><a href="https://doi.org/10.1080/01431161.2019.1706009">Research on a novel extraction method using Deep Learning based on GF-2 images for aquaculture areas</a></td>
            <td>International Journal of Remote Sensing</td>
        </tr>
        <tr>
            <td>2017</td>
            <td>Sentinel-1</td>
            <td>Connected Component Segmentation</td>
            <td><a href="https://doi.org/10.3390/rs9050440">Large-scale assessment of coastal aquaculture ponds with Sentinel-1 time series data</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2019</td>
            <td>Landsat TM, OLI, GF-1</td>
            <td>SVM</td>
            <td><a href="https://doi.org/10.1016/j.jag.2019.03.019">Extracting aquaculture ponds from natural water surfaces around inland lakes on medium resolution multispectral images</a></td>
            <td>International Journal of Applied Earth Observation and Geoinformation</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Landsat, GF-1, ALOS, ZY-3</td>
            <td>RCSANet</td>
            <td><a href="https://doi.org/10.3390/rs13010092">RCSANet: A full convolutional network for extracting inland aquaculture ponds from high-spatial-resolution images</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2021</td>
            <td>GF-1, GF-2</td>
            <td>Semi-SSN</td>
            <td><a href="https://doi.org/10.3390/rs13061083">Semi-/Weakly-supervised semantic segmentation method and its application for coastal aquaculture areas based on multi-source remote sensing
              images—taking the Fujian coastal area (mainly Sanduo) as an example</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2018</td>
            <td>GF-1</td>
            <td>DS-HCN, AT, DeepLab</td>
            <td><a href="https://doi.org/10.3390/rs10071130">Automatic raft labeling for remote sensing images via dual-scale homogeneous convolutional neural network</a></td>
            <td>Remote Sensing</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>NOAA, METOP-1, METOP-2, MODIS</td>
            <td>HE-DFNETS</td>
            <td><a href="https://doi.org/10.1155/2022/5081541">HE‐DFNETS: a novel hybrid deep learning architecture for the prediction of potential fishing zone areas in Indian Ocean using remote sensing images</a></td>
            <td>Computational Intelligence and Neuroscience</td>
        </tr>
    </tbody>
</table>


Fish Production Forecast
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
            <td>2021</td>
            <td>UAV</td>
            <td>YOLOv3</td>
            <td><a href="https://doi.org/10.3390/drones5020028">Seecucumbers: Using deep learning and drone imagery to detect sea cucumbers on coral reef flats</a></td>
            <td>Drones</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>Onsite devices</td>
            <td>MaskRCNN</td>
            <td><a href="https://doi.org/10.1016/j.ecss.2022.107815">Coastal fisheries resource monitoring through A deep learning-based underwater video analysis</a></td>
            <td>Estuarine, Coastal and Shelf Science</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>Onsite devices, MODIS, Landsat, GSW JRC</td>
            <td>XGBoost</td>
            <td><a href="https://doi.org/10.3389/fenvs.2022.944319">Remote sensing modeling of environmental influences on lake fish resources by machine learning: A practice in the largest freshwater lake of China</a></td>
            <td>Frontiers in Environmental Science</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>Faster MSSDLite, YOLOv3, Faster RCNN, HOG+SVM</td>
            <td><a href="https://doi.org/10.1016/j.compag.2020.105339">Real-time robust detector for underwater live crabs based on deep learning</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2023</td>
            <td>Onsite devices</td>
            <td>MobileCenterNet, ResNet-CenterNet</td>
            <td><a href="https://doi.org/10.1016/j.compag.2022.107522">Real-time detection of underwater river crab based on multi-scale pyramid fusion image enhancement and MobileCenterNet model</a></td>
            <td>Computers and Electronics in Agriculture</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>YOLOv3</td>
            <td><a href="https://doi.org/10.1093/icesjms/fsz223">Automatic detection of Western rock lobster using synthetic data</a></td>
            <td>ICES Journal of Marine Science</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Laboratory conditions</td>
            <td>Mask-RCNN</td>
            <td><a href="https://doi.org/10.1016/j.foodcont.2020.107184">An application of Convolutional Neural Network to lobster grading in the Southern Rock Lobster supply chain</a></td>
            <td>Food Control</td>
        </tr>
        <tr>
            <td>2020</td>
            <td>Onsite devices</td>
            <td>CNN</td>
            <td><a href="https://doi.org/10.1007/s43674-022-00048-6">Fish recognition model for fraud prevention using convolutional neural networks</a></td>
            <td>Advances in Computational Intelligence</td>
        </tr>
    </tbody>
</table>
