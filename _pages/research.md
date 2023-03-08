---
layout: archive
title: "Research"
permalink: /research/ # generate a html called research.html in _site
author_profile: true
---
<div class = "row">  <!--   -->
  <div class = "column-text"> 
    <h2>Beam-offset Optical Coherence Tomography </h2>
    <p> In conventional OCT, the illumination and detection beams share the same optical path, while in BO-OCT, the detection beam is offset from the illumination beam by a small distance ∆r. This offset detection beam can detect multiple scattered photons (MSPs) that are beyond the scope of the illumination beam.</p>
    <p> The BO-OCT enables the separation of least scattered photons (LSPs) and MSPs. This separation allows for the direct extraction of depth-resolved PSF autocorrelation function/MTF from OCT images. Such capability opens up new avenues for realizing adaptive optical imaging and accurately quantifying tissue optical properties. </p>
    <a href = "https://opg.optica.org/boe/fulltext.cfm?uri=boe-13-11-6124&id=513697"> Weiming Xu and Hui Wang, "Using beam-offset optical coherence tomography to reconstruct backscattered photon profiles in scattering media," Biomed. Opt. Express 13, 6124-6135 (2022)</a>
  </div>
  <div class="column-video">
    <video class ="bo-oct" preload width="100%" height = "auto" controls>
     <source src="{{site.baseurl }}/assets/video/BSOCT.mp4" type="video/mp4">
    </video>

  </div>             
</div>


<div class="row">
  <div class="column-text">
    <h2> Tissue Regeneration Process Under OCT </h2>
    <p class="small-gap"> Regenerating a human organ as its original one remains a part of our imagination. However, some animals do have this capability. Newts have the ability to regenerate their lens when lost or injured by reprogramming the dorsal iris pigmented epithelial cells (iPECs). Lens regeneration not only has important clinical significance, but it is also an ideal process for studying tissue regeneration as it occurs in the transparent anterior chamber of the eye and is easily accessible.</p>   
  </div>  
 <div class="column-video">
    <video class ="newtlens" preload width="90%" height = "auto" controls>
     <source src="{{site.baseurl }}/assets/video/NewtLens.mp4" type="video/mp4">
    </video>
  </div>              
</div> 

<div class= "row">
  <div class = "column-text-full">
   <p>Histological analysis, electron microscopy, immunofluorescence and in situ hybridization analysis have long been adapted as major tools to help us understand the process of lens regeneration. Mostly, these ex-vivo technologies represent a snapshot of the regeneration process from a specific point of view at a specific time point. However, tissue regeneration is a dynamic process involving cellular, molecular and functional changes. Collaborating with Dr. Katia Del Rio-Tsonis, we have been able, for the first time, to noninvasively acquire high-quality in vivo images with optical coherence tomography (OCT) by tracking a single newt continuously during the process of lens regeneration.</p>
   <p>Our research has been highlighted by National Eye Institue (NEI). In addition to imaging the lens, we are working on imaging the regeneration of the retina. </p>
   <a href = "https://www.nei.nih.gov/about/news-and-events/news/small-creatures-teach-big-lessons">1) Small creatures teach big lessons:Animal models provide critical clues in vision research</a> <br>
   <a href = "https://tvst.arvojournals.org/article.aspx?articleid=2776586">2) Weihao Chen, Georgios Tsissios, Anthony Sallese, Byran Smucker, Anh-Thu Nguyen, Junfan Chen, Hui Wang, Katia Del Rio-Tsonis; In Vivo Imaging of Newt Lens Regeneration: Novel Insights Into the Regeneration Process. Trans. Vis. Sci. Tech. 2021;10(10):4.</a> 
 </div>
</div>

<style>
.row {
  display: flex;
  justify-content: right;
  /* margin-bottom: 0 -10px;  */
}
.column-text{
  width:70%;
  /* padding: 0 -10px; */
}
.column-video{
  width:30%
  height: auto;
  /* padding: 0 10px; */
}
.column-text-full{
  width:100%;

} 
.small-gap{
  margin-bottom:5px;
}

.bo-oct {
  max-width: 60%;
  height: auto;
}
.newtlens {
  padding-top:10%;
  max-width: 100%;
  height: auto;
  margin-left:10px;
} 
</style> 


