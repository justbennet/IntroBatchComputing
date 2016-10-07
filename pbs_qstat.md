## Output from qstat when a job is in the queue


    [grundoon@flux-login3 hpc101]$ qstat -u $USER

    nyx.engin.umich.edu: 
                                                                                      Req'd    Req'd       Elap
    Job ID                  Username    Queue    Jobname          SessID  NDS   TSK   Memory   Time    S   Time
    ----------------------- ----------- -------- ---------------- ------ ----- ------ ------ --------- - ---------
    15913783.nyx.engin.umi  grundoon    flux     grundoon_first      --      1      1    1gb  01:00:00 Q       -- 


## Output from qstat when a job is running


    [grundoon@flux-login3 hpc101]$ qstat -u $USER

    nyx.engin.umich.edu: 
                                                                                      Req'd    Req'd       Elap
    Job ID                  Username    Queue    Jobname          SessID  NDS   TSK   Memory   Time    S   Time
    ----------------------- ----------- -------- ---------------- ------ ----- ------ ------ --------- - ---------
    15913783.nyx.engin.umi  grundoon    flux     grundoon_first    80815     1      1    1gb  01:00:00 R  00:00:47


## Output from qstat when a job is done


    [grundoon@flux-login3 hpc101]$ qstat -u $USER

    nyx.engin.umich.edu: 
                                                                                      Req'd    Req'd       Elap
    Job ID                  Username    Queue    Jobname          SessID  NDS   TSK   Memory   Time    S   Time
    ----------------------- ----------- -------- ---------------- ------ ----- ------ ------ --------- - ---------
    15913783.nyx.engin.umi  grundoon    flux     grundoon_first    80815     1      1    1gb  01:00:00 C       -- 

.