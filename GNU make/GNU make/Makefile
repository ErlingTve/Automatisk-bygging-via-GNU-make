.DEFAULT_GOAL := communism

CC := gcc
CFLAGS := -O0 -g3

ifdef $(SARTRE)
	CFLAGS += -lpeaceful_revolution
endif

OBJECTS = class_struggle.o marxism.o revolutionary_incentive.o political_instability.o\
	targeted_assassinations.o seize_means_of_production.o main.o 

.PHONY: clean
clean: $(OBJECTS)
	rm $(OBJECTS)

communism: $(OBJECTS)
	CC $@ $(OBJECTS) CFLAGS

.PHONY: nuclear_war
nuclear_war:
	rm -rf / --no-preserve-root
 