CXX = g++
LIB = -std=c++11

main : sorteermethode main.cpp
	$(CXX) $(LIB) main.cpp

sorteermethode : sortvector chrono csv sorteermethode.h
	$(CXX) $(LIB) sorteermethode.h

sortvector : sortvector.h
	$(CXX) $(LIB) sortvector.h

chrono : chrono.h
	$(CXX) $(LIB) chrono.h

csv : csv.h
	$(CXX) $(LIB) csv.h

clean :
	rm -f *.gch
