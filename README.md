#  Metal Contamination in the Flag Boshielo Dam

## Background 
Scientists from  University of KwaZulu-Natal conducted an array of ICP-OES experiments to assess contamination in the Flag Boshielo Dam. They found that when a body of water is introduced to metal contamination it is retained by the various organisms and bottom sediment rather than remaining suspended in the water. They then performed non-metric multidimensional scaling ordination  on the metal(loid) concentrations within the gill, liver, and muscle of two fish species during two different seasons. The resulting cluster analysis below shows little difference between metal concentration within the fish analyzed  during the winter and summer[fig 1.] while showing statistically notable differences between the metal concentration between the two species[fig 2.].  

**Fig. 1** Liver (square), Gill (circle) and Muscle (triangle). Summer (unfilled) and Winter (filled). 2014.


<p align = "center" >
<img src="img/fig1.jpg">
</p>

**Fig. 2**  Liver (square), Gill (circle) and Muscle (triangle) of Labeo rosae (filled) and Oreochromis mossambicus (unfilled).

<p align = "center" >
<img src="img/fig2.jpg"  width="400">
</p>

##  Analysis 
A supplementary XLS file with data pertaining to the fish specimens' morphometry and the concentrations of metal(loid)s were provided by The National Center for Biotechnology Information and the scientists from University of KwaZulu-Natal. This is an exploratory analysis of that data. The original files were converted to CSV format and titled fish_tissues.csv' and 'fish_morphometry.csv'. The code behind the  visualizations below can be found in the Jupyter notebook titled "Data Visualization.ipynb".
### Python Libraries Used 
* NumPy
* Matplotlib
* Seaborn


<p align = "center" >

<img src="img/om_gill.png"  width="400">
<img src="img/lr_gill.png"  width="400">

</p>

<p align = "center" >
<img src="img/om_liver.png"  width="400">
<img src="img/lr_liver.png"  width="400">
</p>
<p align = "center" >
<img src="img/om_muscle.png"  width="400">
<img src="img/lr_muscle.png"  width="400">

</p>

##  Instrumentation 
Perkin Elmer, Optima 2100 DV [Detection limit: 0.01 mg/L]



##  Work to be done
* Scale y-axis on graphs equally between species


##  References

**1.**   Lebepe J, Oberholster PJ, Luus-Powell WJ. Dataset of metal(loid) concentrations recorded in the tissues of two fish species from Flag Boshielo Dam, South Africa. Data Brief. 2020;33:106396. Published 2020 Oct 9. doi:10.1016/j.dib.2020.106396
















