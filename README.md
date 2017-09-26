# Image Search Abstraction Layer

Full stack JavaScript service that allows you to search for images . A [FreeCodeCamp](https://www.freecodecamp.org/challenges/image-search-abstraction-layer) project.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing

```
git clone https://github.com/kelvinabella/image-search-abstraction-layer.git
cd image-search-abstraction-layer
create .env file and connect to your mongodb
yarn install
yarn start
```

### Usage

```
User stories:

I can get the image URLs, alt text and page urls for a set of images relating to a given search string.
I can paginate through the responses by adding a ?offset=2 parameter to the URL.
I can get a list of the most recently submitted search strings.
```

```
Usage:
https://cryptic-ridge-9197.herokuapp.com/api/imagesearch/lolcats%20funny?offset=10
https://cryptic-ridge-9197.herokuapp.com/api/latest/imagesearch/
```

## License

This project is licensed under the MIT License.

## Acknowledgments

*FreeCodeCamp
