ordered.exe: main.o functions.o
	g++ main.o functions.o -o ordered.exe

main.o: main.cpp functions.h
	g++ -c main.cpp

functions.o: functions.cpp functions.h
	g++ -c functions.cpp

clean: 
	rm *.o ordered.exe