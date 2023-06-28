package main

import (
	"fmt"
	"strconv"
)

func main() {

	var str string
	var count int

	count = 0

	fmt.Print("Digite uma string:")
	fmt.Scanln(&str)

	for _, num := range str {
		if _, err := strconv.Atoi(string(num)); err == nil {
			count++
		}
	}
	if count > 0 {
		fmt.Print("A string possui um numero!")
	} else {
		fmt.Print("A string não possui um numero!")
	}
}
