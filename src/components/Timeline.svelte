
 <div class="timeline">
    <div style="position: absolute;top: 0px;right: 200px;"  >
                    <!-- <img class="img-fluid" src="images/m21.png"  alt="alternative"> -->
        <img cl width="250" src="images/m23.png"  alt="alternative">
    </div> <!-- end of image-container -->
    <div class="container1 left ">
        
        <div class="content" style="text-align: right" >
        <h2 style="text-align: right">2017</h2>
        <b>DIAMASTER WHISPERCUT PRISMATIC REBATE CUTTERHEAD</b>
        <p>
    For highly efficient V-grooving in aluminium composite panels with changeable cutter knives.</p>
                    
        </div>
    </div>

        <div style="position: relative;top: 150px;left: 250px;" >
                    <!-- <img class="img-fluid" src="images/m21.png"  alt="alternative"> -->
        <img cl height="250" src="images/N1.png"  alt="alternative">
    </div> <!-- end of image-container -->
  
  <div class="container1 right">
    <div class="content">
      <h2 >2016</h2>
      <b>CLIMATREND STYLE</b>
      <p>

This innovative and modular window and door system delivers new design and performance USPs.</p>
 
    </div>
  </div>
  <div class="container1 left ">
    <div class="content" style="text-align: right">
      <h2 style="text-align: right">2015</h2>
      <b>COMPACT HOGGER DT PREMIUM</b>
      <p>
The latest evolution of the Leitz hogger programme brings panel sizing to the next economic level.</p>
                <div class="image-container " >
                    <!-- <img class="img-fluid" src="images/m21.png"  alt="alternative"> -->
                     <img width="150" src="images/tt.png"  alt="alternative">
                </div> <!-- end of image-container -->
    </div>
  </div>
</div> 



<style>
/* The actual timeline (the vertical ruler) */
.timeline {
  position: relative;
  max-width: 1200px;

}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: #0f3c6c;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: 0px;
}

/* Container around content */
.container1 {
  padding: 10px 40px;
  position: relative;
  
  width: 50%;
}

/* The circles on the timeline */

.left::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -15px;
  background-color: white;
  border: 4px solid #cc2973;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

.right::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  left: -10px !important;
  background-color: white;
  border: 4px solid #cc2973;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */


/* Place the container to the right */
.right {
  left: 50%;
}




/* Fix the circle for containers on the right side */
.right::after {
  left: -15px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
/* Place the timelime to the left */
  .timeline::after {
    left: 31px;
  }

/* Full-width containers */
  .container1 {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

/* Make sure that all arrows are pointing leftwards */
  .right::before {
    left: 60px;
    border: medium solid white;
    border-width: 10px 10px 10px 0;
    border-color: transparent white transparent transparent;
  }

/* Make sure all circles are at the same spot */
  .left::after, .right::after {
    left: 20px;
  }

/* Make all right containers behave like the left ones */
  .right {
    left: 30px;
  }
}
</style>