SRC = \
	lesson06.cpp \
	tgaload.cpp \
	glsl.cpp

OBJ = $(SRC:.cpp=.o)

CXXFLAGS = -Wall -I. -IGL

lesson06: $(OBJ)
	$(CXX) -o $@ $^ -lGL -lGLU -lglut -lGLEW

clean:
	rm -f $(OBJ) lesson06
