OBJS=addvaltest max max2 max3 max3a max4.o stack1test stack2test stack3test stack4test \
     stack5test stack6test stack8test refnonref myfirstmain 
PHONY+=clean

all: addvaltest max max2 max3 max3a max4.o stack1test stack2test stack3test stack4test \
     stack5test stack6test stack8test refnonref myfirstmain 

addvaltest: addvaltest.cpp
max: max.cpp
max2: max2.cpp
max3: max3.cpp
max3a: max3a.cpp
max4.o: max4.cpp
stack1test: stack1test.cpp
stack2test: stack2test.cpp
stack3test: stack3test.cpp
stack4test: stack4test.cpp
stack5test: stack5test.cpp
stack6test: stack6test.cpp
#stack7test: stack7test.cpp stack7decl.hpp stack7.hpp
stack8test: stack8test.cpp
#max5: max5.cpp
refnonref: refnonref.cpp
myfirstmain: myfirstmain.cpp
#myfirst3main: myfirst3main.cpp
#tracertest: tracertest.cpp

.PHONY: $(PHONY)
clean:
	rm $(OBJS)
