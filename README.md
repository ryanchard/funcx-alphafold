# funcX AlphaFold

This shows using AlphaFold on ThetaGPU via funcX and Globus Flows. The notebook goes through uploading a FASTA file to ALCF's Eagle before invoking an AlphaFold job on the file. 
The AlphaFold job is dispatched to ThetaGPU using funcX and the results are written to Eagle for the user to collect. 
Once the flow completes it will send an email with a link to the results.



