

Configless Slurm [smdcs]....

* ...pulls configuration information directly from the `slurmctld` instead of from
  a pre-distributed local file.
* Built in by default starting with Slurm 20.02.

```bash
# run in the configless mode
>>> grep SlurmctldParameters slurm.conf 
SlurmctldParameters=enable_configless
```



[smdcs]: SchedMD Documentation - "Configless" Slurm  
         <https://slurm.schedmd.com/configless_slurm.html>
