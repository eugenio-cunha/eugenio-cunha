<h1 align="left">Hi there👋, I'm Eugênio Cunha</h1>
<h3 align="left">A Software developer. ⚡</h3>

```go
package main

import (
	"playground/profile"
)

func main() {
	me := profile.NewBio("Eugenio Cunha")
	stack := profile.NewStack(
		[]string{"Go", "Kotlin", "JavaScript"},
		[]string{"Postgres", "SQLite", "MongoDB", "Redis"},
		[]string{"Linux", "Android", "MacOS"},
		[]string{"AWS", "Docker", "Jetpack Compose"},
		[]string{"Rust", "RNN", "English"}
	)
	_ = me
	_ = stack
}

-- go.mod --

module playground

-- profile/profile.go --

package profile

type Bio struct {
	Name string
}

type Stack struct {
	languages []string
	databases []string
	os        []string
	misc      []string
	ongoing   []string
}

func NewBio(name string) *Bio {
	return &Bio{name}
}

func NewStack(languages, databases, os, misc, ongoing []string) *Stack {
	return &Stack{languages, databases, os, misc, ongoing}
}
```

<pre>
██╗    ██╗███████╗██╗      ██████╗ ██████╗ ███╗   ███╗███████╗
██║    ██║██╔════╝██║     ██╔════╝██╔═══██╗████╗ ████║██╔════╝
██║ █╗ ██║█████╗  ██║     ██║     ██║   ██║██╔████╔██║█████╗  
██║███╗██║██╔══╝  ██║     ██║     ██║   ██║██║╚██╔╝██║██╔══╝  
╚███╔███╔╝███████╗███████╗╚██████╗╚██████╔╝██║ ╚═╝ ██║███████╗
 ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
</pre>

<br>
<p align="center"> 
 <a href="https://www.linkedin.com/in/eugenio-cunha-68309315b/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
</p>

<h3 align="center">Spotify 🎧</h3>
<br>
<p align="center">            
    <a href="https://github.com/kittinan/spotify-github-profile">
        <img align="center" src="https://spotify-github-profile.kittinanx.com/api/view?uid=genio.py&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false)](https://github.com/kittinan/spotify-github-profile"/>
    </a>
</p>
