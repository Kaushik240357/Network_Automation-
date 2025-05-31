topconfig

Author: AJ NOURI <ajn.bin@gmail.com>

In this lab we will see how to use a generic GNS3 topology to run multiple independent scenarios, similarly to what is used in CCIE lab rental to switch between different technology scenarios for training.

Each time you need to practice or test a particular network configuration, all you have to do is:
backup the current one.
load a new scenario to the routers and reload them.
on the next boot, your entire topology will run with the new scenario configuration.

This is done using a python script to remotely access the routers to either backup the running configurations to tftp server or load configurations from tftp server to router startup configurations
