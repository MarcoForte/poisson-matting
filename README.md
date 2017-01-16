# poisson-matting
Python of poisson matting method described in   
Jian Sun, Jiaya Jia, Chi-Keung Tang, and Heung-Yeung Shum. 2004. Poisson matting. ACM Trans. Graph. 23, 3 (August 2004), 315-321. DOI=http://dx.doi.org/10.1145/1015706.1015721
http://www.cs.virginia.edu/~gfx/courses/2006/DataDriven/bib/matting/sun04.pdf


### Requirements
- python 3.5 or 2.7
- scipy
- numpy
- matplotlib
- opencv
- numba (optional for speed up)

### Running the demo
- '''python poisson_matting.py'''

### Results
<img alt="Original image" src="https://github.com/MarcoForte/poisson-matting/blob/master/troll.png" width="200">
<img alt="Trimap image" src="https://github.com/MarcoForte/poisson-matting/blob/master/trollTrimap.bmp" width="200">
<img alt="Result image" src="https://github.com/MarcoForte/poisson-matting/blob/master/trollAlpha.png" width="200">

### More Information
The jupyter notebook contains more explanation with nice formatting and pretty pictures, also a numpy version of the poisson solve.


### Disclaimer
The code is free for academic/research purpose. Use at your own risk and we are not responsible for any loss resulting from this code. Feel free to submit pull request for bug fixes.

### Contact 
[Marco Forte](https://marcoforte.github.io/) (fortem@tcd.ie)  
