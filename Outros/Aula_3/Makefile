reciprocal: reciproco.o reciprocal.o
	g++ $(CFLAGS) -o prog reciproco.o reciprocal.o
reciproco.o: reciproco.c reciprocal.hpp	
	gcc $(CFLAGS) -c reciproco.c
reciprocal.o: reciprocal.cpp reciprocal.hpp
	g++ $(CFLAGS) -c reciprocal.cpp
clean:
	rm -f *.o prog

