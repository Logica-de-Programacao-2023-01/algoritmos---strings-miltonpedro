package main

import (
	"bufio"
	"fmt"
	"os"
	"strings"
)

func main() {
	scanner := bufio.NewScanner(os.Stdin)

	fmt.Print("Digite uma string:")
	scanner.Scan()

	str := scanner.Text()
	str1 := strings.Count(str, " ") + 1
	fmt.Print("A quantidade de palavras da string informada é: ", str1)
}
