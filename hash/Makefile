# Makefile для программы хэширования

# Имя исполняемого файла
TARGET = file_hash

# Компилятор и флаги
CXX = g++
CXXFLAGS = -std=c++17 -Wall -Wextra -O2
LDFLAGS = -lcryptopp

# Исходные файлы
SRC = file_hashing.cpp

# Правило сборки исполняемого файла
$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC) $(LDFLAGS)

# Удаление скомпилированных файлов
clean:
	rm -f $(TARGET)

# Фиктивные цели
.PHONY: clean
