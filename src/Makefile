all: dednm rasfor raspro rasbin 

%.o : %.f90
	gfortran -c $<

dednm: dednm.o 
	gfortran dednm.o -o dednm

raspro: raspro.o
	gfortran raspro.o -o raspro 

rasfor: rasfor.o
	gfortran rasfor.o -o rasfor 

rasbin: rasbin.o
	gfortran rasbin.o -o rasbin 

clean:
	rm dednm.o rasfor.o raspro.o rasbin.o 
	rm dednm raspro rasfor rasbin 

