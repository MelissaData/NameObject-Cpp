# Melissa Name Object Windows C++

CXX=cl
CXXFLAGS=-Zi -EHsc
LDLIBS=mdName.lib
RM=del /q /f

all: MelissaNameObjectWindowsCpp.exe clean

MelissaNameObjectWindowsCpp.exe:	Main.cpp mdName.h mdNameEnums.h
	$(CXX) $(CXXFLAGS) Main.cpp NameObject.cpp $(LDLIBS) /Fe:.\Build\MelissaNameObjectWindowsCpp.exe

clean:
	$(RM) *.obj *.ilk *.pdb *.h.hash *.lib.hash 

