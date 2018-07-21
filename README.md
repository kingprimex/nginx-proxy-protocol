# Project Title

Adding proxy-protocol support for nginx TCP STREAM + Allowing specific IP after TCP BALANCING

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. "@Development Tools"
2. "openssl-devel"
3. "zlib-devel"
4. "pcre-devel"

```
Give examples
```

### Installing

1. ```yum install openssl-devel zlib-devel pcre-devel```
2. ```yum groupinstall "Development Tools"```
3. ```wget http://nginx.org/download/nginx-1.14.0.tar.gz```
4. ```tar -xvf nginx-1.14.0.tar.gz && cd nginx-1.14.0```
5. ```
./configure --with-http_ssl_module \
         --with-stream_realip_module \
         --with-http_realip_module \
         --with-stream \ 
         --with-stream_ssl_module\
         --with-stream_ssl_preread_module```
6. ```make && make install```

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* shell commands
* skill
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [git](https://git.com/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Codrut Predoi** - *Initial work* - [kingprimex](https://github.com/kingprimex)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
