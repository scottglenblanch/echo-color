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
echo 'source ${ECHO_COLOR_DIR}/src/terminal_setup/.echo.color.rc' >> ~/.bashrc
source ~/.bashrc
```


## Base Commands

```
echo.color.rgb "[red:int];[green:int];[blue:int]" [input:string]
```
```
echo.color.create
```

## Custom Color Commands        
```
echo.color.red [input:string]
```
```
echo.color.green [input:string]
```
```
echo.color.blue [input:string]
```

## Release History
* 0.0.2
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
