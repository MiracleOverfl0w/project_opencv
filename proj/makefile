cc=g++
src=src.cpp
configlib=`pkg-config --cflags --libs opencv4`
output=main
tac=-o
src :
	$(cc) $(src) $(tac) $(output) $(configlib)
run :
	make src
	./main
clean:
	rm main