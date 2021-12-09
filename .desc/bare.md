# Container: Bare  
_A starting point_  

An Archlinux64 based container. On startup it runs a script to detect core count 
and configure makepkg and pacman respectively. It then updates, and installs:  
 - git  
 - wget  
 - sudo  
And replaces grep with ag (the\_silver\_searcher)
