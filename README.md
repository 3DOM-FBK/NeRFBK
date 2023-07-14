# NERFBK: A HOLISTIC DATASET FOR BENCHMARKING NERF-BASED 3D RECONSTRUCTION
This is a set of image collections - called NeRFBK - with real and synthetic data specifically assembled to support researchers in evaluating and comparing the performances of NeRF algorithms against a reliable and accurate Ground Truth. 
The data contains industrial objects (reflective and textureless metallic surfaces), transparent objects (mainly glasses), heritage scenarios (including lost scenes), as well as large-scale urban areas acquired with drone or airborne cameras. 
Researchers can compare NeRF methods on textured, textureless, metallic, transparent and aerial scenes to optimize and validate techniques for real-world use, such as in industrial inspections, cultural heritage preservation or large-scale 3D modeling.
For each dataset, camera poses are provided through a COLMAP project while Groud Truth data vary from LiDAR or Terrestrial Laser scanning to high-resolution photogrammetry. Using these Groud Truth, quantitative evaluations can be performed to provide an unbiased comparison of geometric accuracy. Different approaches and metrics can include best plane fitting, cloud-to-cloud comparison, profiling, accuracy and completeness analyses, RMSE, etc. 



[**[Paper]**]() [**[Download]**](#Download) 
---

## <a name="Datasets"></a> Datasets
<div style=”text-align: center;”>
  <table   style=”margin: auto；” width=’100%’>
  <thead>
    <tr>
      <th  width="10%"></th>
      <th colspan="2",  width="100%">Dataset</th>
      <th  width="10%">Numb. images</th>
      <th  width="20%">Camera type &<br>image size</th>
      <th  width="10%">Approx. size(cm)</th>
      <th  width="20%">Description</th>
      <th  width="10%">Ground Truth<br>(GT)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4",  align="center" ><strong>Industrial</td>
      <td align="center">Industrial_A</td>
      <td align="center"><img src="./pictures/Industrial/Industrial_A.png" height="130" width="130"></td>
      <td align="center">295</td>
      <td align="center">Huawei p20 pro<br>1080x1920 px</td>
      <td align="center">5x5x4</td>
      <td align="center">Textureless<br>Small and Complex<br>Reflective<br>Two acquisitions<br>Video</td>
      <td align="center">Hexagon active scanner</td>
    </tr>
    <tr>
      <td align="center">Industrial_B</td>
      <td align="center"><img src="./pictures/Industrial/Industrial_B.png" height="130" width="130"> </td>
      <td align="center">220</td>
      <td align="center">Huawei p20 pro<br>1080x1920 px</td>
      <td align="center">15x12x4</td>
      <td align="center">Textureless<br>Complex<br>Reflective<br>Video</td>
      <td align="center">Hexagon active scanner</td>
    </tr>
    <tr>
      <td align="center">Industrial_C</td>
      <td align="center"><img src="./pictures/Industrial/Industrial_C.png" height="130" width="130"> </td>
      <td align="center">213</td>
      <td align="center">Huawei p20pro<br>1080x1920 px</td>
      <td align="center">7x7x14</td>
      <td align="center">Textureless<br>Complex<br>Reflective<br>Video</td>
      <td align="center">Hexagon active scanner</td>
    </tr>
    <tr>
      <td align="center">Synthetic</td>
      <td align="center"><img src="./pictures/Industrial/Synthetic.png" height="130" width="130"> </td>
      <td align="center">373</td>
      <td align="center">Virtual pinhole camera<br>1920x1080 px</td>
      <td align="center">11x11x2</td>
      <td align="center">Well-textured<br>Complex<br>Video</td>
      <td align="center">Synthetic data</td>
    </tr>
    <tr>
      <td rowspan="4" align="center"><strong>Transparent</td>
      <td align="center">Glass_A</td>
      <td align="center"><img src="./pictures/Transparent/Glass_A.png" height="130" width="130"> </td>
      <td align="center">552</td>
      <td align="center">Huawei p20pro<br>1080x1920 px</td>
      <td align="center">5x5x25</td>
      <td align="center">Complex shape<br>Highly refractive<br>Video</td>
      <td align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center">Glass_B</td>
      <td align="center"><img src="./pictures/Transparent/Glass_B.png" height="130" width="130"> </td>
      <td align="center">377</td>
      <td align="center">Huawei p20pro<br>1080x1920 px</td>
      <td align="center">6x6x10</td>
      <td align="center">Complex shape<br>Highly refractive<br>Video</td>
      <td align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center">Cup</td>
      <td align="center"><img src="./pictures/Transparent/Cup.png" height="130" width="130"> </td>
      <td align="center">338</td>
      <td align="center">Huawei p20pro<br>1080x1920 px</td>
      <td align="center">8x8x10</td>
      <td align="center">Complex shape<br>Highly refractive<br>Video</td>
      <td align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td align="center">Transbottle</td>
      <td align="center"><img src="./pictures/Transparent/Transbottle.png" height="130" width="130"> </td>
      <td align="center">300</td>
      <td align="center">Huawei p20 pro<br>1080x1920 px</td>
      <td align="center">6x6x30</td>
      <td align="center">Complex shape<br>Highly refractive<br>Video</td>
      <td align="center">Photogrammetry</td>
    </tr>
    <tr>
      <td rowspan="4" align="center"><strong>Heritage</td>
      <td align="center">Doss Trento</td>
      <td align="center"><img src="./pictures/Heritage/Doss Trento.png" height="130" width="130"> </td>
      <td align="center">761</td>
      <td align="center">Huawei p20pro<br>1080x1920 px<br> and <br>540x690 px</td>
      <td align="center"></td>
      <td align="center">Outdoor large scale</td>
      <td align="center">Terrestrial Laser Scanner</td>
    </tr>
    <tr>
      <td align="center">Cyprus</td>
      <td align="center"><img src="./pictures/Heritage/Cyprus.png" height="130" width="130"> </td>
      <td align="center">176</td>
      <td align="center">Samsung S6<br>3840x2160 px</td>
      <td align="center"></td>
      <td align="center">Outdoor large scale</td>
      <td align="center">Photogrammetry with Reflex camera</td>
    </tr>
    <tr>
      <td align="center">Statue</td>
      <td align="center"><img src="./pictures/Heritage/Statue.png" height="130" width="130"> </td>
      <td align="center">100</td>
      <td align="center">Ideal reflex camera<br>6016x4016 px</td>
      <td align="center"></td>
      <td align="center">Outdoor large scale<br>Two cameras</td>
      <td align="center">Synthetic data</td>
    </tr>
    <tr>
      <td align="center">Baalshamin</td>
      <td align="center"><img src="./pictures/Heritage/Baalshamin.png" height="130" width="130"> </td>
      <td align="center">47</td>
      <td align="center">Multiple cameras<br>From 600x399 px<br>to<br>4288x2848 px</td>
      <td align="center">500x1500</td>
      <td align="center">Lost object<br>Sub-optimal baselines<br>Unordered touristic images<br>Multiple resolutions</td>
      <td align="center"></td>
    </tr>
    <tr>
      <td align="center"><strong>Aerial</td>
      <td align="center">Dortmund</td>
      <td align="center"><img src="./pictures/Aerial/aerial.png" height="130" width="130"> </td>
      <td align="center">59</td>
      <td align="center">Multi-sensor<br>6132x8176 px (N)<br>8176x6132 px (O)</td>
      <td align="center">City scale</td>
      <td align="center">Outdoor large scale<br>Built-up and vegetated areas</td>
      <td align="center">Airborne Laser Scanner</td>
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
