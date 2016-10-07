## Output from `checkjob` command

	[grundoon@flux-login1 hpc101]$ qsub iris.pbs 
	15913928.nyx.engin.umich.edu
	[grundoon@flux-login1 hpc101]$ checkjob -v 15913928

	--------------------------------------------------------------------
	NOTE: The following information has been cached by the remote server
	      and may be slightly out of date.
	--------------------------------------------------------------------

	ERROR:  invalid job specified: 15913928

	[grundoon@flux-login1 hpc101]$ checkjob -v 15913928

	--------------------------------------------------------------------
	NOTE: The following information has been cached by the remote server
	      and may be slightly out of date.
	--------------------------------------------------------------------

	job 15913928 (RM job '15913928.nyx.engin.umich.edu')

	AName: iris_R
	State: Idle 
	Creds:  user:grundoon  group:cacstaff  account:hpc101_flux  class:flux  qos:flux
	WallTime:   00:00:00 of 1:00:00
	SubmitTime: Wed May 13 21:45:30
	  (Time Queued  Total: 00:01:25  Eligible: 00:00:03)

	TemplateSets:  DEFAULT
	Total Requested Tasks: 1

	Req[0]  TaskCount: 1  Partition: ALL
	Dedicated Resources Per Task: PROCS: 1  MEM: 768M
	NodeSet=ONEOF:FEATURE:[NONE]

	Reserved Nodes:  (-00:01:22 -> 00:58:38  Duration: 1:00:00)
	[nyx5512:1]

	SystemID:   Moab
	SystemJID:  15913928
	Task Distribution: nyx5512
	UMask:          0000 
	OutputFile:     flux-login1.engin.umich.edu:/home2/grundoon/hpc101/iris_R.o15913928
	ErrorFile:      flux-login1.engin.umich.edu:/home2/grundoon/hpc101/iris_R.e15913928
	User Specified Partition List:   flux
	Partition List: flux
	SrcRM:          nyx  DstRM: nyx  DstRMJID: 15913928.nyx.engin.umich.edu
	Submit Args:    iris.pbs
	Flags:          BACKFILL,RESTARTABLE,PROCSPECIFIED
	Attr:           BACKFILL,checkpoint
	StartPriority:  -1389225
	PE:             1.00
	Reservation '15913928' (-00:01:22 -> 00:58:38  Duration: 1:00:00)
	NOTE:  job violates constraints for partition flux (waiting for non-blocking AM action to complete)

	NOTE:  job violates constraints for partition fluxm (waiting for non-blocking AM action to complete)

	NOTE:  job violates constraints for partition fluxg (waiting for non-blocking AM action to complete)

	NOTE:  job violates constraints for partition fluxod (waiting for non-blocking AM action to complete)

	NOTE:  job violates constraints for partition fluxoe (waiting for non-blocking AM action to complete)

	Message[0] Waiting to register job start with accounting manager

.
