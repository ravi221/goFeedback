# #01: Hello World!
### Step #1: File and Folder Structure
-- rkFeedback
+ src     :  # Source code goes here
    - main  :  # main Package
        - web.go  :  # main entry file
+ bin     :  # Generated binary files and configuration settings goes here
+ pkg
+ Docs       :  # Documentation goes here
  - 01_hello.md
+ .gitignore
+ LICENCE
+ README.md
 
### Step #2:  Hello World!
File: **src/main/web.go**  
```go
package main
import "fmt"
func main() {
	fmt.Println("Hello, World!")
}
```

### Step #3:  Setting paths and running the program
- Open command prompt / terminal (in windows : Start -> Run -> cmd )
```sh
$ cd /e/rkFeedback/goFeedback
```
```sh
#  Linux / Unix / gitbash
$ export GOPATH=/e/rkFeedback/goFeedback
$ export GOBIN=/e/rkFeedback/goFeedback/bin
$ go run src/main/web.go
Hello, World!
```
