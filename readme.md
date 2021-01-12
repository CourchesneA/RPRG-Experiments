# RPRG Local Experiments

This repo contains the setup to run the experiments for RPRG

To use, clone the template as "ExperimentX". Modify the container for the sim in the docker-compose file and run `make` to execute a run. You can then backup the "challenge" folder to keep results of the experiment. Run the experiment multiple times, then change the agent container in the docker-compose file to proceed to the next student. `imagelist.txt` contains a list of images for the agents and a flag for each experiment was done.

The results are not included in this repo, they are stored locally and exported in a google sheet.

The Notebook folder has the code to compute and analyze the results
