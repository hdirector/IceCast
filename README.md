# IceCast (version 3.1)
Apply Statistical Post-Processing to Improve Sea Ice Predictions


Tools for correcting biases and calibrating forecasts of sea ice presence based on dynamic ensemble models. Implements Director et al. (2020) (arxiv.org/abs/1908.09377) which builds on Director et al. (2017) (doi:10.1175/JCLI-D-17-0185.1).  This package depends on the 'ncdf4' and 'rgeos' R packages. These packages require installing externally from R Unidata's 'NetCDF' library and Geometry Engine - Open Source ('GEOS'). (See the 'rgeos' and 'ncdf4' packages for details.) 

Install in R with command: install.packages("IceCast_3.1.0.tar.gz", repos = NULL, type = "source")

View rendered vignettes at: http://htmlpreview.github.io/?https://github.com/hdirector/IceCast/blob/master/biasCorrectDemo.html, 
                            http://htmlpreview.github.io/?https://github.com/hdirector/IceCast/blob/master/FitAndGenerateContours.html, and 
                            http://htmlpreview.github.io/?https://github.com/hdirector/IceCast/blob/master/MixtureContourForecasts.html
