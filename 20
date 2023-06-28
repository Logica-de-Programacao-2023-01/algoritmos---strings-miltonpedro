package main

import (
	"fmt"
	"strings"
)

func main() {
	var str string

	fmt.Print("Digite uma string:")
	fmt.Scanln(&str)

	maiusculas := "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
	minusculas := "abcdefghijklmnopqrstuvwxyz"

	quantidade := len(str)
	if strings.HasPrefix(str, maiusculas) || strings.HasPrefix(str, minusculas) {
		if strings.HasSuffix(str, minusculas) {
			fmt.Println("A string informada não está em camelCase")
		} else {
			fmt.Println("A string informada está em camelCase")
		}
		fmt.Println("A quantidade de letras é:", quantidade)
	}

}
