package main

import (
	"fmt"
	"strings"
)

func main() {
	var str string

	fmt.Print("Digite uma string:")
	fmt.Scanln(&str)

	str = strings.ToUpper(str)

	chars := []rune(str)

	for i, j := 0, len(chars)-1; i < j; i, j = i+1, j-1 {
		chars[i], chars[j] = chars[j], chars[i]
	}

	reversedStr := string(chars)

	if str == reversedStr {
		fmt.Print("A string informada é um palíndromo!")
	} else {
		fmt.Print("A string informada não é um palíndromo!")
	}
}
