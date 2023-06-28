package main

import (
	"fmt"
	"strconv"
)

func main() {
	var str string
	var count int

	fmt.Print("Digite um número:")
	fmt.Scan(&str)

	for _, char := range str {
		if string(char) == "." {
			count += 1
		}
	}

	if count == 1 {
		if _, err := strconv.ParseFloat(str, 64); err == nil {
			fmt.Println("O numero informado pode ser um ponto flutuante!")
		} else {
			fmt.Println("O número informado não pode ser um ponto flutuante!")
		}

	} else {
		fmt.Println("O número informado não pode ser um ponto flutuante!")
	}
}
