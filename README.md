package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of metalHead-synthWave-cyberPunk-melomaniac-gearAddict-amateurMusician-traveler-foodLover-gamer-coder-programmer-catLover-sportsAficionado hybrid",
		"- 🔭 I’m currently working on":      "Tredicom as a Student at University --- Information of Technology & Computer Vision",
		"- 🌱 I’m currently learning":        "C++, C#, Python, Javascript, HTML, CSS",
		"- 👯 I’m looking to collaborate on": "Working",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Anything that you want haha",
		"- 📫 How to reach me:":              "- pthong901102@gmail.com - 20120201@student.hcmus.edu.vn",
	}
}

<!---
EdricJ/EdricJ is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
