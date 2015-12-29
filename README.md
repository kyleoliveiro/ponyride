# ponyride

### A utility script for reposting products on [Carousell](https://carousell.com).

## Requirements
* [Python 2.7](https://www.python.org/downloads/)
* [Firefox](http://firefox.com/)

## Installation
* `git clone https://github.com/kyleoliveiro/ponyride`
* `pip install splinter`

## Example Usage
`./ponyride -u <username> -p <password> -f <product_list.txt>`

## Options
	-u, --username <username>
	-p, --password <password>
	-f, --file <product_list.txt>

## Product List
To let ponyride know which items to repost, create a `.txt` file
containing product ID's (one per line). The file can also contain
comments, indicated with a `#` character at the beginning of the line.

### Example product_list.txt

	# Hawkings McGill Checkered Shirt (XS)
	38974461

	# Calvin Klein Long Sleeved Striped Black Shirt (XS)
	38974508

	# Topman Long Sleeved Striped Grey Shirt (XS)
	38974561

## Changelog
* **29 December 2015:** Initial release