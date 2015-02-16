# SimpleHttpsClient
A simple HTTPS client based on Boost Asio.

It is based on the boost asio examples
http://www.boost.org/doc/libs/1_55_0/doc/html/boost_asio/example/cpp03/http/client/async_client.cpp
http://www.boost.org/doc/libs/1_55_0/doc/html/boost_asio/example/cpp03/ssl/client.cpp

The resulting applcation creates a connection to a specified server and path and make a GET request using a secure SSL connection.

Building (Linux):
```
cd <path to SimpleHttpsClient>
mkdir build
cd build
cmake -G "Unix Makefiles" ../
make
```
