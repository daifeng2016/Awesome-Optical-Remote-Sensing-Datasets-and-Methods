## 📢 Latest Updates
:fire::fire::fire:  Lastest Updated on 2025.04.02 for UrbanSARFloods, dataset3_Wuhan, Kuro Siwo, and BRIGHT :fire::fire::fire:


# Awesome-Optical-Remote-Sensing-Datasets-and-Methods
This repository is for summarizing the latest optical remote sensing datasets and methods, which are listed in our review article [Deep learning change detection techniques for optical remote sensing imagery: Status, Perspectives and Challenges](https://www.sciencedirect.com/science/article/pii/S1569843224006381) published in International Journal of Applied Earth Observation and Geoinformation.
# Introduction
Change detection (CD) aims to compare and analyze images of identical geographic areas but different dates, whereby revealing spatio-temporal change patterns of Earth’s surface. With the implementation of the High-Resolution Earth Observation Project, an integrated sky-to-ground observation system has been continuously developed and improved. The accumulation of massive multi-modal, multi-angle, and mul-ti-resolution remote sensing data have greatly enriched the CD data sources. Among them, high-resolution optical remote sensing images contain abundant spatial detail information, making it possible to interpret fine-grained scenes and greatly expand the application breadth and depth of CD. Generally, traditional optical remote sensing CD methods are cumbersome in steps and have a low level of automation. In con-trast, artificial intelligence (AI) based CD methods possess powerful feature extraction and non-linear modeling capabilities, thereby gaining advantages that traditional methods cannot match. As a result, they have become the mainstream approaches in the field of CD. This review article systematically summarizes the datasets, theories, and methods of CD for optical remote sensing image. It provides a comprehensive analysis of AI-based CD algorithms based on deep learning paradigms from the perspectives of algorithm granularity. In-depth analysis of the performance of typical algorithms are further conducted. Finally, we summarize the challenges and trends of the CD algorithms in the AI era, aiming to provide important guidelines and insights for relevant researchers.
# Publicaiton trends of DLCD
![image](https://github.com/user-attachments/assets/114813aa-681e-40a1-8f09-514cce9085b4)


## BCD datasets of optical remote sensing images 
<table>
<caption>
	<tr>
	    <th>Target of interest</th>
	    <th>Datasets</th>
            <th>Year</th>	
	    <th>Image Pairs</th>
	    <th>Image size</th>	
	    <th>Resolution</th>
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="13">Building</th>
    <th>TUE-CD[<a href="https://doi.org/10.1109/TGRS.2024.3438290" target="_blank">paper</a>]</th>
    <th>2024</th>
    <th>1656</th>
    <th>256×256</th>
    <th>1.8m</th>
    <th> <a href="https://github.com/RSMagneto/MSI-Net" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>EGY-BCD[<a href="https://doi.org/10.1109/LGRS.2023.3283505" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>6091</th>
    <th>256×256</th>
    <th>0.25m</th>
    <th> <a href="https://github.com/oshholail/EGY-BCD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>HRCUS-CD[<a href="https://doi.org/10.1109/TGRS.2023.3300533" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>11388</th>
    <th>256×256</th>
    <th>0.5m</th>
    <th> <a href="https://github.com/zjd1836/AERNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>SI-BU dataset[<a href="https://doi.org/10.1016/j.isprsjprs.2023.05.011" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>4932</th>
    <th>512×512</th>
    <th>0.2m</th>
    <th> <a href="https://github.com/liaochengcsu/BCE-Net" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>LEVIR-CC[<a href="https://doi.org/10.1109/TGRS.2022.3218921" target="_blank">paper</a>]</th>
    <th>2022</th>
    <th>10077</th>
    <th>1024×1024</th>
    <th>0.5m</th>
    <th> <a href="https://github.com/Chen-Yang-Liu/RSICC" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>SYSU-CD[<a href="https://doi.org/10.1109/TGRS.2021.3085870" target="_blank">paper</a>]</th>
    <th>2021</th>
    <th>20000</th>
    <th>256×256</th>
    <th>0.5m</th>
    <th> <a href="https://github.com/liumency/SYSU-CD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>CD_Data_GZ[<a href="https://doi.org/10.1109/TGRS.2020.3011913" target="_blank">paper</a>]</th>
    <th>2020</th>
    <th>19</th>
    <th>1006×1168-4936×5224</th>
    <th>0.55m</th>
    <th><a href="https://github.com/daifeng2016/Change-Detection-Dataset-for-High-Resolution-Satellite-Imagery" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>DSIFN Dataset[<a href="https://doi.org/10.1016/j.isprsjprs.2020.06.003" target="_blank">paper</a>]</th>
    <th>2020</th>
    <th>3940</th>
    <th>512×512</th>
    <th>-</th>
    <th><a href="https://github.com/GeoZcx/A-deeply-supervised-image-fusion-network-for-change-detection-in-remote-sensing-images/tree/master/dataset" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>LEVIR-CD[<a href="https://doi.org/10.3390/rs12101662" target="_blank">paper</a>]</th>
    <th>2020</th>
    <th>637</th>
    <th>1024×1024</th>
    <th>0.5m</th>
    <th><a href="https://justchenhao.github.io/LEVIR/" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>LEVIR-CD+[<a href="https://doi.org/10.3390/rs13245094" target="_blank">paper</a>]</th>
    <th>2020</th>
    <th>1970</th>
    <th>1024×1024</th>
    <th>0.5m</th>
    <th><a href="https://github.com/S2Looking/Dataset" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>WHU Building CD[<a href="https://doi.org/10.1109/TGRS.2018.2858817" target="_blank">paper</a>]</th>
    <th>2019</th>
    <th>1</th>
    <th>32507×15354</th>
    <th>0.2m</th>
    <th><a href="https://study.rsgis.whu.edu.cn/pages/download/building_dataset.html" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>CDD Dataset[<a href="https://doi.org/10.5194/isprs-archives-XLII-2-565-2018" target="_blank">paper</a>]</th>
    <th>2018</th>
    <th>16000</th>
    <th>256×256</th>
    <th>0.03-1m</th>
    <th><a href="https://drive.google.com/file/d/1GX656JqqOyBi_Ef0w65kDGVto-nHrNs9/edit" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>ABCD[<a href="https://doi.org/10.23919/MVA.2017.7986759" target="_blank">paper</a>]</th>
    <th>2017</th>
    <th>16950</th>
    <th>128×128</th>
    <th>0.4m</th>
    <th><a href="https://github.com/gistairc/ABCDdataset" target="_blank">link</a></th>
    </tr>
     <tr>
    <caption>
    </tr>
     <tr>
    <th rowspan="4">Land cover</th>
    <th>TZ-CD[<a href="https://doi.org/10.3390/rs15051219" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>1</th>
    <th>30307×40620</th>
    <th>1m</th>
    <th>-</th>
    </tr>
     <tr>
    <th>BTCDD[<a href="https://doi.org/10.1016/j.jag.2021.102597" target="_blank">paper</a>]</th>
    <th>2021</th>
    <th>5281</th>
    <th>256×256</th>
    <th>-</th>
    <th>-</th>
    </tr>
     <tr>
    <th>ZY3[<a href="https://doi.org/10.1109/TGRS.2020.2981051" target="_blank">paper</a>]</th>
    <th>2017</th>
    <th>1</th>
    <th>458×559</th>
    <th>5.8m</th>
    <th><a href="http://poles.tpdc.ac.cn/zh-hans/data/b9748f8d-c06e-42a4-a2bc-7a185927f025/" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>AICD[<a href="https://ieeexplore.ieee.org/document/6050150" target="_blank">paper</a>]</th>
    <th>2011</th>
    <th>1000</th>
    <th>800×600</th>
    <th>0.5m</th>
    <th>-</th>
    </tr>
     <tr>
<caption>
    <tr>
    <th rowspan="1">Mine</th>
    <th>MineNetCD[<a href="https://doi.org/10.48550/arXiv.2407.03971" target="_blank">paper</a>]</th>
    <th>2024</th>
    <th>71711</th>
    <th>256×256</th>
    <th>1.2m</th>
    <th><a href="https://huggingface.co/datasets/ericyu/MineNetCD256" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="1">Cropland</th>
    <th>CLCD[<a href="https://doi.org/10.1109/JSTARS.2022.3177235" target="_blank">paper</a>]</td>
    <th>2022</th>
    <th>600</th>
    <th>512×512</th>
    <th>0.5-2m</th>
    <th><a href="https://github.com/liumency/CropLand-CD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="1">Riverway</th>
    <th>The River Data Set[<a href="https://doi.org/10.1109/TGRS.2018.2849692" target="_blank">paper</a>]</th>
    <th>2019</th>
    <th>1</th>
    <th>463×241</th>
    <th>30m</th>
    <th><a href="https://share.weiyun.com/5xdge4R" target="_blank">link</a></th>
    </tr>
     <tr>
<table>
	


## BCD contest dataset for optical remote sensing images
<table>
<caption>
	<tr>
	    <th>Target of interest</th>
	    <th>Event</th>
            <th>Year</th>	
	    <th>Track</th>	
	    <th>Image Pairs</th>
	    <th>Image size</th>	
	    <th>Resolution</th>
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="4">Land cover</th>
    <th>"Shengteng Cup" remote sensing image intelligent processing algorithm competition</th>
    <th>2021</th>
    <th>Remote sensing image change detection</th>
    <th>4194</th>    
    <th>512×512</th>
    <th>1-2m</th>
    <th> <a href="http://rsipac.whu.edu.cn/subject_two_2021" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>Artificial Intelligence Remote sensing Interpretation Competition</th>
    <th>2020</th>
    <th>change detection</th>
    <th>4662</th>
    <th>512×512</th>
    <th>0.5-3m</th>
    <th><a href="https://rs.sensetime.com/">link</a></th>
    </tr>
     <tr>
    <th>SN7: Multi-Temporal Urban Development Challenge</th>
    <th>2020</th>
    <th>Multi-Temporal Urban Development Challenge</th>
    <th>12</th>
    <th>1024×1024</th>
    <th>4m</th>
    <th><a href="https://spacenet.ai/sn7-challenge/">link</a></th>
    </tr>
     <tr>
    <th>Remote sensing image sparse characterization and intelligent Processing algorithm competition</th>
    <th>2019</th>
    <th>Remote sensing image change detection</th>
    <th>103</th>
    <th>960×960</th>
    <th>-</th>
    <th><a href="https://autdatamotion.github.io/RSC2019/#/home">link</a></th>
    </tr>
     <tr>
<caption>
    <tr>
    <th rowspan="1">Building</th>
    <th>The 5th "Sino-Keke Star Map Cup" International high-resolution remote sensing image interpretation Competition</th>
    <th>2021</th>
    <th>Building survey and change detection in high resolution visible light images</th>
    <th>2000</th>
    <th>512×512</th>
    <th>2m</th>
    <th><a href="https://www.gaofen-challenge.com/challenge" target="_blank">link</a></th>
    </tr>
     <tr>
    <table>

## BCD datasets of SAR remote sensing images
<table>
<caption>
	<tr>
	    <th>Target of interest</th>
	    <th>Datasets</th>
            <th>Year</th>	
	    <th>Image Pairs</th>
	    <th>Image size</th>	
	    <th>Resolution</th>
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="1">Flood</th>
    <th>UrbanSARFloods [<a href="https://openaccess.thecvf.com/content/CVPR2024W/EarthVision/html/Zhao_UrbanSARFloods_Sentinel-1_SLC-Based_Benchmark_Dataset_for_Urban_and_Open-Area_Flood_CVPRW_2024_paper.html" target="_blank">paper</a>]</th>
    <th>2024</th>
    <th>8879</th>
    <th>512×512</th>
    <th>20m</th>
    <th> <a href="https://github.com/jie666-6/UrbanSARFloods" target="_blank">link</a></th>
    </tr>
    <tr>
<table>

## BCD datasets of multi-modal remote sensing images
<table>
<caption>
	<tr>
	    <th>Target of interest</th>
	    <th>Multimodal types</th>
	    <th>Datasets</th>
            <th>Year</th>	
	    <th>Image Pairs</th>
	    <th>Image size</th>	
	    <th>Resolution</th>
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="4">Flood</th>
    <th rowspan="3">Opt-SAR</th>
    <th>CAU-Flood dataset[<a href="https://doi.org/10.1016/j.jag.2023.103197" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>18302</th>
    <th>256×256</th>
    <th>10m</th>
    <th><a href="https://github.com/CAU-HE/CMCDNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>dataset3_Wuhan[<a href="https://doi.org/10.1016/j.jag.2022.102769" target="_blank">paper</a>]</th>
    <th>2022</th>
    <th>1</th>
    <th>11216×13693</th>
    <th>3m</th>
    <th><a href="https://github.com/GeoZcx/A-Domain-Adaption-Neural-Network-for-Change-Detection-with-Heterogeneous-Optical-and-SAR-Remote-Sens" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>Ombria dataset[<a href="https://ieeexplore.ieee.org/document/9723593" target="_blank">paper</a>]</th>
    <th>2022</th>
    <th>1688</th>
    <th>256×256</th>
    <th>10m</th>
    <th><a href="https://github.com/geodrak/OMBRIA" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="1">DEM-SAR</th>
    <th>Kuro Siwo[<a href="https://doi.org/10.48550/arXiv.2311.12056" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>67490</th>
    <th>224×224</th>
    <th>10m</th>
    <th><a href="https://github.com/Orion-AI-Lab/KuroSiwo" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="1">Land for construction</th>
    <th rowspan="1">Opt-Map</th>
    <th>EVLab-CMCD[<a href="https://doi.org/10.1016/j.isprsjprs.2024.10.010" target="_blank">paper</a>]</th>
    <th>2024</th>
    <th>5622</th>
    <th>512×512</th>
    <th>0.8m</th>
    <th><a href="https://github.com/whudk/EVLab-CMCD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="2">Building</th>
    <th rowspan="1">Opt-SAR</th>
    <th>BRIGHT[<a href="https://doi.org/10.48550/arXiv.2501.06019" target="_blank">paper</a>]</td>
    <th>2025</th>
    <th>4538</th>
    <th>1024×1024</th>
    <th>0.3-1m</th>
    <th><a href="https://github.com/ChenHongruixuan/BRIGHT" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="1">Opt-DSM</th>
    <th>Hi-BCD[<a href="https://doi.org/10.1016/j.inffus.2024.102358" target="_blank">paper</a>]</td>
    <th>2023</th>
    <th>1500</th>
    <th>1000×1000</th>
    <th>0.25m</th>
    <th><a href="https://github.com/HATFormer/MMCD" target="_blank">link</a></th>
    </tr>
     <tr>
<table>

## SCD datasets of optical remote sensing images 
<table>
<caption>
	<tr>
	    <th>Target of interest</th>
	    <th>Datasets</th>
            <th>Year</th>	
	    <th>Image Pairs</th>
	    <th>Image size</th>	
	    <th>Resolution</th>
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="13">Land cover</th>
    <th>CropSCD[<a href="https://doi.org/10.5194/isprs-annals-X-1-2024-75-2024" target="_blank">paper</a>]</th>
    <th>2024</th>
    <th>4141</th>
    <th>512×512</th>
    <th>0.5-2m</th>
    <th> <a href="https://github.com/lsmlyn/CropSCD" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>Hi-CNA dataset[<a href="https://doi.org/10.1016/j.isprsjprs.2024.05.011" target="_blank">paper</a>]</th>
    <th>2024</th>
    <th>6797</th>
    <th>512×512</th>
    <th>0.8m</th>
    <th> <a href="http://rsidea.whu.edu.cn/Hi-CNA_dataset.htm" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>ChangNet[<a href="https://doi.org/10.1109/ICASSP48485.2024.10446592" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>31000</th>
    <th>1900×1200</th>
    <th>0.3m</th>
    <th> <a href="https://github.com/jankyee/ChangNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>CNAM-CD[<a href="https://doi.org/10.3390/rs15092464" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>2503</th>
    <th>512×512</th>
    <th>0.5m</th>
    <th> <a href="https://github.com/Silvestezhou/CNAM-CD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>WUSU dataset[<a href="https://doi.org/10.1080/17538947.2023.2246445" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>3</th>
    <th>6358×6382/7025×5500</th>
    <th>1m</th>
    <th> <a href="http://rsidea.whu.edu.cn/resource_wusu_sharing.htm" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>DynamicEarthNet[<a href="https://openaccess.thecvf.com/content/CVPR2022/html/Toker_DynamicEarthNet_Daily_Multi-Spectral_Satellite_Dataset_for_Semantic_Change_Segmentation_CVPR_2022_paper.html" target="_blank">paper</a>]</th>
    <th>2022</th>
    <th>600</th>
    <th>1024×1024</th>
    <th>3m</th>
    <th> <a href="https://mediatum.ub.tum.de/1650201" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>Landsat-SCD[<a href="https://doi.org/10.1080/17538947.2022.2111470" target="_blank">paper</a>]</th>
    <th>2022</th>
    <th>8468</th>
    <th>416×416</th>
    <th>30m</th>
    <th><a href="https://figshare.com/articles/figure/Landsat-SCD_dataset_zip/19946135/1" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>S2MTCP[<a href="https://doi.org/10.1007/978-3-030-68787-8_42" target="_blank">paper</a>]</th>
    <th>2021</th>
    <th>1520</th>
    <th>600×600</th>
    <th>10m</th>
    <th><a href="https://zenodo.org/record/4280482" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>Hi-UCD[<a href="https://doi.org/10.48550/arXiv.2011.03247" target="_blank">paper</a>]</th>
    <th>2020</th>
    <th>1293</th>
    <th>1024×1024</th>
    <th>0.1m</th>
    <th><a href="https://github.com/Daisy-7/Hi-UCD-S" target="_blank">link</a></th>
    </tr>
    <tr>
    <th>SECOND[<a href="https://doi.org/10.1109/TGRS.2021.3113912" target="_blank">paper</a>]</th>
    <th>2020</th>
    <th>4662</th>
    <th>512×512</th>
    <th>-</th>
    <th><a href="https://captain-whu.github.io/SCD/" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>HRSCD[<a href="https://doi.org/10.1016/j.cviu.2019.07.003" target="_blank">paper</a>]</th>
    <th>2019</th>
    <th>291</th>
    <th>10000×10000</th>
    <th>0.5m</th>
    <th><a href="https://ieee-dataport.org/open-access/hrscd-high-resolution-semantic-change-detection-dataset" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>Mts-WH[<a href="https://doi.org/10.1109/TGRS.2016.2642125" target="_blank">paper</a>]</th>
    <th>2019</th>
    <th>1</th>
    <th>7200×6000</th>
    <th>1m</th>
    <th><a href="http://sigma.whu.edu.cn/newspage.php?q=2019_03_26" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>HCCD[<a href="https://doi.org/10.1109/IGARSS.2018.8518338" target="_blank">paper</a>]</th>
    <th>2018</th>
    <th>3</th>
    <th>390×200</th>
    <th>30m</th>
    <th>-</th>
    </tr>
     <tr>
    <caption>
    </tr>
     <tr>
    <th rowspan="4">Building</th>
    <th>BANDON[<a href="https://doi.org/10.1007/s11432-022-3691-4" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>2283</th>
    <th>2048×2048</th>
    <th>0.6m</th>
    <th><a href="https://github.com/fitzpchao/BANDON" target="_blank">link</a></th>
    </tr>
     <tr> 
    <th>NanjingDataset[<a href="https://doi.org/10.1016/j.isprsjprs.2022.05.001" target="_blank">paper</a>]</th>
    <th>2022</th>
    <th>2519</th>
    <th>256×256</th>
    <th>0.3m</th>
    <th><a href="https://github.com/SianGIS/NanjingDataset" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>QFabric[<a href="https://openaccess.thecvf.com/content/CVPR2021W/EarthVision/html/Verma_QFabric_Multi-Task_Change_Detection_Dataset_CVPRW_2021_paper.html" target="_blank">paper</a>]</th>
    <th>2021</th>
    <th>2520</th>
    <th>120×120-12000×12000</th>
    <th>0.31-0.7m</th>
    <th><a href="https://sagarverma.github.io/qfabric" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>S2Looking[<a href="https://doi.org/10.3390/rs13245094" target="_blank">paper</a>]</th>
    <th>2021</th>
    <th>5000</th>
    <th>1024×1024</th>
    <th>0.5-0.8m</th>
    <th><a href="https://github.com/S2Looking/Dataset" target="_blank">link</a></th>
    </tr>
     <tr>
<caption>
    <tr>
    <th rowspan="1">Landslide</th>
    <th>GVLM[<a href="https://doi.org/10.1016/j.isprsjprs.2023.01.018" target="_blank">paper</a>]</th>
    <th>2023</th>
    <th>17</th>
    <th>1748×1748-10808×7424</th>
    <th>0.59m</th>
    <th><a href="https://sagarverma.github.io/qfabric" target="_blank">link</a></th>
    </tr>
     <tr>
<table>


## SCD contest dataset for optical remote sensing images
<table>
<caption>
	<tr>
	    <th>Target of interest</th>
	    <th>Event</th>
            <th>Year</th>	
	    <th>Track</th>	
	    <th>Image Pairs</th>
	    <th>Image size</th>	
	    <th>Resolution</th>
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="5">Land cover</th>
    <th>2024 "Jilin-1" Cup Satel-lite Remote Sensing Application Youth Innovation and Entrepreneurship Competition</th>
    <th>2024</th>
    <th>High resolution remote sensing image total element change detection</th>
    <th>5000</th>    
    <th>512×512</th>
    <th><0.75m</th>
    <th> <a href="https://www.jl1mall.com/contest/matchMenu" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>"Jilin-1" Cup Satellite Remote Sensing Application Youth Innovation and Entrepreneurship Compe-tition</th>
    <th>2023</th>
    <th>Cultivated land change detection based on high-resolution satellite images</th>
    <th>8000</th>
    <th>256×256</th>
    <th><0.75m</th>
    <th><a href="https://www.jl1mall.com/contest/match">link</a></th>
    </tr>
     <tr>
    <th>Guofeng East Eye Cup" remote sensing image intelligent processing algorithm competition</th>
    <th>2023</th>
    <th>Object level change detection</th>
    <th rowspan="2">6000+</th>
    <th rowspan="2">512×512</th>    
    <th rowspan="2">1-2m</th>
    <th rowspan="2"><a href="http://rsipac.whu.edu.cn/">link</a></th>
    </tr>
     <tr>
    <th>"Space Map Cup" remote sensing image intelligent processing algorithm competition</th>
    <th>2022</th>
    <th>Remote sensing image change detection</th>
    </tr>
     <tr>
    <th>National Artificial Intelligence Competition</th>
    <th>2020</th>
    <th>AI + Remote sensing track</th>
    <th>-</th>
    <th>256×256</th>
    <th>-</th>
    <th><a href="https://naic.pcl.ac.cn/landingpage/2020/index.html">link</a></th>
    </tr>
     <tr>
<caption>
    <tr>
    <th rowspan="3">Building</th>
    <th>"Remote Sensing Image Intelligent Interpretation Technology Challenge</th>
    <th>2021</th>
    <th>Building change detection in remote sensing images</th>
    <th>10000</th>
    <th>512×512</th>
    <th>-</th>
    <th><a href="https://captain-whu.github.io/PRCV2021_RS/tasks.html" target="_blank">link</a></th>
    </tr>
     <tr>	     
    <th>"Tianzhi Cup" artificial intelligence challenge</th>
    <th>2021</th>
    <th>Visible light image building intelligent change detection</th>
    <th>5000</th>
    <th>1024×1024</th>
    <th>0.5-0.7m</th>
    <th><a href="https://rsaicp.com/portal/contestList" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>xView2 Challenge</th>
    <th>2019</th>
    <th>Building Damage Assessment</th>
    <th>11034</th>
    <th>1024×1024</th>
    <th><0.8m</th>
    <th><a href="https://xview2.org/dataset" target="_blank">link</a></th>
    </tr>
     <tr>	     
    <th rowspan="1">Flood</th>
    <th>SpaceNet8: Flood Detection Challenge</th>
    <th>2022</th>
    <th>Flood Detection Challenge Using Multiclass Segmentation</th>
    <th>12</th>
    <th>1300×1300</th>
    <th>0.3-0.8m</th>
    <th><a href="https://spacenet.ai/sn8-challenge/" target="_blank">link</a></th>
    </tr>
     <tr>
    <table>


## CNN-based IB-DLCD methods
<table>
<caption>
	<tr>
	    <th>Category</th>
	    <th>Abbreviation</th>
            <th>Title</th>	
	    <th>Publication</th>	
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="4">Early fusion</th>
    <th>Res2-Unet[<a href="https://doi.org/10.1109/JSTARS.2022.3146430" target="_blank">paper</a>]</th>
    <th>Res2-Unet, a new deep architecture for building detection from high spatial resolution images</th>
    <th>JSTARS2022</th>
    <th> <a href="https://github.com/yubozuzu123/res2-unet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>FC-EF-Res[<a href="https://doi.org/10.1016/j.cviu.2019.07.003" target="_blank">paper</a>]</th>
    <th>Multitask learning for large-scale semantic change detection</th>
    <th>CVIU2019</th>
    <th> <a href="https://github.com/rcdaudt/fully_convolutional_change_detection" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>UNet++_MSOF[<a href="https://doi.org/10.3390/rs11111382" target="_blank">paper</a>]</th>
    <th>End-to-end change detection for high resolution satellite images using improved UNet++</th>
    <th>RS2019</th>
    <th> <a href="https://github.com/daifeng2016/End-to-end-CD-for-VHR-satellite-image" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>FC-EF[<a href="https://doi.org/10.1109/ICIP.2018.8451652" target="_blank">paper</a>]</th>
    <th>Fully convolutional siamese networks for change detection</th>
    <th>ICIP2018</th>
    <th> <a href="https://github.com/rcdaudt/fully_convolutional_change_detection" target="_blank">link</a></th>
    </tr>
     <tr>     
<caption>
    <tr>
    <th rowspan="10">Middle fusion</th>
    <th>DESNet[<a href="https://doi.org/10.1109/LGRS.2023.3310676" target="_blank">paper</a>]</th>
    <th>A Difference Enhanced Neural Network for Semantic Change Detection of Remote Sensing Images</th>
    <th>GRSL2023</th>
    <th>-</th>
    </tr>
     <tr>    
    <th>EGPNet[<a href="https://doi.org/10.1109/JSTARS.2023.3306274" target="_blank">paper</a>]</th>
    <th>Edge-Guided Parallel Network for VHR Remote Sensing Image Change Detection</th>
    <th>JSTARS2023</th>
    <th> <a href="https://github.com/Lvkyky/EGPNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>Bi-SRNet[<a href="https://doi.org/10.1109/TGRS.2022.3154390" target="_blank">paper</a>]</th>
    <th>Bi-temporal semantic reasoning for the semantic change detection in HR remote sensing images</th>
    <th>TGRS2022</th>
    <th> <a href="https://github.com/DingLei14/Bi-SRNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>P2V-CD[<a href="https://doi.org/10.1109/TIP.2022.3226418" target="_blank">paper</a>]</th>
    <th>Transition is a process: Pair-to-video change detection networks for very high resolution remote sensing images</th>
    <th>TIP2022</th>
    <th> <a href="https://github.com/Bobholamovic/CDLab" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>SMD-Net[<a href="https://doi.org/10.3390/rs14071580" target="_blank">paper</a>]</th>
    <th>SMD-Net: Siamese multi-scale difference-enhancement network for change detection in remote sensing</th>
    <th>RS2022</th>
    <th>-</th>
    </tr>
     <tr>
    <th>BASNet[<a href="https://doi.org/10.1109/LGRS.2021.3119885" target="_blank">paper</a>]</th>
    <th>BASNet: A Boundary-Aware Siamese Network for Accurate Remote-Sensing Change Detection</th>
    <th>GRSL2021</th>
    <th>-</th>
    </tr>
     <tr>
    <th>DSNet[<a href="https://doi.org/10.3390/rs13173394" target="_blank">paper</a>]</th>
    <th>Deep Siamese Networks Based Change Detection with Remote Sensing Images</th>
    <th>RS2021</th>
    <th>-</th>
    </tr>
     <tr>
    <th>SNUNet-CD[<a href="https://doi.org/10.1109/LGRS.2021.3056416" target="_blank">paper</a>]</th>
    <th>SNUNet-CD: A densely connected Siamese network for change detection of VHR images</th>
    <th>GRSL2021</th>
    <th> <a href="https://github.com/likyoo/Siam-NestedUNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>FC-Siam-conc[<a href="https://doi.org/10.1109/ICIP.2018.8451652" target="_blank">paper</a>]</th>
    <th rowspan="2">Fully convolutional siamese networks for change detection</th>
    <th rowspan="2">ICIP2018</th>
    <th rowspan="2"><a href="https://github.com/rcdaudt/fully_convolutional_change_detection" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>FC-Siam-diff[<a href="https://doi.org/10.1109/ICIP.2018.8451652" target="_blank">paper</a>]</th>
    </tr>
     <tr>     
<caption>
    <tr>
    <th rowspan="3">Late fusion</th>
    <th>RaSRNet[<a href="https://doi.org/10.1109/TIM.2023.3243680" target="_blank">paper</a>]</th>
    <th>RaSRNet: An end-to-end Relation-aware Semantic Reasoning Network for Change Detection in Optical Remote Sensing Images</th>
    <th>TIM2023</th>
    <th>-</th>
    </tr>
     <tr>	     
    <th>SGSLN[<a href="https://doi.org/10.1109/TGRS.2023.3327780" target="_blank">paper</a>]</th>
    <th>Exchanging Dual-Encoder–Decoder: A New Strategy for Change Detection With Semantic Guidance and Spatial Localization</th>
    <th>TGRS2023</th>
    <th> <a href="https://github.com/NJU-LHRS/offical-SGSLN" target="_blank">link</a></th>
    </tr>
     <tr> 
    <th>FCCDN[<a href="https://doi.org/10.1016/j.isprsjprs.2022.02.021" target="_blank">paper</a>]</th>
    <th>FCCDN: Feature constraint network for VHR image change detection</th>
    <th>JPRS2022</th>
    <th> <a href="https://github.com/chenpan0615/FCCDN_pytorch" target="_blank">link</a></th>
    </tr>
     <tr>
    <table>

## Attention-based IB-DLCD methods
|Abbreviation|Title|Publication|Website|
|:---:|:---:|:---:|:---:|
|**A2Net[[paper](https://doi.org/10.1109/TGRS.2023.3241436)]**|**Lightweight Remote Sensing Change Detection With Progressive Feature Aggregation and Supervised Attention**|**TGRS2023**|**[link](https://github.com/guanyuezhen/A2Net)**|
|**DMINet[[paper](https://doi.org/10.1109/TGRS.2023.3241257)]**|**Change detection on remote sensing images using dual-branch multilevel intertemporal network**|**TGRS2023**|**[link](https://github.com/ZhengJianwei2/DMINet)**|
|**GAS-Net[[paper](https://doi.org/10.1016/j.isprsjprs.2023.04.001)]**|**Global-aware siamese network for change detection on remote sensing images**|**JPRS2023**|**[link](https://github.com/xiaoxiangAQ/GAS-Net)**|
|**USSFC-Net[[paper](https://doi.org/10.1109/TGRS.2023.3261273)]**|**Ultralightweight Spatial–Spectral Feature Cooperation Network for Change Detection in Remote Sensing Images**|**TGRS2023**|**[link](https://github.com/SUST-reynole/USSFC-Net)**|
|**SNAFF[[paper](https://doi.org/10.1111/phor.12462)]**|**High‐resolution optical remote sensing image change detection based on dense connection and attention feature fusion network**|**PHOR2023**|**_**|
|**DMSANet[[paper](https://doi.org/10.3390/rs14215405)]**|**Building Change Detection in Remote Sensing Images Based on Dual Multi-Scale Attention**|**RS2022**|**_**|
|**ISNet[[paper](https://doi.org/10.1109/TGRS.2022.3174276)]**|**ISNet: Towards Improving Separability for Remote Sensing Image Change Detection**|**TGRS2022**|**[link](https://github.com/xingronaldo/ISNet)**|
|**AGCDetNet[[paper](https://doi.org/10.1109/JSTARS.2021.3077545)]**|**AGCDetNet: An attention-guided network for building change detection in high-resolution remote sensing images**|**JSTARS2021**|**_**|
|**ADS-Net[[paper](https://doi.org/10.1016/j.jag.2021.102348)]**|**ADS-Net: An Attention-Based deeply supervised network for remote sensing image change detection**|**JAG2021**|**_**|
|**SSA-SiamNet[[paper](https://doi.org/10.1109/TGRS.2021.3095899)]**|**SSA-SiamNet: Spectral–spatial-wise attention-based Siamese network for hyperspectral image change detection**|**TGRS2021**|**_**|
|**MSPSNet[[paper]( https://doi.org/10.1109/TGRS.2021.3131993)]**|**Deep Multiscale Siamese Network With Parallel Convolutional Structure and Self-Attention for Change Detection**|**TGRS2021**|**_**|
|**DTCDSCN[[paper](https://doi.org/10.1109/LGRS.2020.2988032)]**|**Building change detection for remote sensing images using a dual-task constrained deep siamese convolutional network model**|**GRSL2020**||**[link](https://github.com/fitzpchao/DTCDSCN)**|
|**IFN[[paper](https://doi.org/10.1016/j.isprsjprs.2020.06.003)]**|**A deeply supervised image fusion network for change detection in high resolution bi-temporal remote sensing images**|**JPRS2020**|[link](https://github.com/GeoZcx/A-deeply-supervised-image-fusion-network-for-change-detection-in-remote-sensing-images)|
|**STANet[[paper](https://doi.org/10.3390/rs12101662)]**|**A spatial-temporal attention-based method and a new dataset for remote sensing image change detection**|**RS2020**|**[link](https://github.com/justchenhao/STANet)**|

## Transformer-based IB-DLCD methods
|Abbreviation|Title|Publication|Website|
|:---:|:---:|:---:|:---:|
|**BiFA[[paper](https://doi.org/10.1109/TGRS.2024.3376673)]**|**Bifa: Remote sensing image change detection with bitemporal feature alignment**|**TGRS2024**|**[link](https://github.com/zmoka-zht/BiFA)**|
|**CDMamba[[paper](https://doi.org/10.48550/arXiv.2406.04207)]**|**CDMamba: Remote Sensing Image Change Detection with Mamba**|**ArXiv2024**|**[link](https://github.com/zmoka-zht/CDMamba)**|
|**CDMask[[paper](https://doi.org/10.48550/arXiv.2406.15320)]**|**Rethinking Remote Sensing Change Detection With A Mask View**|**ArXiv2024**|**[link](https://github.com/xwmaxwma/rschange)**|
|**Changemamba[[paper](https://doi.org/10.48550/arXiv.2404.03425)]**|**Changemamba: Remote sensing change detection with spatio-temporal state space model**|**ArXiv2024**|**[link](https://github.com/ChenHongruixuan/MambaCD)**|
|**MaskCD[[paper](https://doi.org/10.48550/arXiv.2404.12081)]**|**MaskCD: A Remote Sensing Change Detection Network Based on Mask Classification**|**ArXiv2024**|**[link](https://github.com/AI4RS/MaskCD)**|
|**M-CD[[paper](https://doi.org/10.48550/arXiv.2407.06839)]**|**A Mamba-based Siamese Network for Remote Sensing Change Detection**|**ArXiv2024**|**[link](https://github.com/JayParanjape/M-CD)**|
|**SBA-PN[[paper](https://doi.org/10.1109/JSTARS.2024.3373753)]**|**Siamese Bi-Attention Pooling Network for Change Detection in Remote Sensing**|**JSTARS2024**|**_**|
|**ScratchFormer[[paper](https://doi.org/10.1109/TGRS.2024.3383800)]**|**Remote sensing change detection with transformers trained from scratch**|**TGRS2024**|**[link](https://github.com/mustansarfiaz/ScratchFormer)**|
|**MDAFormer[[paper](https://doi.org/10.1016/j.jag.2023.103256)]**|**MDAFormer: Multi-level difference aggregation transformer for change detection of VHR optical imagery**|**JAG2023**|**_**|
|**TransY-Net[[paper](https://doi.org/10.1109/TGRS.2023.3327253)]**|**TransY-Net: Learning Fully Transformer Networks for Change Detection of Remote Sensing Images**|**TGRS2023**|**[link](https://github.com/Drchip61/TransYNet)**|
|**ChangeFormer[[paper](https://doi.org/10.1109/IGARSS46834.2022.9883686)]**|**A transformer-based siamese network for change detection**|**IGARSS2022**|**[link](https://github.com/wgcban/ChangeFormer)**|
|**FTN[[paper](https://openaccess.thecvf.com/content/ACCV2022/html/Yan_Fully_Transformer_Network_for_Change_Detection_of_Remote_Sensing_Images_ACCV_2022_paper.html)]**|**Fully transformer network for change detection of remote sensing images**|**ACVV2022**|**[link](https://github.com/AI-Zhpp/FTN)**|
|**Pyramid-SCDFormer[[paper](https://doi.org/10.1080/17538947.2022.2111470)]**|**A transformer-based Siamese network and an open optical dataset for semantic change detection of remote sensing images**|**JDE2022**|**_**|
|**SST-Former[[paper](https://doi.org/10.1109/TGRS.2022.3203075)]**|**Spectral–spatial–temporal transformers for hyperspectral image change detection**|**TGRS2022**|**[link](https://github.com/yanhengwang-heu/IEEE_TGRS_SSTFormer)**|
|**SwinSUNet[[paper](https://doi.org/10.1109/TGRS.2022.3160007)]**|**SwinSUNet: Pure transformer network for remote sensing image change detection**|**TGRS2022**|**_**|
|**TMFF[[paper](https://doi.org/10.1117/1.JRS.16.046509)]**|**Transformer-based multi-scale feature fusion network for remote sensing change detection**|**JRS2022**|**_**|
|**TransUNetCD[[paper](https://doi.org/10.1109/TGRS.2022.3169479)]**|**TransUNetCD: A hybrid transformer network for change detection in optical remote-sensing images.**|**TGRS2022**|**_**|


## CNN-Transformer hybrid-based IB-DLCD methods
<table>
<caption>
	<tr>
	    <th>Category</th>
	    <th>Abbreviation</th>
            <th>Title</th>	
	    <th>Publication</th>	
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="5">Sequential integration</th>
    <th>GCFormer[<a href="https://doi.org/10.1109/TGRS.2024.3381738" target="_blank">paper</a>]</th>
    <th>GCFormer: Global Context-aware Transformer for Remote Sensing Image Change Detection</th>
    <th>TGRS2024</th>
    <th> <a href="https://github.com/yuwanting828/GCFormer" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>MSCANet[<a href="https://doi.org/10.1109/JSTARS.2022.3177235" target="_blank">paper</a>]</th>
    <th>A CNN-transformer network with multiscale context aggregation for fine-grained cropland change detection</th>
    <th>JSTARS2022</th>
    <th> <a href="https://github.com/liumency/CropLand-CD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>UVACD[<a href="https://doi.org/10.3390/rs14092228" target="_blank">paper</a>]</th>
    <th>A network combining a transformer and a convolutional neural network for remote sensing image change detection</th>
    <th>RS2022</th>
    <th>-</th>
    </tr>
     <tr>     
    <th>BIT[<a href="https://doi.org/10.1109/TGRS.2021.3095166" target="_blank">paper</a>]</th>
    <th>Remote sensing image change detection with transformers</th>
    <th>TGRS2021</th>
    <th> <a href="https://github.com/justchenhao/BIT_CD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>MTCNet[<a href="https://doi.org/10.1109/JSTARS.2022.3198517" target="_blank">paper</a>]</th>
    <th>A CBAM based multiscale transformer fusion approach for remote sensing image change detection</th>
    <th>TGRS2021</th>
    <th>-</th>
    </tr>
     <tr>	     
    <th rowspan="2">Multi-path CNN integration</th>
    <th>SCanNet[<a href="https://doi.org/10.1109/TGRS.2024.3362795" target="_blank">paper</a>]</th>
    <th>Joint spatio-temporal modeling for semantic change detection in remote sensing images</th>
    <th>TGRS2024</th>
    <th> <a href="https://github.com/DingLei14/SCanNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>DMATNet[<a href="https://doi.org/10.1109/TGRS.2022.3209972" target="_blank">paper</a>]</th>
    <th>Multi-path CNN integration**|**Remote sensing image change detection transformer network based on dual-feature mixed attention</th>
    <th>TGRS2022</th>
    <th>-</th>
    </tr>
     <tr>     
    <th rowspan="3">Parallel integration</th>
    <th>WNet[<a href="https://doi.org/10.1109/TGRS.2023.3296383" target="_blank">paper</a>]</th>
    <th>Wnet: W-shaped hierarchical network for remote sensing image change detection</th>
    <th>TGRS2023</th>
    <th> <a href="https://github.com/TangXu-Group/Remote-Sensing-Image-Change-Detection/tree/main/WNet" target="_blank">link</a></th>
    </tr>
     <tr>     
    <th>ACABFNet[<a href="https://doi.org/10.1109/JSTARS.2022.3224081" target="_blank">paper</a>]</th>
    <th>Axial cross attention meets CNN: Bibranch fusion network for change detection</th>
    <th>JSTARS2022</th>
    <th> <a href="https://github.com/SONGLEI-arch/ACABFNet" target="_blank">link</a></th>
    </tr>
     <tr>	     
    <th>ICIF-Net[<a href="https://doi.org/10.1109/TGRS.2022.3168331" target="_blank">paper</a>]</th>
    <th>ICIF-Net: Intra-scale cross-interaction and inter-scale feature fusion network for bitemporal remote sensing images change detection</th>
    <th>TGRS2022</th>
    <th> <a href="https://github.com/ZhengJianwei2/ICIF-Net" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="7">Unilateral mixing</th>
    <th>ConvTransNet[<a href="https://doi.org/10.1109/TGRS.2023.3272694" target="_blank">paper</a>]</th>
    <th>ConvTransNet: A CNN-Transformer Network for Change Detection with Multi-Scale Global-Local Representations</th>
    <th>TGRS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>CTD-Former[<a href="https://doi.org/10.1109/TGRS.2023.3281711" target="_blank">paper</a>]</th>
    <th>Relation Changes Matter: Cross-Temporal Difference Transformer for Change Detection in Remote Sensing Images</th>
    <th>TGRS2023</th>
    <th> <a href="https://github.com/RSMagneto/CTD-Former" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>DAHT-Net[<a href="https://doi.org/10.1109/ACCESS.2023.3307642" target="_blank">paper</a>]</th>
    <th>DAHT-Net: Deformable Attention-Guided Hierarchical Transformer Network Based on Remote Sensing Image Change Detection</th>
    <th>ACCESS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>GateFormer[<a href="https://doi.org/10.1109/JSTARS.2023.3335281" target="_blank">paper</a>]</th>
    <th>GateFormer: Gate Attention UNet With Transformer for Change Detection of Remote Sensing Images</th>
    <th>JSTARS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>GeoFormer[<a href="https://doi.org/10.1109/TGRS.2023.3331751" target="_blank">paper</a>]</th>
    <th>GeoFormer: A Geometric Representation Transformer for Change Detection</th>
    <th>TGRS2023</th>
    <th> <a href="https://github.com/Jiaxzhao/GeoFormer" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>SMNet[<a href="https://doi.org/10.3390/rs15040949" target="_blank">paper</a>]</th>
    <th>SMNet: symmetric multi-task network for semantic change detection in remote sensing images based on CNN and transformer</th>
    <th>RS2023</th>
    <th>-</th>
    </tr>
     <tr> 
    <th>SUT[<a href="https://doi.org/10.3390/rs15225383" target="_blank">paper</a>]</th>
    <th>A Full-Scale Connected CNN–Transformer Network for Remote Sensing Image Change Detection</th>
    <th>RS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th rowspan="4">Bilateral mixing</th>
    <th>ACAHNet[<a href="https://doi.org/10.1109/TGRS.2023.3245674" target="_blank">paper</a>]</th>
    <th>Asymmetric cross-attention hierarchical network based on CNN and transformer for bitemporal remote sensing images change detection</th>
    <th>TGRS2023</th>
    <th>-</th>
    </tr>
     <tr>     
    <th>DMMSTNet[<a href="https://doi.org/10.3390/rs15030842" target="_blank">paper</a>]</th>
    <th>Remote Sensing Image Change Detection Based on Deep Multi-Scale Multi-Attention Siamese Transformer Network</th>
    <th>RS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>TChange[<a href="https://doi.org/10.3390/rs15051219" target="_blank">paper</a>]</th>
    <th>TChange: A Hybrid Transformer-CNN Change Detection Network</th>
    <th>RS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>H-TransCD[<a href="https://doi.org/10.3390/ijgi11040263" target="_blank">paper</a>]</th>
    <th>Hybrid-transcd: A hybrid transformer remote sensing image change detection network via token aggregation</th>
    <th>JPRS2022</th>
    <th>-</th>
    </tr>
     <tr>
    <table>

## Label-efficient learning-based IB-DLCD methods
<table>
<caption>
	<tr>
	    <th>Method</th>
	    <th>Category</th>
	    <th>Abbreviation</th>
            <th>Title</th>	
	    <th>Publication</th>	
	    <th>Website</th>
	</tr>
    <tr>
    <th rowspan="16">Semi-supervised</th>
    <th rowspan="2">Adversarial learning</th>    
    <th>SemiCDNet[<a href="https://doi.org/10.1109/TGRS.2020.3011913" target="_blank">paper</a>]</th>
    <th>SemiCDNet: A semisupervised convolutional neural network for change detection in high resolution remote-sensing images</th>
    <th>TGRS2020</th>
    <th>-</th>
    </tr>
     <tr>
    <th>GDCN[<a href="https://doi.org/10.1109/JSTARS.2018.2887108" target="_blank">paper</a>]</th>
    <th>Adversarial learning**|**A generative discriminatory classified network for change detection in multispectral imagery</th>
    <th>JSTARS2019</th>
    <th>-</a></th>
    </tr>
     <tr>
    <th rowspan="5">Consistency constraints</th>    
    <th>C2F-SemiCD[<a href="https://doi.org/10.1109/TGRS.2024.3370568" target="_blank">paper</a>]</th>
    <th>C2F-SemiCD: A Coarse-to-Fine Semi-Supervised Change Detection Method Based on Consistency Regularization in High-Resolution Remote-Sensing Images</th>
    <th>TGRS2024</th>
    <th> <a href="https://github.com/ChengxiHAN/C2F-SemiCD-and-C2FNet" target="_blank">link</a></th>
    </tr>
     <tr>    
    <th>FPA[<a href="https://doi.org/10.1109/TGRS.2023.3247605" target="_blank">paper</a>]</th>
    <th>Semisupervised Change Detection With Feature-Prediction Alignment</th>
    <th>TGRS2023</th>
    <th> <a href="https://github.com/zxt9/FPA-SSCD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>Semi-LCD[<a href="https://doi.org/10.1080/15481603.2023.2257980" target="_blank">paper</a>]</th>
    <th>Consistency-guided lightweight network for semi-supervised binary change detection of buildings in remote sensing images</th>
    <th>GRS2023</th>
    <th>-</a></th>
    </tr>
     <tr>
    <th>SaDL[<a href="https://doi.org/10.1109/TGRS.2022.3203769" target="_blank">paper</a>]</th>
    <th>Semantic-aware dense representation learning for remote sensing image change detection</th>
    <th>TGRS2022</th>
    <th> <a href="https://github.com/justchenhao/SaDL_CD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>SemiCD[<a href="https://doi.org/10.48550/arXiv.2204.08454" target="_blank">paper</a>]</th>
    <th>Revisiting consistency regularization for semi-supervised change detection in remote sensing images</th>
    <th>ArXiv2022</th>
    <th> <a href="https://github.com/wgcban/SemiCD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="9">Pseudo-label learning</th>    
    <th>DCSS[<a href="https://doi.org/10.1109/TGRS.2024.3369059" target="_blank">paper</a>]</th>
    <th>Dynamically updated semi-supervised change detection network combining cross-supervision and screening algorithms</th>
    <th>TGRS2024</th>
    <th>-</th>
    </tr>
     <tr>
    <th>ECPS[<a href="https://doi.org/10.1109/TGRS.2024.3370236" target="_blank">paper</a>]</th>
    <th>ECPS: Cross Pseudo Supervision Based on Ensemble Learning for Semi-Supervised Remote Sensing Change Detection</th>
    <th>TGRS2024</th>
    <th> <a href="https://github.com/TangXu-Group/ECPS" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>STCRNet[<a href="https://doi.org/10.1109/JSTARS.2023.3345017" target="_blank">paper</a>]</th>
    <th>STCRNet: A Semi-Supervised Network Based on Self-Training and Consistency Regularization for Change Detection in VHR Remote Sensing Images</th>
    <th>JSTARS2023</th>
    <th> <a href="https://github.com/WangLukang/STCRNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>ST-RCL[<a href="https://doi.org/10.1109/TGRS.2023.3314452" target="_blank">paper</a>]</th>
    <th>Joint Self-training and Rebalanced Consistency Learning for Semi-supervised Change Detection</th>
    <th>TGRS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>SemiBuildingChange[<a href="https://doi.org/10.1109/TGRS.2023.3321637" target="_blank">paper</a>]</th>
    <th>SemiBuildingChange: A Semi-supervised High-Resolution Remote Sensing Image Building Change Detection Method With a Pseudo Bi-Temporal Data Generator</th>
    <th>TGRS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>SSCD[<a href="https://doi.org/10.1109/LGRS.2023.3311106" target="_blank">paper</a>]</th>
    <th>Pseudo-label learning**|**A New Semi-Supervised Method for Detecting Semantic Changes in Remote Sensing Images</th>
    <th>GRSL2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th>RCL[<a href="https://doi.org/10.1109/TGRS.2022.3228016" target="_blank">paper</a>]</th>
    <th>Reliable contrastive learning for semi-supervised change detection in remote sensing images</th>
    <th>TGRS2022</th>
    <th> <a href="https://github.com/VCISwang/RC-Change-Detection" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>SemiSANet[<a href="https://doi.org/10.3390/rs14122801" target="_blank">paper</a>]</th>
    <th>SemiSANet: A semi-supervised high-resolution remote sensing image change detection model using Siamese networks with graph attention</th>
    <th>RS2022</th>
    <th>-</th>
    </tr>
     <tr>
    <th>IAug_CDNet[<a href="https://doi.org/10.1109/TGRS.2021.3066802" target="_blank">paper</a>]</th>
    <th>Adversarial instance augmentation for building change detection in remote sensing images</th>
    <th>TGRS2021</th>
    <th> <a href="https://github.com/justchenhao/IAug_CDNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="2" and colspan ="2">Active learning</th>
    <th>DALCD[<a href="https://doi.org/10.48550/arXiv.2008.11201" target="_blank">paper</a>]</th>
    <th>Deep active learning in remote sensing for data efficient change detection</th>
    <th>ArXiv2020</th>
    <th>-</th>
    </tr>
     <tr>
    <th>CFSS-CD[<a href="https://doi.org/10.1109/TGRS.2018.2802785" target="_blank">paper</a>]</th>
    <th>A coarse-to-fine semi-supervised change detection for multispectral images</th>
    <th>TGRS2018</th>
    <th>-</th>
    </tr>
     <tr>
<caption>
    <tr>
    <th rowspan="9">Weakly-supervised</th>
    <th rowspan="1">Point-level labels</th>    
     <th>CARGNet[<a href="https://doi.org/10.1109/TGRS.2023.3348459" target="_blank">paper</a>]</th>
    <th>Point Label Meets Remote Sensing Change Detection: A Consistency-Aligned Regional Growth Network</th>
    <th>TGRS2023</th>
    <th> <a href="https://github.com/Wanderlust717/CARGNet" target="_blank">link</a></th>
    </tr>
     <tr>
    <th rowspan="2">Patch-level labels</th>    
    <th>MS-Former[<a href="https://doi.org/10.48550/arXiv.2311.09726" target="_blank">paper</a>]</th>
    <th>MS-Former: Memory-Supported Transformer for Weakly Supervised Change Detection with Patch-Level Annotations</th>
    <th>ArXiv2023</th>
    <th> <a href="https://github.com/guanyuezhen/MS-Former" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>SDCDNet<a href="https://doi.org/10.1109/TGRS.2023.3286113" target="_blank">paper</a>]</th>
    <th>SDCDNet: A Semi-Dual Change Detection Network Framework with Super-Weak Lable for Remote Sensing Image</th>
    <th>TGRS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th rowspan="5">Image-level labels</th>    
    <th>WSLCD[<a href="https://doi.org/10.1109/TGRS.2024.3379431" target="_blank">paper</a>]</th>
    <th>Beyond Pixel-Level Annotation: Exploring Self-Supervised Learning for Change Detection With Image-Level Supervision</th>
    <th>TGRS2024</th>
    <th> <a href="https://github.com/mfzhao1998/WSLCD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>BGMix[<a href="https://doi.org/10.1609/aaai.v37i7.25958" target="_blank">paper</a>]</th>
    <th>Background-mixed augmentation for weakly supervised change detection</th>
    <th>AAAI2023</th>
    <th> <a href="https://github.com/tsingqguo/bgmix" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>FCD-GAN[<a href="https://doi.org/10.1109/TPAMI.2023.3237896" target="_blank">paper</a>]</th>
    <th>Fully convolutional change detection framework with generative adversarial network for unsupervised, weakly supervised and regional supervised change detection</th>
    <th>TPAMI2023</th>
    <th> <a href="https://github.com/Cwuwhu/FCD-GAN-pytorch" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>TransWCD-DL[<a href="https://doi.org/10.48550/arXiv.2307.10853" target="_blank">paper</a>]</th>
    <th>Exploring Effective Priors and Efficient Models for Weakly-Supervised Change Detection</th>
    <th>ArXiv2023</th>
    <th> <a href="https://github.com/zhenghuizhao/TransWCD" target="_blank">link</a></th>
    </tr>
     <tr>
    <th>WSCD[<a href="https://doi.org/10.1109/JSTARS.2023.3279863" target="_blank">paper</a>]</th>
    <th>A Siamese Network Combining Multi-Scale Joint Supervision and Improved Consistency Regularization for Weakly Supervised Building Change Detection</th>
    <th>JSTARS2023</th>
    <th>-</th>
    </tr>
     <tr>
    <th rowspan="1">Low-resolution labels</th>    
    <th>RFWSCD[<a href="https://doi.org/10.1109/IGARSS47720.2021.9553768" target="_blank">paper</a>]</th>
    <th>Weakly supervised semantic change detection via label refinement framework</th>
    <th>IGARSS2021</th>
    <th>-</th>
    </tr>
     <tr>
    <table>

# Citation
Please cite our paper if you find it is useful for your research.
```
@article{PENG2025104282,
  title={Deep learning change detection techniques for optical remote sensing imagery: Status, perspectives and challenges},
  author={Peng, Daifeng, Liu, Xuelian, Zhang, Yongjun,  Guan, Haiyan,  Li, Yansheng and Bruzzone, Lorenzo},
  journal={International Journal of Applied Earth Observation and Geoinformation},
  volume={136},
  pages={104282},
  year={2025},
  publisher={Elsevier},
  issn = {1569-8432},
  doi = {https://doi.org/10.1016/j.jag.2024.104282},
  url = {https://www.sciencedirect.com/science/article/pii/S1569843224006381}
}
```
# Reference
- [wenhwu/awesome-remote-sensing-change-detection](https://github.com/wenhwu/awesome-remote-sensing-change-detection)
