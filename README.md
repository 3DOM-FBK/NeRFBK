# NERFBK: A HOLISTIC DATASET FOR BENCHMARKING NERF-BASED 3D RECONSTRUCTION
This is a repository of image collections - called NeRFBK - with real and synthetic data specifically assembled to support researchers in evaluating and comparing the performances of NeRF algorithms against a reliable and accurate Ground Truth (GT). 
The data contains industrial objects (reflective and textureless metallic surfaces), transparent objects (mainly glasses), heritage scenarios (including lost scenes), as well as large-scale urban areas acquired with drone or airborne cameras. 
Researchers can compare NeRF methods on textured, textureless, metallic, transparent and aerial scenes to optimize and validate techniques for real-world use, such as in industrial inspections, cultural heritage preservation or large-scale 3D modeling.
For each dataset, GT data vary from LiDAR or Terrestrial Laser scanning to high-resolution photogrammetry. Using these GT, quantitative evaluations can be performed to provide an unbiased comparison of geometric accuracy. Different approaches and metrics can include best plane fitting, cloud-to-cloud comparison, profiling, accuracy and completeness analyses, RMSE, etc. 
For each scenario, images and GT data can be downloaded from the given links.

If you use these data and you publish any result, please acknolwedge this repository and its related publications. Thanks!


[**Related Papers**]
- Gabriele Mazzacca, Ali Karami, Simone Rigon, Elisa Mariarosaria Farella, Pawel Trybala and Fabio Remondino, 2023: <a href="https://isprs-archives.copernicus.org/articles/XLVIII-M-2-2023/1051/2023/" target=page>NeRF FOR HERITAGE 3D RECONSTRUCTION</a>. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-M-2-2023, pp. 1051–1058
- Fabio Remondino, Ali Karami, Ziyang Yan, Gabriele Mazzacca, Simone Rigon and Rongjun Qin, 2023: <a href="https://www.mdpi.com/2072-4292/15/14/3585" target=page>A CRITICAL ANALYSIS OF NERF-BASED 3D RECONSTRUCTION</a>. Remote Sensing, Vol. 15(14), 3585
- Ziyang Yan, Gabriele Mazzacca, Simone Rigon, Elisa Mariarosaria Farella, Pawel Trybala, Fabio Remondino, 2023: NERFBK: A HOLISTIC DATASET FOR BENCHMARKING NERF-BASED 3D RECONSTRUCTION. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., forthcoming / in preparation


