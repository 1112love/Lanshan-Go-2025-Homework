LV1
package main

import "fmt"

func main() {
	const pi float32 = 3.14
	var r float32 = 5
	area := pi * r * r
	fmt.Println(area)
}
LV2
package main

import "fmt"

func main() {
	sum := 0
	for i := 1; i < 1001; i++ {
		sum += i
	}
	fmt.Println(sum)
}
LV3
package main 
import "fmt"
func factorial(n int )int {
	
	if n==0{
		
		return 1
}
return n*factorial(n-1)
}
func main() {
	result := factorial(n - 1)
	fmt.Println(result)
}
