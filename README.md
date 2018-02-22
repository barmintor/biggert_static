# Biggert Static Site

## Getting Started

### Set up

```sh
$ git clone https://github.com/cul/biggert_static.git && cd biggert_static
$ ruby _lib/export.rb > _data/biggert-items.json # to generate json from hyacinth csv
$ bundle
```
### Run the Rake processing tasks

#### Generate the collection markdown pages
```sh
$ bundle exec rake wax:pagemaster biggert
```
#### Generate json for the map markers
```sh
$ bundle exec rake markers
```
#### Generate the lunr index
```sh
$ bundle exec rake wax:lunr
```

### OR:

#### Run all of the above at once
```sh
$ bundle exec rake aota # generates pages, markers & the index
```


# Constant Data
| **key** 	| **value** 	|
|------------------	|------------------------------------------------------------------------	|
| `collection` 	| Biggert Collection of Architectural Vignettes on Commercial Stationery 	|
| `location` 	| Avery Architectural & Fine Arts Library, Columbia University 	|
| `sublocation` 	| Avery Classics Collection 	|
| `collector` 	| Biggert, Robert 	|
| `digital_origin` 	| reformatted digital 	|
