### Output from `showq` when jobs are running and waiting

	[grundoon@flux-login1 hpc101]$ showq -w acct=hpc101_flux
	
	active jobs------------------------
	JOBID              USERNAME      STATE PROCS   REMAINING            STARTTIME
	
	15913823             bennet    Running     1    00:13:42  Wed May 13 21:19:01
	15913820           grundoon    Running     1    00:58:42  Wed May 13 21:19:01
	15913821           grundoon    Running     1    00:58:42  Wed May 13 21:19:01
	
	3 active jobs           3 of 17464 processors in use by local jobs (0.02%)
	                       826 of 1172 nodes active      (70.48%)


	eligible jobs----------------------
	JOBID              USERNAME      STATE PROCS     WCLIMIT            QUEUETIME	

		0 eligible jobs   

	
	blocked jobs-----------------------
	JOBID              USERNAME      STATE PROCS     WCLIMIT            QUEUETIME
	15886094[19]         albert       Idle     8  1:00:00:00  Tue May 12 00:28:43
	15886867               pogo       Idle     1  2:02:59:00  Tue May 12 02:30:39

	2 blocked jobs   
	
	Total jobs:  5

_._    