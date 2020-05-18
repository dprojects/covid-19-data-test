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

### for Hopkins data source:     
    
    firefox ./indexHopkins.html
    
# License

MIT
