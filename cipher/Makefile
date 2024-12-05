# Makefile для программы шифрования/расшифрования

# Имя исполняемого файла
TARGET = file_encrypt_decrypt

# Компилятор и флаги
CXX = g++
CXXFLAGS = -std=c++17 -Wall -Wextra -O2
LDFLAGS = -lcryptopp

# Исходные файлы
SRC = file_encrypt_decrypt.cpp

# Правило сборки исполняемого файла
$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRC) $(LDFLAGS)

# Удаление скомпилированных файлов
clean:
	rm -f $(TARGET)

# Фиктивные цели
.PHONY: clean
