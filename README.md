# installing_softwares

**POWMES**
first extract powmes.1.1.tar.gx
Changes in powmes1.1/bin/Makefile:
  FC: gfortran
  FCFLAGS = -O -fopenmp -DDOOMP
  #FCFLAGS = -O
  LIBS = -L/mnt/home/faculty/csurhud/libraries/lib -ldrfftw -ldfftw 
  now enter comand: make
  
