# NERFBK: A HOLISTIC DATASET FOR BENCHMARKING NERF-BASED 3D RECONSTRUCTION
This is a repository of image collections - called NeRFBK - with real and synthetic data specifically assembled to support researchers in evaluating and comparing the performances of NeRF algorithms against a reliable and accurate Ground Truth (GT). 

The data contains:
- industrial objects (reflective and textureless metallic surfaces);
- transparent objects (mainly glasses);
- heritage scenarios (small and large scales, including lost scenes);
- large scale urban areas acquired with drone or airborne cameras. 

Researchers can compare NeRF methods on textured, textureless, metallic, transparent and aerial scenes to optimize and validate techniques for real-world use, such as in industrial inspections, cultural heritage preservation or large-scale urban 3D modeling.
For each dataset, GT data vary from LiDAR or Terrestrial Laser Scanning to high-resolution photogrammetry. Using these GT, quantitative evaluations can be performed to provide an unbiased comparison of geometric accuracy. Different approaches and metrics can include best plane fitting, cloud-to-cloud comparison, profiling, accuracy and completeness analyses, RMSE, etc. 
For each scenario, images and GT data can be downloaded from the given links.

If you use these data and you publish any result, please acknolwedge this repository and its related publications. Thanks!

------------
## Related Papers
- Gabriele Mazzacca, Ali Karami, Simone Rigon, Elisa Mariarosaria Farella, Pawel Trybala and Fabio Remondino, 2023: <a href="https://isprs-archives.copernicus.org/articles/XLVIII-M-2-2023/1051/2023/" target=page>NeRF FOR HERITAGE 3D RECONSTRUCTION</a>. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-M-2-2023, pp. 1051–1058
- Fabio Remondino, Ali Karami, Ziyang Yan, Gabriele Mazzacca, Simone Rigon and Rongjun Qin, 2023: <a href="https://www.mdpi.com/2072-4292/15/14/3585" target=page>A CRITICAL ANALYSIS OF NERF-BASED 3D RECONSTRUCTION</a>. Remote Sensing, Vol. 15(14), 3585
- Ziyang Yan, Gabriele Mazzacca, Simone Rigon, Elisa Mariarosaria Farella, Pawel Trybala, Fabio Remondino, 2023: <a href="https://isprs-archives.copernicus.org/articles/XLVIII-1-W3-2023/219/2023/" target=page>NERFBK: A HOLISTIC DATASET FOR BENCHMARKING NERF-BASED 3D RECONSTRUCTION</a>. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-1/W3-2023, 219–226

