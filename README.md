<h1 align="center">quotes-cli</h1>
<div align="center">
 <strong>
   使用命令行获取股票行情、股票列表等信息
 </strong>
</div>
<div align="center">

<img src="https://github.com/Yangzhenzhao/quotes-cli/workflows/CI/badge.svg" />
 
</div>


### Installation

#### MacOS

```
tar xf quotes-cli-v0.1.0-x86_64-apple-darwin.zip
cd quotes-cli-v0.1.0-x86_64-apple-darwin
sudo mv quotes-cli /usr/lcal/bin
sudo chmod +x /usr/loca/bin/quotes-cli
quotes-cli -h
```

#### Linux

```
unzip quotes-cli-v0.1.0-x86_64-unknown-linux-musl.zip
cd quotes-cli-v0.1.0-x86_64-unknown-linux-musl
sudo mv quotes-cli /usr/local/bin
sudo chmod +x /usr/local/bin/quotes-cli
quotes-cli -h
```


### Command-line options


```bash
USAGE:
    quotes-cli [OPTIONS]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -c, --current_price <code>    Sets a code to get current price
    -o, --open <code>             Sets a code to get open price
    -p, --pct_change <code>       Sets a code to get pct change
    -P, --pre_close <code>        Sets a code to get pre close price
    -t, --tick <code>             Sets a code to get tick
```

### Examples

```bash
$ quotes-cli -p sh000905
-0.27%

$ quotes-cli -c 000001  
18.36

$ quotes-cli --pre_close 000001
18.95
```

