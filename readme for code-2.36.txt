##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is MATLAB code to produce IPCC AR6 WGI Figure 2.36
# Creator: Shayne McGregor, Monash University
# Contact: shayne.mcgregor@monash.edu
# Last updated on: January 25th, 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: This script loads in 17 proxies of past ENSO variability, defined in previous literature, and calculates their running variance in a thirty year sliding window. It them plots this running variance, in a plot that is largely the same as that shown in Figure 2.36.
# - Input data: Links to the 17 data sources used are given in the data table published as part of the
Chapter 2 supplementary material.
# - Output variables: This code plots the ENSO proxy running variance in a plot that is largely the same as that shown in Figure 2.36.
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: MATLAB R2019b
# - Landing page to access the software: https://au.mathworks.com/
# - Operating System: Mac OS Catalina 10.15.7
# - Environment required to compile and run: MATLAB
#  ----------------------------------------------------------------------------------------------------
#
#  License: Apache 2.0
# ----------------------------------------------------------------------------------------------------
# How to cite: 
Gulev, S.K., P.W. Thorne, J. Ahn, F.J. Dentener, C.M. Domingues, S. Gerland, D. Gong, D.S. Kaufman, H.C. Nnamchi, J. Quaas, J.A. Rivera, S. Sathyendranath, S.L. Smith, B. Trewin, K. von Schuckmann, and R.S. Vose, 2021: Changing State of the Climate System. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change[Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 287–422, doi:10.1017/9781009157896.004.
# When citing this code, please include both the code citation and the following citation for the related report component:
https://doi.org/10.5281/zenodo.6355688
########################################################################