## <a name="Datasets"></a> Datasets - Downloading coming soon!
<div style=”text-align: center;”>
  <table   style=”margin: auto;” width=’40%’>
  <thead>
    <tr>
      <th  width="10%"></th>
      <th  width="40%">Dataset</th>
      <th  width="10%">Numb. images</th>
      <th  width="20%">Camera type &<br>image size</th>
      <th  width="10%">Approx.<br>size(cm)</th>
      <th  width="20%">Description</th>
      <th  width="10%">Ground Truth<br>(GT)</th>
    </tr>
  </thead>
  <tbody> 
    <tr>
      <td rowspan="15",  align="center" ><strong>Industrial</td>
      <td colspan="1",  align="center">Industrial_A</td>
      <td rowspan="3",  align="center">295</td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">5x5x4</td>
      <td rowspan="3",  align="center">Textureless, <br>Small and Complex, <br>Reflective, <br>Two acquisitions, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ES-5jysUwX5GmbdEOvzc4KsBc5qi-Dpu62pVq14Xwq2f3Q?e=gGQIo9" target=page>Triangulation laser scanner</a><br>(ca 50 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_A.png" height="111" width="130"></td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_A_network.png" height="111" width="130"></td>
    </tr>  
    <tr>
      <td colspan="1",  align="center">Industrial_B</td>
      <td rowspan="3",  align="center">220</td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">15x12x4</td>
      <td rowspan="3",  align="center">Textureless, <br>Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center">Triangulation scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_B.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_B_network.png" height="99" width="130"> </td>
    </tr>
    <tr>
    <tr>
      <td colspan="1",  align="center">Synthetic</td>
      <td rowspan="3",  align="center">373</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">11x11x2</td>
      <td rowspan="3",  align="center">Well-textured, <br>Complex, <br>Video</td>
      <td rowspan="3",  align="center">Synthetic data</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Synthetic.png?raw=True" height="73" width="130"> </td>
    </tr>
    <tr>
        <td align="center"><img src="./pictures/Industrial/Synthetic_network.png" height="73" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Synthetic_Metallic</td>
      <td rowspan="3",  align="center">300</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">16x16x13</td>
      <td rowspan="3",  align="center">Textureless, <br>Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center">Synthetic data</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Syntethic_Metallic.png" height="130" width="130"></td>
    </tr>
    <tr>
        <td align="center"><img src="./pictures/Industrial/Synthetic_Metallic_network.png" height="130" width="130"></td>
    </tr>
    <tr>
      <td rowspan="15",  align="center"><strong>Transparent</td>
      <td colspan="1",  align="center">Glass_A</td>
      <td rowspan="3",  align="center">552</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">5x5x25</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Glass_A.png" height="130" width="128"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Glass_A_network.png" height="130" width="128"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Glass_B</td>
      <td rowspan="3",  align="center">377</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">6x6x10</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Glass_B.png" height="111" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Glass_B_network.png" height="111" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Cup</td>
      <td rowspan="3",  align="center">338</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">8x8x10</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Cup.png" height="130" width="93"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Cup_network.png" height="130" width="93"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Transbottle</td>
      <td rowspan="3",  align="center">300</td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">6x6x30</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Transbottle.png" height="130" width="120"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Transbottle_network.png" height="130" width="120"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Synthetic_Glass</td>
      <td rowspan="3",  align="center">300</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">10x10x22</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center">Synthetic data</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Syntethic_Glass.png" height="130" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Synthetic_Glass_network.png" height="130" width="130"> </td>
    </tr>
    <tr>
      <td rowspan="30",  align="center"><strong>Heritage</td>
      <td colspan="1",  align="center">Doss Trento</td>
      <td rowspan="3",  align="center">761</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">2500x2500 <br>x1500</td>
      <td rowspan="3",  align="center">Outdoor large scale</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Doss.png" height="112" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/doss_network.png" height="86" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Cyprus monument</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EZMbbYGAaWtLjUDTPa3xDeEBsY9BMJryLRVGR2CIClTx0w?e=XHv4av" target=page>2942</a><br>(ca 900 MB)</td>
      <td rowspan="3",  align="center">Samsung S6, <br>3840x2160 px</td>
      <td rowspan="3",  align="center">1500x1500<br>x500</td>
      <td rowspan="3",  align="center">Outdoor large scale, video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/ETrVvtaAxABKtjk7nebla0MB4J-RxnnXi71Eb77OOPF9XA?e=XJ47hY" target=page>Photogrammetry with Reflex camera</a><br>(ca 500 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Cyprus.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Cyprus_network.png" height="34" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Statue</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/EUtXOsDBN_BCvy5bXx_gs2gBoliC7UpD_LQxQLphQDZrgQ?e=2DXpXu" target=page>100</a><br>(ca 100 MB)</td>
      <td rowspan="3",  align="center">Ideal reflex camera, <br>6016x4016 px</td>
      <td rowspan="3",  align="center">200x100 <br>x500</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Two cameras</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/EVy9uWyQkfNEiRRTF1EvhkgBT_pJJ99hPuiXEVuiSOUNUQ?e=aZD7F4"target=page>Synthetic data</a></td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Statue.png" height="104" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Statue_network.png" height="100" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Vase</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EXpwaA2mvcJNrtajEISiBdMBumqdHtBkAWZmpi0lYhwH6w?e=AOKeeD" target=page>50</a><br>(ca 1 GB)</td>
      <td rowspan="3",  align="center">Google Pixel2, <br>4024x3016 px</td>
      <td rowspan="3",  align="center">40x30</td>
      <td rowspan="3",  align="center">Indoor</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EXAlapxZPnxDuIp4wkJARx4BQZeJUMIOdi_txEuJBOvuCw?e=p48RCb" target=page>Photogrammetry with Reflex camera</a><br>(ca 500 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Vase.png" height="130" width="95"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Vase_network.png" height="95" width="95"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Metopa</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/ETDLzigIfktFj7MmRgPaL9MB3n7FUKzJgcRM2oNYvgikFQ?e=2g1nUw" target=page>106</a><br>(ca 500 MB)</td>
      <td rowspan="3",  align="center">Nikon COOLPIX P90, <br>4000x3000 px</td>
      <td rowspan="3",  align="center">100x80x10</td>
      <td rowspan="3",  align="center">Indoor museal detailed relief</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/EcJIDNW8oINGsJkI6XRfr8wB2tkp-05Q1El3aTd4UGrBrw?e=e3rVUC" target=page>Terrestrial Laser Scanner</a><br>(ca 800 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Metopa.png" height="70" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Metopa_network.png" height="82" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Tunnel</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EZlJda2V3SJMpzuI8mWuJoAB-6Zyzp_VpNWE0g2wRVohEg?e=fQBAc2" target=page>4353</a></td>
      <td rowspan="3",  align="center">RealSense D455, <br>640x480 px</td>
      <td rowspan="3",  align="center">8000x300 <br>x200</td>
      <td rowspan="3",  align="center">Underground, <br>Mobile robot based, <br> High frame-rate</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EVDolcU8esxFlSLcpQem6JABo01ZrXdzTBds5k3GIx6uWA?e=9lpdch" target=page>Terrestrial Laser Scanner</a><br>(ca 200 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Tunnel.png" height="127" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Tunnel_network.png" height="75" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Neptune temple</td>
      <td rowspan="3",  align="center">680<br>+ <br>214</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EaYJ7HQE59VEqQCqWJpUtIABGjbRNKqGa-VTEX1-1Kd_Xw?e=vr1fFy" target=page>Nikon D3X</a>, <br>6048x4032 px, <br><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EVyJxrzrSX5Frxuk4BdBgygBVMZ8xRUQBoV-yOiywEXpKg?e=PDCdP5" target=page>Canon EOS 550D</a>, <br> 5184x3456 px</td>
      <td rowspan="3",  align="center">2500x1500 <br>x7000</td>
      <td rowspan="3",  align="center">Terrestrial <br>+ <br>UAV images<br>Outdoor large scale</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EZ7a0BcDQUdBg_gIlGr0rSYBU3i-1vFxhzA0inJGXC8vFA?e=0AZb7B" target=page>Terrestrial Laser Scanner</a><br>(ca 50 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Neptune.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Neptune_network.png" height="80" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Trento Duomo</td>
      <td rowspan="3",  align="center"><a href="" target=page>565</a><br>(ca 4 GB)</td>
      <td rowspan="3",  align="center">Samsung S6, <br>5312x2988 px</td>
      <td rowspan="3",  align="center">8000x8000</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Terrestrial</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EaK8oBhSNrhIiNyvQ0X3qs8BbO9PNKQnidhSmXYU8DkQmA?e=5MCr9H" target=page>Photogrammetry with Reflex camera</a><br>(ca 2.6 GB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Duomo.png" height="74" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Duomo_network.png" height="86" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Modena cathedral</td>
      <td rowspan="3",  align="center">132 <br>+ <br>58</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EUisBmoBqGdIkyLPfUSNrBMB6pNEO0C_LcDDs4TTGTvOuA?e=cSGdqy" target=page>Nikon D750</a>,<br>6016x4016 px<br><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EbSBpKBNQARChkcKhqCCgFcBS48zEmOEpX6HdbsC7g9PaQ?e=jnmtwO" target=page>Canon EOS 600D</a>,<br>5184x3456 px</td>
      <td rowspan="3",  align="center">2500x2500</td>
      <td rowspan="3",  align="center">Terrestrial <br>+ <br>UAV images<br>Large scale architecture</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EcgXjXU_y4NGto79_nRfBtgBQq0AKqosULKiMyfhywXWhQ?e=mhjPNF" target=page>Terrestrial Laser Scanner</a><br>(ca 4.8 GB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Modena.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Modena_network.png" height="103" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Baalshamin temple</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/Ed3K5XJDBhdBtvtb21YdiNEBmwZfD5iHfE7m1UsYWbNVPw?e=bpdtcQ" target=page>47</a><br>(ca 100 MB)</td>
      <td rowspan="3",  align="center">Multiple cameras, <br>From 600x399 px<br>to<br>4288x2848 px</td>
      <td rowspan="3",  align="center">500x1500</td>
      <td rowspan="3",  align="center">Lost object, <br>Sub-optimal baselines, <br>Unordered touristic images, <br>Multiple resolutions</td>
      <td rowspan="3",  align="center">-</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Baalshamin.png" height="98" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Baalshamin_network.png" height="39" width="130"> </td>
    </tr>
    <tr>
      <td rowspan="6",  align="center"><strong>Aerial</td>
      <td colspan="1",  align="center">Drone / UAV</td>
      <td rowspan="3",  align="center"><a href="" target=page>224</a><br>(ca 6 GB)</td>
      <td rowspan="3",  align="center">Sony, <br>7952x5304 px</td>
      <td rowspan="3",  align="center">City scale</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Built-up and vegetated areas</td>
      <td rowspan="3",  align="center"><a href="">Airborne Laser Scanner<br>(ca 3 GB)</a></td>
    <tr>
      <td align="center"><img src="./pictures/Aerial/Drone.png" height="86" width="130"> </td>
    </tr>
     <tr>
      <td align="center"><img src="./pictures/Aerial/Drone_network.png" height="84" width="130"> </td>
     </tr>
    <tr>
      <td colspan="1",  align="center">Dortmund</td>
      <td rowspan="3",  align="center">59<br><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/Eax_wsvVHqhLlbpnX_SYxR0B8yxGpFm1MQ7uVHVjT_RUCQ?e=WTa9af" target=page>cam0</a><br>(ca 2GB),<br><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/EYgksm7lO-NFlvViNr5vNVMBLAGeQ7mvKdeI8s0QOOs49A?e=xOUbX4">cam1</a><br>(ca 1.8 GB),<br><a href="https://fbk.sharepoint.com/:u:/r/sites/NerFBK/Shared%20Documents/BENCHMARKS/NeRFBK_datasets/aerial/dortmund/Cam2.zip?csf=1&web=1&e=NyFIbq" target=page>cam2</a><br>(ca 1 GB),<br><a href="https://fbk.sharepoint.com/:u:/r/sites/NerFBK/Shared%20Documents/BENCHMARKS/NeRFBK_datasets/aerial/dortmund/Cam3.zip?csf=1&web=1&e=9gphce" target=page>cam3</a><br>(ca 1 GB),<br><a href="https://fbk.sharepoint.com/:u:/r/sites/NerFBK/Shared%20Documents/BENCHMARKS/NeRFBK_datasets/aerial/dortmund/Cam4.zip?csf=1&web=1&e=v9tmIH" target=page>cam4</a><br>(ca 1 GB)</td>
      <td rowspan="3",  align="center">IGI Multi-sensor, 5 views <br>6132x8176 px at Nadir, 50 mm<br>8176x6132 px at Oblique, 80 mm</td>
      <td rowspan="3",  align="center">City scale</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Built-up and vegetated areas</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/r/sites/NerFBK/Shared%20Documents/BENCHMARKS/NeRFBK_datasets/aerial/dortmund/Dortmund_LiDAR_GT.rar?csf=1&web=1&e=APRnF8" target=page>Airborne Laser Scanner<br>(ca 220 MB)</a></td>
    <tr>
      <td align="center"><img src="./pictures/Aerial/aerial.png" height="97" width="130"> </td>
    </tr>
     <tr>
      <td align="center"><img src="./pictures/Aerial/Aerial_network.png" height="116" width="130"> </td>
     </tr>
    </tr>
  </tbody>
  </table>
