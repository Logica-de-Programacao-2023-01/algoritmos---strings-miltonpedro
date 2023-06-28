package main

import (
	"bufio"
	"fmt"
	"os"
	"strings"
)

func main() {
	var str string

	fmt.Print("Digite uma string qualquer:")
	reader := bufio.NewReader(os.Stdin)
	str, _ = reader.ReadString('\n')

	espaços := strings.ReplaceAll(str, " ", "")
	fmt.Println("O resultado da nova string é:", espaços)
}
