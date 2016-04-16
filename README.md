# ponyride

###### A utility script for reposting products on [Carousell](https://carousell.com).

### Requirements
* [Python 2.7](https://www.python.org/downloads/)
* [Firefox](http://firefox.com/)

### Installation
* `git clone https://github.com/kyleoliveiro/ponyride`
* `pip install splinter`

### Usage
`./ponyride -u <username> -p <password> -f <product_list>`

### Options
	-u, --username <username>
	-p, --password <password>
	-f, --file <product_list>

### Product List
To let ponyride know which items to repost, create a `.txt` file in the `/lists/` directory containing product ID's one per line). The file can also contain comments, indicated with a `#` character at the beginning of the line.

Whenever the ponyride script is executed, the product list file that it uses is automatically updated with the new product ID once a product is successfully posted and deleted.

This means that you won't have to manually update your product list file unless you want to include more items or exclude certain items from being reposted.

###### Example Product List

	# /lists/shirts.txt

	# Hawkings McGill Checkered Shirt
	38974461

	# Calvin Klein Long Sleeved Striped Black Shirt
	38974508

	# Topman Long Sleeved Striped Grey Shirt
	38974561

### Changelog
* **16 April 2015:** Compatibility fixes
* **29 December 2015:** Initial release
