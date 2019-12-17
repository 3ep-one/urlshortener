# Url Shortener

This package get long url and give back shorter url

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Require python3.7+



### Installing

installed with:

pip install urlshortener==1.0.0


End with an example of getting some data out of the system or using it for a little demo

## Running the tests

You can run test by :
python -m test


### And coding style tests

All code linted by flake8.

## Deployment
You should first set configs.
'db.ini' contain redis configuration
'handeler.ini' contain http listener configuration
'config.ini' contain url shortener configuration

After running the urlshortener you cabn send POST request JSON with format {"url": "www.eample.com/sddf324sdf"} and
recieve JSON response with format {"url" : "shorturl.com/asd"}

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


