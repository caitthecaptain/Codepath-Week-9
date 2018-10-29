# Week 9 - Honeypot

Time spent: **4** hours

> Objective: To set up and deploy a honeypot.

## Summary

- Google Cloud Platform (Free Tier) was used. 
- Both virtual machines were f1-micro (1 vCPU, 0.6 GB memory) using the Intel Haswell CPU platform. 
- Both had Ubunto 14.04 (trusty) installed. 
- The first VM (admin console) had the Modern Honey Network (MHN) installed. 
- The other VM had a Dionaea honeypot installed.

## Results

- The honeypot collected a total of **7850** attacks.
- Unfortunately, no malware samples were found. :(
- View my session.json [here](https://raw.githubusercontent.com/caitthecaptain/Codepath-Week-9/master/session.json)!


## Issues

- I had an issue with the Codepath steps for creating my MHN. I found the correct answer [here](https://github.com/RedolentSun/mhn).
- I had an issue with being able to access the MHN VM via my browser. To fix this, I edited my firewall rules to allow traffic on TCP port 80.


## References
- [Google Cloud Platform](https://cloud.google.com/free/docs/frequently-asked-questions) was used for my virtual machines.
