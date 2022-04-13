<script>
    import Timeline from "./Timeline.svelte";
</script>

<div id="details" class="basic-2" style="padding-top: 3rem;background-image: url(images/l1.png); background-repeat: repeat-x;" >
    <img class="decoration-star-2" src="images/decoration-star.svg" alt="alternative">
   
    <div class="container"  >
       
        <div class="row">
             <div class="col-xl-6">
                <div class="image-container " >
                    <!-- <img class="img-fluid" src="images/m21.png"  alt="alternative"> -->
                     <img class="img-fluid" src="images/m24.png"  alt="alternative">
                </div>
                <div class="row mt-5">
                    {#each Array(8) as _, i}
                    <div class="col-xs-2 col-sm-3">
                        <img class="img-fluid mb-4" src="http://placehold.jp/0f3c6c/ffffff/150x150.png"  alt="alternative" > 
                    </div>
                   
                    {/each}
                </div>
               
            </div> 
            <div class="col-xl-6">
                <div class="text-container" style="padding-top: 0px;">
                    <h2 >Une machine 100% fabriquee en Tunisie</h2>
                    <ul class="list-unstyled li-space-lg">
                        <li class="d-flex">
                            <i class="fas fa-square"></i>
                            <div class="flex-grow-1"> <b>Quatre vis à billes</b> assurent un déplacement précis et sans aucune vibration de la machine même dans les conditions de coupe les plus difficiles.</div>
                        </li>
                        <li class="d-flex">
                            <i class="fas fa-square"></i>
                            <div class="flex-grow-1"> <b>Broche asynchrone</b>  à haute fréquence jusqu’à la puissance de <b>9kw</b> (à <b>24.000 rpm</b> ) avec l’option de roulements en céramique pour une forte cadence de travail.</div>
                        </li>                      
                        <li class="d-flex">
                            <i class="fas fa-square"></i>
                            <div class="flex-grow-1"><b>Alimentation industrielle</b>  robuste 76VDC-1000W.Armoire Vitrée IP55 avec ventilation forcée,Directeur d’axes supportant 4 axes (standard) avec commande de vitesse de la broche ,commande aspirateur et un watch dog pour la sécurité.</div>
                        </li>
                          <li class="d-flex">
                            <i class="fas fa-square"></i>
                            <div class="flex-grow-1">Dimensions de coupe (standard) : <b>2500</b> x <b>1850</b> x  <b>150mm</b>  </div>
                        </li>
                    </ul>
                    <a class="btn-solid-reg" href="article.html">Plus d'Infomation</a>
                </div> <!-- end of text-container -->
            </div> 
        </div>
        
    </div> 
</div>

<div id="details" class="basic-2" style="padding-top: 3rem;" >
    <img class="decoration-star-2" src="images/decoration-star.svg" alt="alternative">
   
    <div class="container"  >
        <div class="row">                            
          
               <div class="col-12" style="border-bottom: 2px solid #0f3c6c ;">
                    <h4>Technologiesegment</h4>
               </div>
               <div>
                    <div class="row mb-5">
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Vertikal</span>
                            <span class="float-end">✓</span>
                        </div>
                    </div>
               </div>
               

               <!--  -->

               <div class="col-12" style="border-bottom: 2px solid #0f3c6c ;">
                    <h4>Arbeitsraum</h4>
               </div>
               <div>
                    <div class="row mb-5">
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Max. X-Achse</span>
                            <span class="float-end">700 mm</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Max. Y-Achse</span>
                            <span class="float-end">420 mm</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Max. Z-Achse</span>
                            <span class="float-end">380 mm</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Max. Anzahl Achsen</span>
                            <span class="float-end">4</span>
                        </div>
                    </div>
               </div>

               <div class="col-12" style="border-bottom: 2px solid #0f3c6c ;">
                    <h4>Fertigungsart</h4>
               </div>
               <div>
                    <div class="row mb-5">
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Einzelfertigung</span>
                            <span class="float-end">✓</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Kleinserien (&lsaquo;50)</span>
                            <span class="float-end">✓</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Mittelserien (50 - 1000)</span>
                            <span class="float-end">✓</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Großserien (1000 - 100.000)</span>
                            <span class="float-end">✓</span>
                        </div>
                    </div>
               </div>

               <div class="col-12" style="border-bottom: 2px solid #0f3c6c ;">
                    <h4>Materialien</h4>
               </div>
               <div>
                    <div class="row mb-5">
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Aluminium</span>
                            <span class="float-end">✓</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">MDF/HDF</span>
                            <span class="float-end">✓</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">HPL</span>
                            <span class="float-end">✓</span>
                        </div>
                        <div class="col-12 py-2 " style="border-bottom: 1px solid #8ba8c6;">
                            <span class="">Plastik / CFK</span>
                            <span class="float-end">✓</span>
                        </div>
                    </div>
               </div>
               
               


              
               
          
           
        </div>
        
    </div> 
</div>