</div>

---


NeRFBK was created by the [3D Optical Metrology unit (3DOM)](https://3dom.fbk.eu/) of Fondazione Bruno Kessler (FBK).

The Statue set of images is part of the ENRICH dataset, available here: https://github.com/davidemarelli/ENRICH
ENRICH: multi-purposE dataset for beNchmaRking In Computer vision and pHotogrammetry
Davide Marelli, Luca Morelli, Elisa Mariarosaria Farella, Simone Bianco, Gianluigi Ciocca, Fabio Remondino, 2-23.
ISPRS Journal of Photogrammetry and Remote Sensing, Volume 198, Pages 84-98.

The UAV set of images is part of the USEGEO project, available here: https://usegeo.fbk.eu

The Dortmund set of images is part of the ISPRS/EuroSDR Benchmark for Multi-Platform Photogrammetry, available here: https://www2.isprs.org/commissions/comm2/icwg-2-1a/benchmark_main/
ISPRS Benchmark for Multi-Platform Photogrammetry.
Nex, F., Gerke, M., Remondino, F., Przybilla H.-J., Bäumker, M., Zurhorst, A., 2015. 
ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Vol. II-3/W4, pp.135-142.

## Citation

Please consider citing our work:

    @inproceedings{
    }

---
## <a name="changelog"></a> Changelog 
* [15 Jul, 2023] Uploaded newest version.
