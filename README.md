# Echo Color

Echo command to add some color into bash scripts.


## Support

### Script Interpreters
Current support is for bash.

## Installation

#### Unix Based

```
git clone https://github.com/scottglenblanch/echo-color.git echo-color
chmod -R +x ./echo-color
cd ./echo-color
echo "export ECHO_COLOR_DIR=$(pwd);" >> ~/.bashrc
source ~/.bashrc
echo "source ${ECHO_COLOR_DIR}/bin/echo.color.setup"
source ~/.bashrc
```


## Commands

* echo.color.rgb "[red:int];[green:int];[blue:int]" [output:string]
    * output color from rgb integers
    * quotes are needed in first input
* echo.color.red [output:string]
    * output color is red
* echo.color.green {{desired output}}
    * output color is green
* echo.color.blue {{desired output}}
    * output color is blue
* echo.color.lightblue {{desired output}}
    * output color is lightblue
* echo.color.yellow {{desired output}}
    * output color is yellow
* echo.color.orange {{desired output}}
    * output color is orange
* echo.color
    * command that other commands use

## Release History
* 0.0.1
    * Work in progress

## Meta

Scott Blanch – [@scottglenblanch](https://twitter.com/scottglenblanch) – scottglenblanch@gmail.com

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/scottglenblanch/initialize-base-scripts](https://github.com/scottglenblanch/)

## Contributing

1. Fork it (<https://github.com/scottglenblanch/initialize-base-scripts/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## Special Thanks
Special Thanks to [@wcspcbmt](https://github.com/wcspcbmt) for teaching me bash. My eyes have been opened to the power of the terminal. 
