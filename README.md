# GSE_Ned

https://mstrsvw.lvn.broadcom.net:449/zosmf/restfiles/ds?dslevel=roddi01.* 

https://sr01brs.lvn.broadcom.net/zosmf/restfiles/ds?dslevel=roddi01.*

zowe db2 execute sql -q "SELECT * FROM EVENT.COLOR" --rfj

zowe db2 execute sql -q "SELECT * FROM EVENT.MARBLE" --rfj

zowe files list ds "roddi01.*"  --rfj

zowe files list am "roddi01.lib.jcl"  --rfj

zowe files list am "roddi01.lib.jcl"  --rfj -a

zowe cics get resource CICSLocalTransaction -c "TRANID=MB08" --rfj

zowe cics get resource CICSProgram -c "PROGRAM=MARBLE0*" --rft table --rfh --rff program status length

zowe cics get resource CICSProgram -c "PROGRAM=MARBLE0*" --rft object --rfh --rff program status length

zowe cics get resource CICSProgram -c "PROGRAM=MARBLE0*" --rfj


