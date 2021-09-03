## SCHISM: Semi-implicit Cross-scale Hydroscience Integrated System Model

#### ----------- This forked directory is maintained by Huy Quang Tran -----------


## VARIABLE LIST

# A


# B

# C

# D

# E

* eta_m0(i) !mean elev at each node

# F

# G

# H

# I

* iETtype(j): b.c flags for elevation
* iFLtype(j): b.c flags for velocity 
* iTEtype(j): b.c flags for temperature
* iSAtype(j): b.c flags for salinity
* iTRtype(j): b.c flags for tracer
* indvel : Control the balance between numerical diffusion and dispersion?
  *    *indvel=0, conformal linear shape function is used; if indvel=1, averaging method is used*

* ihorcon: Control the balance between numerical diffusion and dispersion?

(ihorcon =0 means horizontal viscosity term=0 see Hydro/schism_init.F90:331)

# J

* jspc(k): tidal species (0: declinational; 1: diurnal; 2: semi-diurnal)
* 

# K

# L

# M

# N

* neta (j): off nodes on the boundary segment j (e.g. see manual page 66 section bctides.in)
* nbfr !total # of tidal boundary forcing frequencies

# O

# P

# Q

# R

# S

# T

* talpha: tidal constituent name
* tamp(k): amplitude constants
* tfreq(k): angular frequency
* tnf(k): nodal factor
* tear(k): earth equilibrium argument (in degrees)
### trobc



# U

# V

* vn_mean !mean normal velocity

# W

# X

# Y

# Z
