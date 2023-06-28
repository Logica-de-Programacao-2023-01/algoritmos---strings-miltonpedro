package main

import (
	"fmt"
	"sort"
	"strings"
)

func main() {
	var str1, str2 string

	fmt.Print("Digite uma string:")
	fmt.Scanln(&str1)
	fmt.Print("Digite uma string:")
	fmt.Scanln(&str2)

	str1 = strings.ToLower(str1)
	str2 = strings.ToLower(str2)

	chars1 := strings.Split(str1, "")
	chars2 := strings.Split(str2, "")

	sort.Strings(chars1)
	sort.Strings(chars2)

	sortedStr1 := strings.Join(chars1, "")
	sortedStr2 := strings.Join(chars2, "")

	if sortedStr2 == sortedStr1 {
		fmt.Println("As duas strings informadas são anagramas!")
	} else {
		fmt.Println("As strings informadas não são anagramas!")
	}
}
