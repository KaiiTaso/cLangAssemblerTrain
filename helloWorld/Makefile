# コンパイラとフラグの設定
CXX = g++
#CXXFLAGS = -g
CXXFLAGS = 

# ターゲットとオブジェクトファイル
TARGET = hello
SOURCE = hello.c

# 実行ファイルのビルド
$(TARGET):
	$(CXX) $(CXXFLAGS) -o $(TARGET)  $(SOURCE)

# 実行ファイルのビルド
hello.s:
	$(CXX) $(CXXFLAGS) -S hello.s $(SOURCE)

# クリーンアップルール
clean:
	rm -f $(TARGET)
