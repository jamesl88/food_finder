# Food Finder

This is a simple resturant finder written in `ruby 2.1.1`. It demontrates some of the fundamental basics of ruby such as:

* Accepting input from a user
* Outputing some results.
* If statements
* Case statements
* Iterators
* Loops
* Modules
* Class methods

The `resturants.txt` file is just the file which contains the records needed to display a list
If this file doesn't exist then a new file will be created when adding a new restaurant.

***

## Getting Started

Run the following command: `ruby init.rb`

Example output:
```
<<< Welcome to the Food Finder >>>

This is an interactive guide to help you find the food you crave.

Commands: 'list', 'add', 'find', 'quit'

>
```

## Commands

#### Add
`> add`

This command will accept input from the user which allows you to add to the current list of restaurants.
If `resturants.txt` doesn't exist then a new `resturants.txt` file will be created when adding a new restaurant.


#### List
`> list`

This command will display a list of resturants.
There is also a sortable command: `list cuisine` or `list by cuisine`

Example output:
```

                    LISTING RESTAURANTS

 Name                           Cuisine               Price
------------------------------------------------------------
 Burger King                    Fast Food             £6.00
 J Sheekey                      British              £25.00
 Kfc                            Fast Food             £6.00
 Masala Zone                    Indian               £12.00
 Nandos                         Portuguese           £10.00
 Wetherspoons                   Pub                  £10.00
------------------------------------------------------------
Sort using: '> list cuisine or '> list by cuisine'
```

#### Find

Find using a key phrase to search the restaurant list.
Examples: `find nandos`, `find portuguese`

`> find nandos`

Example output:
```
                     FIND A RESTAURANT

 Name                           Cuisine               Price
------------------------------------------------------------
 Nandos                         Portuguese           £10.00
------------------------------------------------------------
```

#### Quit

`> quit`

This will exit the program.

***

### Potential new features

* More columns options such as descretionary service charge or VAT
* Sortable columns in both ascending and descending order
