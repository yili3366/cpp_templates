OBJS=max implicit adl inject lazy funcoverload nontmpl

PHONY+=clean

all: max implicit adl inject lazy funcoverload nontmpl

max: max.cpp
implicit: implicit.cpp
adl: adl.cpp
inject: inject.cpp
lazy: lazy.cpp
#fppm: fppm.cpp
funcoverload: funcoverload.cpp
nontmpl: nontmpl.cpp

.PHONY: $(PHONY)
clean:
	rm $(OBJS)
