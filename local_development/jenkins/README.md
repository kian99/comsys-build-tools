# Run jenkins locally upto 22.04
Many of the docker images provided by jenkins use glibc 2.32-34, jammy ships with 2.35.
Inside this repo you will find a ready-to-go compose and dockerfile for running jenkins locally.
The volume is bound to `../../jeninsdata`.