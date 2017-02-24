# cli-weather

> cli-weather package

**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Package Presentation](#Package Presentation)
- [Requirements](#Requirements)
- [Package Installation](#Package Installation)
- [How to use it?](#How to use it?)
- [Licence](#licence)

##Presentation

This package gives the weather and temperature of a town you specify.

##Requirements

Have "node.js" installed on your machine. You can get it [here](https://nodejs.org/en/).

##Package Installation
- Download this pakage, clicking the button "Clone or download" available [here](https://github.com/92bondstreet/rdd-cdd-tdd).

- Open your terminal and go to the package directory with the command :
```sh
cd directory_name/weather
```
- Install all dependencies of the package using the command :
```sh
npm install
```
It will install all depedencies that are in the "package.json" file.


##How to use it
- Go to the package directory from the terinal, use the command :
```sh
cd directory_name/weather
```
- Run cli.js using the command :
```sh
node cli.js
```
```
Dhaka, Bangladesh
Condition: Clear
Temperature: 22C
```

By default the program gives the weather of Dhaka, Bangladesh in celcius. 

If you want another town, write the name and the country of the town after "node cli.js". Example :
```sh
node cli.js Paris France
```

```
Paris, France
Condition: Mostly Cloudy
Temperature: 8C
```

Warning: don't forget the capital letters of the names.

If you want the temperature in Farenheit, write F at the end of the command. For example :
```sh
node cli.js Paris France F
```
```
Paris, France
Condition: Mostly Cloudy
Temperature: 49F
```


If you want help, use :
```sh
node cli.js --help
```

```
Check the weather for your city from your terminal
Usage
$ weather <input>
Options
city [Default: Dhaka]
country [Default: Bangladesh]
scale (C/F) [Default: Celcius]

Examples
$ weather London UK C
London, UK
Condition: Partly Cloudy
Temperature: 32C
```


## Licence
[Uncopyrighted](http://zenhabits.net/uncopyright/)
