# Description

Useful for data testing, shows invalid values, e.g. for "Poland" at date 
"2020-3-18" is 13 recovered and next day at "2020-3-19" there is only 1 recovered. 

The idea behind this tool is very simple. Just set last value as max and search 
all higher values (invalid) and shift the max if value is lower (valid).

So to use this tool, make sure the last value is valid.

# Install

    git clone https://github.com/dprojects/covid-19-data-test.git

# Usage

    cd ./covid-19-data-test
    
### for pomber data source: 

    firefox ./index.html

> ![screen1](https://github.com/dprojects/covid-19-data-test/blob/master/screen1.png)
    
    
### for Hopkins data source:     
    
    firefox ./indexHopkins.html

> ![screen2](https://github.com/dprojects/covid-19-data-test/blob/master/screen2.png)

### for diff Pomber vs Hopkins:     
    
This show different values in [Pomber](https://pomber.github.io/covid19/timeseries.json) source.
        
    firefox ./indexDiff.html

> ![screen3](https://github.com/dprojects/covid-19-data-test/blob/master/screen3.png)
    
# License

MIT
