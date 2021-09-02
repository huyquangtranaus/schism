## SCHISM: Semi-implicit Cross-scale Hydroscience Integrated System Model

Build instructions may be found on the SCHISM wiki at schism.wiki

When using the development version, note changes in flags and features described in
beta_notes and examplified in param.in.sample, bctides.in.sample, etc.
 
## VARIABLE LIST

# A


# B

# C

# D

# E

# F

# G

# H

# I

# J

# K

# L

# M

# N

# O

# P

# Q

# R

# S

# T

### trobc
schism_init.F90:1666:          & itrtype(natrm,max(1,nope_global)),trobc(natrm,nope_global), & !tobc(nope_global),sobc(nope_global) 
schism_init.F90:2486:        trobc(:,k)=0 !init.
schism_init.F90:2494:              read(31,*) trobc(i,k) !nudging factor
schism_init.F90:2496:              read(31,*) trobc(i,k) !nudging factor
schism_init.F90:2506:              read(31,*) trobc(i,k) !nudging factor
schism_init.F90:2508:              read(31,*) trobc(i,k) !nudging factor
schism_init.F90:2516:            if(trobc(i,k)<0.or.trobc(i,k)>1) then
schism_init.F90:2517:              write(errmsg,*)'Tr. obc nudging factor wrong:',trobc(i,k),k
transport_TVD.F90:902:                    trel_tmp_outside(ll)=trobc(jj,ibnd)*trth(ll,1,1,ibnd)+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD.F90:905:                    trel_tmp_outside(ll)=trobc(jj,ibnd)*tmp+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD.F90:906:                    !trel_tmp_outside(ll)=trobc(jj,ibnd)*trel0(ll,k,i)+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD.F90:908:                    trel_tmp_outside(ll)=trobc(jj,ibnd)* &
transport_TVD.F90:910:     &(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD_imp.F90:623:                        trel_tmp_outside(ll)=trobc(jj,ibnd)*trth(ll,1,1,ibnd)+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD_imp.F90:626:                        trel_tmp_outside(ll)=trobc(jj,ibnd)*tmp+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD_imp.F90:628:                        trel_tmp_outside(ll)=trobc(jj,ibnd)* &
transport_TVD_imp.F90:630:       &(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD_imp.F90:1141:                      trel_tmp_outside(ll)=trobc(jj,ibnd)*trth(ll,1,1,ibnd)+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD_imp.F90:1144:                      trel_tmp_outside(ll)=trobc(jj,ibnd)*tmp+(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)
transport_TVD_imp.F90:1146:                      trel_tmp_outside(ll)=trobc(jj,ibnd)* &
transport_TVD_imp.F90:1148:     &(1-trobc(jj,ibnd))*trel_tmp(ll,k,i)


# U

# V

# W

# X

# Y

# Z
