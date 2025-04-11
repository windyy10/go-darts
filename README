# darts
移植于[go-darts](https://github.com/awsong/go-darts)
原代码本身存在越界的错误, 进行了修复

## 关于 darts
This is a GO implementation of Double-ARray Trie System. It's a clone of the [C++ version](http://chasen.org/~taku/software/darts/)

## 示例 详细使用参考[example](./example)

```go
package main

import (
	"fmt"

	"github.com/windyy10/go-darts"
)

func main() {
	d, err := darts.Import("darts.txt", "darts.lib", true)
	if err == nil {
		if d.ExactMatchSearch([]rune("考察队员"), 0) {
			fmt.Println("考察队员 is in dictionary")
		}
	}
}
```