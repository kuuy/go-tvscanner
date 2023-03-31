# go-tvscanner
TradingView scanner api client

## Usage
~~~ go
package main

import (
	scanner "github.com/kuuy/go-tvscanner"

	"fmt"
)


func main() {
	fmt.Println("Starting")
	cl := scanner.New()
	cl.GetAnalysis("crypto", "BITTREX", "BTCUSD", "1h")
}
~~~