Bootstrap: docker
From: trinityrnaseq/trinityrnaseq

%labels
  MAINTAINER SysBioChalmers
  DESCRIPTION Singularity image containing the trinityrnaseq pipeline tweaked for the Hebbe cluster at Chalmers University of Technology
  VERSION 2.8.5

%post
  mkdir -p /c3se
  mkdir -p /local
  mkdir -p /apps
  mkdir -p /priv
  mkdir -p /usr/share/lmod/lmod
  mkdir -p /var/hasplm
  mkdir -p /var/opt/thinlinc
  mkdir -p /usr/lib64
  touch /usr/lib64/libdlfaker.so
  touch /usr/lib64/libvglfaker.so
  touch /usr/bin/nvidia-smi
