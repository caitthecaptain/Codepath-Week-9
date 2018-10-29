# Week 9 - Honeypot

Time spent: 4 hours spent in total

> Objective: To setup and deploy a honeypot in the cloud and report back the findings.

## Setup Details

I used Google Cloud Platform Free Tier. Two virtual machines were set up. Both were f1-micro (1 vCPU, 0.6 GB memory) using the Intel Haswell CPU platform. Both had Ubunto 14.04 (trusty) installed. On one, I installed the Modern Honey Network (MHN) administration application. On the other, I deployed a Dionaea honeypot. I then ran an attack against the honeypot using nmap to make sure it is working correctly. Then, I began collecting information.

## Results

The honeypot collected a total of _ attacks, with the session.json [here](https://github.com/...blob/Week-9/session.json).


## Issues

I did not really encounter too many issues. However, I did have an issue with setting up the MHN VM, but I easily found a solution.

## Unresolved Questions
