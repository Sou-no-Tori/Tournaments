all: withwinds withoutwinds

withwinds: withwinds.cpp
	clang++ $< -I/opt/localsolver_7_5/include -llocalsolver -lpthread -o $@

withoutwinds: withoutwinds.cpp
	clang++ $< -I/opt/localsolver_7_5/include -llocalsolver -lpthread -o $@

.PHONY: clean

clean:
	rm -rf withwinds withoutwinds
