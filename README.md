# google_test_example
Google Testの練習

こちらの記事【Google Test ことはじめ】を写経させていただいた。

https://techblog.kayac.com/google-test


コンパイルのコマンドはつぎのとおり。

g++ -std=c++11 test/example_test.cpp -I. -Isrc -Igoogletest/include -Lgoogletest -lgtest -lgtest_main -lpthread