------------
## Datasets - Downloading available
<div style=”text-align: center;”>
  <table   style=”margin: auto;” width=’80%’>
  <thead>
    <tr>
      <th  width="8%"></th>
      <th  width="25%">Dataset</th>
      <th  width="22%">Numb. images</th>
      <th  width="20%">Camera type &<br>image size</th>
      <th  width="10%">Approx.<br>size(cm)</th>
      <th  width="25%">Description</th>
      <th  width="10%">Ground Truth<br>(GT)</th>
    </tr>
  </thead>
  <tbody> 
    <tr>
      <td rowspan="12", valign="top" ><strong>I<br>N<br>D<br>U<br>S<br>T<br>R<br>I<br>A<br>L</td>
      <td colspan="1",  align="center">Industrial_A</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ERVOA91ETFJNtw141SOr5zEBkfwsOpRMJxemXypER5TOaw?e=r18fho" target=page>295</a><br>(ca 200 MB)</td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">5x5x4</td>
      <td rowspan="3",  align="center">Textureless, <br>Small and Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EceGXlqG-r9MutbxfVhO-QgBHmpq5YdmCcjPjtheYEEqoA?e=ct4pQv" target=page>Triangulation laser scanner</a><br>(ca 171 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_A.png" height="111" width="130"></td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_A_network.png" height="111" width="130"></td>
    </tr>  
    <tr>
      <td colspan="1",  align="center">Industrial_B</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EW1YpnL-yn1DpzyjT-jK-WUBDmWhTwx4x7ZNTGxbMaElWw?e=tECFoQ" target=page">220</a></td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">15x12x4</td>
      <td rowspan="3",  align="center">Textureless, <br>Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EZJDReFkxVpElA6XViAO910BX7x2-nKfAooUIPXD-JYEXg?e=Uzi39b" target=page>Triangulation laser scanner</a><br>(ca 190 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_B.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_B_network.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Synthetic</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ERH-2pwnZGxCkKKDyvR7prIB1m6zq9Gng0K4p6VAmNRFrg?e=YwQXLX" target=page>373</a><br>(ca 250 MB)</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">11x11x2</td>
      <td rowspan="3",  align="center">Well-textured, <br>Sharp edges, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EbnFzNi39B1MpFKUZ7_mafcB0fltOlNguTbJa9wJFg3COw?e=PXRj8v" target=page>Synthetic data</a><br>(ca 1 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Synthetic.png?raw=True" height="73" width="130"> </td>
    </tr>
    <tr>
        <td align="center"><img src="./pictures/Industrial/Synthetic_network.png" height="73" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Synthetic_Metallic</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EXyAhh8BfJZJkIyWhDd_Z9EBi9tqJliFysiQthDv4-1eRw?e=HefNwq" target=page>300</a><br>(ca 750 MB)</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">16x16x13</td>
      <td rowspan="3",  align="center">Textureless, <br>Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EVKrneZ-EupCo1qSbqW1-AUBdM5DpS8tCEZAoIva2g1kDw?e=usJB6W" target=page>Synthetic data</a><br>(ca 10 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Syntethic_Metallic.png" height="130" width="130"></td>
    </tr>
    <tr>
        <td align="center"><img src="./pictures/Industrial/Synthetic_Metallic_network.png" height="130" width="130"></td>
    </tr>
    <tr>
      <td rowspan="12", valign="top"><strong>T<br>R<br>A<br>N<br>S<br>P<br>A<br>R<br>E<br>N<br>T<br><br>and<br><br>R<br>E<br>F<br>L<br>E<br>C<br>T<br>I<br>V<br>E</td>
      <td colspan="1",  align="center">Glass</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EVP3CFI_2zVFrz3XiCgHr2oBQnCW4C9UAFy0Ma8inRRjdw?e=BB77RW" target=page>552</a><br>(ca 380 MB)</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">5x5x25</td>
      <td rowspan="3",  align="center">Complex transparent shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EUAszNrfR2NJk9wQhz5xqTQBIg3n_AeFwnzlmSr-cifOzQ?e=2whLEQ" target=page>Photogrammetry on powdered surface</a><br>(ca 50 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Glass_A.png" height="130" width="128"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Glass_A_network.png" height="130" width="128"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Cup</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EaE1mT-aXyJNnqVCTHBG8eEBrCksNs1gPRkUD6R4ctZz3Q?e=7RoMrw" target=page>287</a></td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">8x8x10</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/r/sites/BENCHMARKS/Shared%20Documents/NeRFBK_datasets/Transparent/Cup/GT/Cup_GT.ply?csf=1&web=1&e=zqKL20" target=page>Photogrammetry</a><br>(ca 138 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Cup.png" height="130" width="93"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Cup_network.png" height="130" width="93"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Bottle</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/Ec7ASJPZ939Fmh3hXPnLUx4BW8T0h6O7gFJw0E7fzm2r5A?e=h1hTRd" target=page>300</a><br>(ca 200 MB)</td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">6x6x30</td>
      <td rowspan="3",  align="center">Complex shape, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EcRTm8FkdlpNr1ElWd66nQwBqG06sN9fPjF3BrABX2sQ1g?e=WEwvnF" target=page>Photogrammetry on powdered surface</a><br>(ca 290 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Transbottle.png" height="130" width="120"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Transbottle_network.png" height="130" width="120"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Synthetic_Glass</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EQgIlLqcpnNBgrXRtMYop1UB3-igKWdimCofK55FzbQDBg?e=fmg3GN" target=page>300</a><br>(ca 750 MB)</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">10x10x22</td>
      <td rowspan="3",  align="center">Transparent, <br>Highly refractive, <br>Video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EWXa8y1CzYJOtzKnk3aoSVYBs0UPBCuRdbYCa5SW1cqMtw?e=DayQYj" target=page>Synthetic data</a><br>(ca 6 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Synthetic_Glass_new.png" height="130" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Transparent/Synthetic_Glass_network.png" height="130" width="130"> </td>
    </tr>
    <tr>
      <td rowspan="30", valign="top"><strong>H<br>E<br>R<br>I<br>T<br>A<br>G<br>E</td>
      <td colspan="1",  align="center">Doss Trento</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EUz26UVqOBNPpAomuVvEYeUB3qM_IwOw545Ve9m5qBr49A?e=n3UdGu" target=page>761</a><br>(ca 150 MB)</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>540x960 px</td>
      <td rowspan="3",  align="center">2500x2500 <br>x1500</td>
      <td rowspan="3",  align="center">Outdoor large scale</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EXhX9Egfa39Isy9LpfqukEwBv_ORDte3SvMhZMsixmbGfw?e=NB97Xg" target=page>Terrestrial Laser Scanner</a><br>(ca 3 GB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Doss.png" height="112" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/doss_network.png" height="86" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Cyprus monument</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/Ef7PT12-NOBFsEJcN34jPLYBbEUH3hVsdD4HZ9WigPwRDg?e=c5V0cZ" target=page>178</a><br>(ca 100 MB)</td>
      <td rowspan="3",  align="center">Samsung S6, <br>3840x2160 px</td>
      <td rowspan="3",  align="center">1500x1500<br>x500</td>
      <td rowspan="3",  align="center">Outdoor large scale, video</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ETrVvtaAxABKtjk7nebla0MB4J-RxnnXi71Eb77OOPF9XA?e=hbzDAK" target=page>Photogrammetry with Reflex camera</a><br>(ca 500 MB)</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Cyprus.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Cyprus_network.png" height="34" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Statue</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EUtXOsDBN_BCvy5bXx_gs2gBoliC7UpD_LQxQLphQDZrgQ?e=UgxtqW" target=page>100</a><br>(ca 100 MB)</td>
      <td rowspan="3",  align="center">Ideal reflex camera, <br>6016x4016 px</td>
      <td rowspan="3",  align="center">200x100 <br>x500</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Two scales</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EVy9uWyQkfNEiRRTF1EvhkgBT_pJJ99hPuiXEVuiSOUNUQ?e=LRCeFJ" target=page>Synthetic data</a><br>(ca 2 MB)</td>
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
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ES0hNd8v-uRJqkvpu1akbPYBv6_VSJlm5Rd0zibrM8hSCw?e=ZuH9l1" target=page>565</a><br>(ca 4 GB)</td>
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
      <td rowspan="6",  valign="top"><strong>A<br>E<br>R<br>I<br>A<br>L</td>
      <td colspan="1",  align="center">Drone / UAV</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/Eenw6S17Hz9MrKjmzIJ-mAcBbCPhpZ9oEUtrZAyuj5mSSw?e=b75CBC" target=page>224</a><br>(ca 6 GB)</td>
      <td rowspan="3",  align="center">Sony, <br>7952x5304 px</td>
      <td rowspan="3",  align="center">City scale</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Built-up and vegetated areas</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/EVDn5GpfCwZJsTmnkuNgidwBkxrXukZqg4mQfo_4ZSewmQ?e=EquGJM">Airborne Laser Scanner<br>(ca 3 GB)</a></td>
    <tr>
      <td align="center"><img src="./pictures/Aerial/Drone.png" height="86" width="130"> </td>
    </tr>
     <tr>
      <td align="center"><img src="./pictures/Aerial/Drone_network.png" height="84" width="130"> </td>
     </tr>
    <tr>
      <td colspan="1",  align="center">Dortmund</td>
      <td rowspan="3",  align="center">59<br><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/Eax_wsvVHqhLlbpnX_SYxR0B8yxGpFm1MQ7uVHVjT_RUCQ?e=JIkDCX" target=page>cam0</a>
        <br>(ca 2GB),
        <br><a href="https://fbk.sharepoint.com/:u:/s/NerFBK/EYgksm7lO-NFlvViNr5vNVMBLAGeQ7mvKdeI8s0QOOs49A?e=xOUbX4">cam1</a>
        <br>(ca 1.8 GB),
        <br><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/Ed5ygUBvAUxNqk5BRanKZ2QBuRdfdxTp9oqVut3HpF5J1A?e=viSsb7" target=page>cam2</a>
        <br>(ca 1 GB),
        <br><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ESn-HVrI1cNAphWLTOdM7qEBZPfTVhjH6zf41YxNaDmfIw?e=aWmlr3" target=page>cam3</a>
        <br>(ca 1 GB),
        <br><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/Ee6ER_BfBaFNqSg--RHxzPQBrj0KaCR3h3eAHuInA9o4UQ?e=CBkoK6" target=page>cam4</a>
        <br>(ca 1 GB)</td>
      <td rowspan="3",  align="center">IGI Multi-sensor, 5 views <br>6132x8176 px at Nadir, 50 mm<br>8176x6132 px at Oblique, 80 mm</td>
      <td rowspan="3",  align="center">City scale</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Built-up and vegetated areas</td>
      <td rowspan="3",  align="center"><a href="https://fbk.sharepoint.com/:u:/s/BENCHMARKS/ESGlhZ1PH2JBpKGtMmcZsYEB2-9Pe8fcUMPpcS75D-_gjg?e=AHhpSp" target=page>Airborne Laser Scanner<br>(ca 220 MB)</a></td>
    <tr>
      <td align="center"><img src="./pictures/Aerial/aerial.png" height="97" width="130"> </td>
    </tr>
     <tr>
      <td align="center"><img src="./pictures/Aerial/Aerial_network.png" height="116" width="130"> </td>
     </tr>

  </tbody>
  </table>
</div>

------------
NeRFBK was created by the [3D Optical Metrology unit (3DOM)](https://3dom.fbk.eu/) of Fondazione Bruno Kessler (FBK).

* The Statue set of images is part of the ENRICH dataset, available here: https://github.com/davidemarelli/ENRICH<br>
Davide Marelli, Luca Morelli, Elisa Mariarosaria Farella, Simone Bianco, Gianluigi Ciocca, Fabio Remondino, 2023: <a href="https://www.sciencedirect.com/science/article/abs/pii/S0924271623000539">ENRICH: multi-purposE dataset for beNchmaRking In Computer vision and pHotogrammetry</a>. ISPRS Journal of Photogrammetry and Remote Sensing, Volume 198, Pages 84-98.

* The UAV set of images is part of the USEGEO project, available here: <a href="https://usegeo.fbk.eu">https://usegeo.fbk.eu</a>

* The Dortmund set of images is part of the ISPRS/EuroSDR Benchmark for Multi-Platform Photogrammetry, available here: <a href="https://www2.isprs.org/commissions/comm2/icwg-2-1a/benchmark_main/">https://www2.isprs.org/commissions/comm2/icwg-2-1a/benchmark_main/</a><br>
Nex, F., Gerke, M., Remondino, F., Przybilla H.-J., Bäumker, M., Zurhorst, A., 2015: <a href="https://isprs-annals.copernicus.org/articles/II-3-W4/135/2015/isprsannals-II-3-W4-135-2015.pdf">ISPRS Benchmark for Multi-Platform Photogrammetry</a>. ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Vol. II-3/W4, pp.135-142.

------------
## License
The data provided here is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---
## <a name="changelog"></a> Changelog 
* [15 Jul, 2023] Uploaded all datasets
* [26 Jul, 2023] Text and links fixing
* [20 Oct, 2023] Link to papers added

