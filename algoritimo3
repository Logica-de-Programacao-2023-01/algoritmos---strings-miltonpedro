package main

import (
	"fmt"
	"strings"
)

func main() {
	var str, char, trocado string
	fmt.Print("Digite uma string:")
	fmt.Scan(&str)

troca:
	fmt.Print("Digite um caracter que sera substituido:")
	fmt.Scan(&trocado)
	if strings.Contains(str, trocado) == true {
		fmt.Print("Digite uma caracter que sera inserido no lugar do retirado:")
		fmt.Scan(&char)
	} else {
		fmt.Print("O caracter informado não esta presente na string!\n")
		goto troca
	}

	nova := strings.ReplaceAll(str, trocado, char)

	fmt.Print("A nova string ficou assim:", nova)
}
