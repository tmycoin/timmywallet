## Timmywallet

>  GUI Wallet --> Timmycoin

#### Build Macos

    brew install qt5
    git clone https://github.com/tmycoin/timmywallet.git
    cd timmywallet

    git clone https://github.com/tmycoin/timmy.git cryptonote

    export CMAKE_PREFIX_PATH=/usr/local/Cellar/qt/5.12.0/
    mkdir build
    cmake ..
    make


#### Build Windows

* download qt and install http://www.qt.io/
* download cmake and insatall http://www.cmake.org/
* download boost and insatall https://www.boost.org/users/download/

```SHELL
SET BOOST_ROOT=C:/Users/yasar.icli/Desktop/boost
cmake .. -G "Visual Studio 14" -DCMAKE_PREFIX_PATH=C:\Qt\5.10.1\msvc2015
```

success then open **Timmycoin.sln** and build but before copy **boost/boost** directory --> build

And finally build a wallet for you coin.
