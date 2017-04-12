
FC = gfortran
FLG = -O
EISLIB = eispack.a
AR = ar r
RAN = ranlib

DP =

#- uncomment for double-precision option

eispack.a: eispack.f
	$(FC) -c $(FLG) $(DP) eispack.f
	$(AR) $(EISLIB) eispack.o
	$(RAN) $(EISLIB)

clean:
	/bin/rm *.o *.a


