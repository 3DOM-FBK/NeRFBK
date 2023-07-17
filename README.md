# NERFBK: A HOLISTIC DATASET FOR BENCHMARKING NERF-BASED 3D RECONSTRUCTION
This is a set of image collections - called NeRFBK - with real and synthetic data specifically assembled to support researchers in evaluating and comparing the performances of NeRF algorithms against a reliable and accurate Ground Truth. 
The data contains industrial objects (reflective and textureless metallic surfaces), transparent objects (mainly glasses), heritage scenarios (including lost scenes), as well as large-scale urban areas acquired with drone or airborne cameras. 
Researchers can compare NeRF methods on textured, textureless, metallic, transparent and aerial scenes to optimize and validate techniques for real-world use, such as in industrial inspections, cultural heritage preservation or large-scale 3D modeling.
For each dataset, camera poses are provided through a COLMAP project while Groud Truth data vary from LiDAR or Terrestrial Laser scanning to high-resolution photogrammetry. Using these Groud Truth, quantitative evaluations can be performed to provide an unbiased comparison of geometric accuracy. Different approaches and metrics can include best plane fitting, cloud-to-cloud comparison, profiling, accuracy and completeness analyses, RMSE, etc. 



[**[Paper]**]() [**[Download]**](#Download) 
---

## <a name="Datasets"></a> Datasets
<div style=”text-align: center;”>
  <table   style=”margin: auto;” width=’40%’>
  <thead>
    <tr>
      <th  width="10%"></th>
      <th  width="40%">Dataset</th>
      <th  width="10%">Numb. images</th>
      <th  width="20%">Camera type &<br>image size</th>
      <th  width="10%">Approx. <br>size(cm)</th>
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
      <td rowspan="3",  align="center">Hexagon active scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_A.png" height="111" width="130"></td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_A.png" height="111" width="130"></td>
    </tr>  
    <tr>
      <td colspan="1",  align="center">Industrial_B</td>
      <td rowspan="3",  align="center">220</td>
      <td rowspan="3",  align="center">Huawei p20 pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">15x12x4</td>
      <td rowspan="3",  align="center">Textureless, <br>Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center">Hexagon active scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_B.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_B.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Industrial_C</td>
      <td rowspan="3",  align="center">213</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px</td>
      <td rowspan="3",  align="center">7x7x14</td>
      <td rowspan="3",  align="center">Textureless, <br>Complex, <br>Reflective, <br>Video</td>
      <td rowspan="3",  align="center">Hexagon active scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_C.png" height="128" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Industrial_C.png" height="128" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Synthetic</td>
      <td rowspan="3",  align="center">373</td>
      <td rowspan="3",  align="center">Virtual pinhole camera, <br>1920x1080 px</td>
      <td rowspan="3",  align="center">11x11x2</td>
      <td rowspan="3",  align="center">Well-textured, <br>Complex, <br>Video</td>
      <td rowspan="3",  align="center">Synthetic data</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Industrial/Synthetic.png" height="73" width="130"> </td>
    </tr>
    <tr>
        <td align="center"><img src="./pictures/Industrial/Synthetic.png" height="73" width="130"> </td>
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
      <td align="center"><img src="./pictures/Industrial/Syntethic_Metallic.png?raw=true)" height="130" width="130"></td>
    </tr>
    <tr>
        <td align="center"><img src="./pictures/Industrial/Syntethic_Metallic.png?raw=true)" height="130" width="130"></td>
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
      <td align="center"><img src="./pictures/Transparent/Glass_A.png" height="130" width="128"> </td>
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
      <td align="center"><img src="./pictures/Transparent/Glass_B.png" height="111" width="130"> </td>
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
      <td align="center"><img src="./pictures/Transparent/Cup.png" height="130" width="93"> </td>
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
      <td align="center"><img src="./pictures/Transparent/Transbottle.png" height="130" width="120"> </td>
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
      <td align="center"><img src="./pictures/Transparent/Syntethic_Glass.png" height="130" width="130"> </td>
    </tr>
    <tr>
      <td rowspan="30",  align="center"><strong>Heritage</td>
      <td colspan="1",  align="center">Doss Trento</td>
      <td rowspan="3",  align="center">761</td>
      <td rowspan="3",  align="center">Huawei p20pro, <br>1080x1920 px<br> and <br>540x690 px</td>
      <td rowspan="3",  align="center">2500x2500 <br>x1500</td>
      <td rowspan="3",  align="center">Outdoor large scale</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Doss Trento.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Doss Trento.png" height="99" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Cyprus</td>
      <td rowspan="3",  align="center">176</td>
      <td rowspan="3",  align="center">Samsung S6, <br>3840x2160 px</td>
      <td rowspan="3",  align="center">1000x1000 <br>x500</td>
      <td rowspan="3",  align="center">Outdoor large scale</td>
      <td rowspan="3",  align="center">Photogrammetry with Reflex camera</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Cyprus.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Cyprus.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Statue</td>
      <td rowspan="3",  align="center">100</td>
      <td rowspan="3",  align="center">Ideal reflex camera, <br>6016x4016 px</td>
      <td rowspan="3",  align="center">200x100 <br>x500</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Two cameras</td>
      <td rowspan="3",  align="center">Synthetic data</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Statue.png" height="104" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Statue.png" height="104" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Vase</td>
      <td rowspan="3",  align="center">50</td>
      <td rowspan="3",  align="center">Google Pixel2, <br>4024x3016 px</td>
      <td rowspan="3",  align="center">30x30</td>
      <td rowspan="3",  align="center">Indoor</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner, <br> Photogrammetry with Reflex camera</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Vase.png" height="130" width="95"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Vase.png" height="130" width="95"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Metopa</td>
      <td rowspan="3",  align="center">106</td>
      <td rowspan="3",  align="center">Nikon COOLPIX P90, <br>4000x3000 px</td>
      <td rowspan="3",  align="center">100x80x10</td>
      <td rowspan="3",  align="center">Indoor museal detailed relief</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Metopa.png" height="70" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Metopa.png" height="70" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Tunnel</td>
      <td rowspan="3",  align="center">4353</td>
      <td rowspan="3",  align="center">RealSense D455, <br>640x480 px</td>
      <td rowspan="3",  align="center">8000x300 <br>x200</td>
      <td rowspan="3",  align="center">Underground, <br>Mobile robot based, <br> High framerate</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Tunnel.png" height="127" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Tunnel.png" height="127" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Neptune</td>
      <td rowspan="3",  align="center">680 <br>+ <br>214</td>
      <td rowspan="3",  align="center">Nikon D3X, <br>6048x4032 px, <br>Canon EOS 550D, <br> 5184x3456 px</td>
      <td rowspan="3",  align="center">2500x1500 <br>x7000</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Terrestrial <br>+ <br>UAV images</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Neptune.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Neptune.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Duomo</td>
      <td rowspan="3",  align="center">565</td>
      <td rowspan="3",  align="center">Samsung S6, <br>5312x2988 px</td>
      <td rowspan="3",  align="center">8000x8000</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Terrestrial</td>
      <td rowspan="3",  align="center"></td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Duomo.png" height="74" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Duomo.png" height="74" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Modena</td>
      <td rowspan="3",  align="center">134 <br>+ <br>87</td>
      <td rowspan="3",  align="center">Nikon D3X, <br>6048x4032 px</td>
      <td rowspan="3",  align="center">2500x2500</td>
      <td rowspan="3",  align="center">Terrestrial <br>+ <br>UAV images</td>
      <td rowspan="3",  align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Modena.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Modena.png" height="87" width="130"> </td>
    </tr>
    <tr>
      <td colspan="1",  align="center">Baalshamin</td>
      <td rowspan="3",  align="center">47</td>
      <td rowspan="3",  align="center">Multiple cameras, <br>From 600x399 px<br>to<br>4288x2848 px</td>
      <td rowspan="3",  align="center">500x1500</td>
      <td rowspan="3",  align="center">Lost object, <br>Sub-optimal baselines, <br>Unordered touristic images, <br>Multiple resolutions</td>
      <td rowspan="3",  align="center"></td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Baalshamin.png" height="98" width="130"> </td>
    </tr>
    <tr>
      <td align="center"><img src="./pictures/Heritage/Baalshamin.png" height="98" width="130"> </td>
    </tr>
    <tr>
      <td rowspan="6",  align="center"><strong>Aerial</td>
      <td colspan="1",  align="center">Drone</td>
      <td rowspan="3",  align="center">328</td>
      <td rowspan="3",  align="center">Sony, <br>7952x5304 px</td>
      <td rowspan="3",  align="center">City scale</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Built-up and vegetated areas</td>
      <td rowspan="3",  align="center">Airborne Laser Scanner</td>
    <tr>
      <td align="center"><img src="./pictures/Aerial/Drone.png" height="86" width="130"> </td>
    </tr>
     <tr>
      <td align="center"><img src="./pictures/Aerial/Drone.png" height="86" width="130"> </td>
     </tr>
    <tr>
      <td colspan="1",  align="center">Aerial</td>
      <td rowspan="3",  align="center">59</td>
      <td rowspan="3",  align="center">Multi-sensor, <br>6132x8176 px (N)<br>8176x6132 px (O)</td>
      <td rowspan="3",  align="center">City scale</td>
      <td rowspan="3",  align="center">Outdoor large scale, <br>Built-up and vegetated areas</td>
      <td rowspan="3",  align="center">Airborne Laser Scanner</td>
    <tr>
      <td align="center"><img src="./pictures/Aerial/aerial.png" height="97" width="130"> </td>
    </tr>
     <tr>
      <td align="center"><img src="./pictures/Aerial/aerial.png" height="97" width="130"> </td>
     </tr>
    </tr>
  </tbody>
  </table>
</div>

---
## <a name="download"></a> Download

Datasets will be downloadable soon. 

NeRFBK was created by the [3D Optical Metrology unit (3DOM)](https://3dom.fbk.eu/) of Fondazione Bruno Kessler (FBK).
## Citation

Please consider citing our work:

    @inproceedings{
    }

---
## <a name="changelog"></a> Changelog 
* [2023-06-10] Uploaded newest version.
