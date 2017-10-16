

application: main.o
	g++ main.o -o application
	./application
main.o: main.cpp
	g++ -c main.cpp 


something.o: something.cpp something.h
	g++ -c something.cpp


clean:
	rm *.o application
