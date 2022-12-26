# SimpleHttpsClient
A simple HTTPS client based on Boost Asio.

It is based on the boost asio examples
http://www.boost.org/doc/libs/1_55_0/doc/html/boost_asio/example/cpp03/http/client/async_client.cpp and 
http://www.boost.org/doc/libs/1_55_0/doc/html/boost_asio/example/cpp03/ssl/client.cpp

See https://pragmaticjoe.gitlab.io/posts/2015-02-13-boost.asio-https-client/ for more details.

The resulting application creates a connection to a specified server and path and make a GET request using a secure SSL connection.

Building (Linux):
```
cd <path to SimpleHttpsClient>
mkdir build
cd build
cmake -G "Unix Makefiles" ../
make
```

Once the binary is built try one of these

`https_client https://www.boost.org/LICENSE_1_0.txt`

`https_client http://info.cern.ch/index.html`
