# STSS
====
#### Ship traffic simulation system

STSS is a ship traffic simulation system developed by the research group of **[Prof. Meng Qiang]** and Dr. Zhang Liye in **[Centre for Maritime Studies]** of National University of Singapore. It can be used for maritime traffic simulation,
safety quatitive evaluation, ship emission calculation and ship operation management optimization.

[Prof. Meng Qiang]: http://www.eng.nus.edu.sg/cee/people/ceemq/
[Centre for Maritime Studies]: http://www.maritimestudies.nus.edu.sg/


The software offers flexibility in several respects: the ship routes can be input from GUI manually or extracted from historical data automatically. Ship OD demand can be analysed automatically using historical AIS data or input by users. All types of ships can be simulated based on user defination. The naviagation behaviors are data driven models, which are calibrated using the advanced optimization techniques based on big data.

![Screenshot](product_image/main_GUI.PNG)
![Screenshot](/product_image/simulation_snap.PNG)

**Latest Release**: 0.5.0 
  * [Documentation](https://github.com/zhangliye/stss/blob/master/doc)
  * [Examples](https://github.com/zhangliye/stss/blob/master/doc)
 
**Development version**:
  * [Documentation](https://github.com/zhangliye/stss/blob/master/doc)
  * [Examples](https://github.com/zhangliye/stss/blob/master/doc)

## Installation

STSS can run from source code directly when the related python packages are installed. We also supply installing package with installing wizard.

For full installation instructions, see the documentation linked above.

## Citing STSS

If you use the nonlinear or conic optimization functionality of JuMP, please cite the following [preprint](http://arxiv.org/abs/1508.01982) which describes the methods implemented in JuMP. You may cite it as:

    @article{ 
    title = {Big Data-Based Estimation for Ship Safety Distance Distribution in Port Waters},
    author = {Liye Zhang, Huang Wang and Qiang Meng},
    journal = {Transportation Research Record},
    year = {2015},
    url = {http://trrjournalonline.trb.org/doi/abs/10.3141/2479-03?ai=1gvoi&mi=3ricys&af=R}
    }
