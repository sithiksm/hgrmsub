# hgrmsub
Converting sub repo to monolithic hg repository

Usage: ./hgrmsub -s \<src directory with sub repo> -d \<dest repo to convert>

This script is helpful to remove subrepo and port metadata similar to the existing hg repo. 

Incase any failure happens due to broken commit in src repo, it is also easy to restart from failure point after fixing the issue with the help of revisionmap file. 

Revisionmap store the map between src & dest repo commits.
