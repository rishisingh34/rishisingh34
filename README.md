
# Hey there, I'm Rishi 👋  

### About Me  

<img src="https://raw.githubusercontent.com/golang-samples/gopher-vector/master/gopher.png" width="90" align="right" alt="Gopher" />

```go
package main

import "fmt"

type Developer struct {
	Name       string
	Languages  []string
	Currently  string
	AskMeAbout []string
}

func (d Developer) Introduce() {
	fmt.Printf("Hey, I'm %s 👋\n", d.Name)
	fmt.Println("I love creating performant systems and scalable apps.")
	fmt.Printf("Currently exploring: %s\n", d.Currently)
	fmt.Printf("Ask me about: %v\n", d.AskMeAbout)
}

func main() {
	rishi := Developer{
		Name:       "Rishi Raj Singh",
		Languages:  []string{"Go", "TypeScript", "JavaScript"},
		Currently:  "Next.js and Golang internals",
		AskMeAbout: []string{"Node.js", "React", "Express", "MongoDB", "Redis"},
	}

	rishi.Introduce()
}
````

---

### 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=rishisingh34\&theme=tokyonight\&hide_border=false\&include_all_commits=true\&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=rishisingh34\&theme=tokyonight\&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=rishisingh34\&theme=tokyonight\&hide_border=false\&include_all_commits=true\&count_private=true\&layout=compact)

---

[![](https://visitcount.itsvg.in/api?id=rishisingh34\&icon=0\&color=0)](https://visitcount.itsvg.in)
