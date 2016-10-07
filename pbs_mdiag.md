## Output from `mdiag -u`

    [grundoon@flux-login1 hpc101]$ mdiag -u $USER
    evaluating user information
    Name                      Priority        Flags         QDef      QOSList*        PartitionList Target  Limits

    grundoon                         0            -         flux         flux                     -   0.00       -
      GDEF=cacstaff
      EMAILADDRESS=grundoon@umich.edu
      ADEF=engin_flux  ALIST=engin_flux,hpc101_flux,support_flux,support_fluxg,support_fluxm,support_fluxod
      Message:  profiling enabled (3021 of 8760 samples/1:00:00 interval)

## Output from `mdiag -a`

    [grundoon@flux-login1 hpc101]$ mdiag -a hpc101_flux
    evaluating acct information
    Name         Priority        Flags         QDef      QOSList*        PartitionList Target  Limits

    hpc101_flux         0            -         flux         flux                [flux]   0.00  MAXPROC=50 MAXMEM=204800 MAXIJOB[USER]=20,20
     MAXIPROC[USER]=-1,-1

      Users:    grundoon,albert,pogo,mizhepz

    [grundoon@flux-login1 hpc101]$
_._
