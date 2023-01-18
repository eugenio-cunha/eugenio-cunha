<h1 align="center">Hi there👋, I'm Eugênio Cunha</h1>

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

<h3 align="center">A Software developer. ⚡</h3>
<br>
<p align="center"> 
 <a href="https://www.linkedin.com/in/eugenio-cunha-68309315b/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;&nbsp;
</p>

<h3 align="center">Languages 🚀</h3>
<br>
<p align="center">
    <img  src="https://img.shields.io/badge/Kotlin-7f52ff?style=for-the-badge&logo=kotlin&logoColor=white">&nbsp;
    <img  src="https://img.shields.io/badge/Go-007F9f?style=for-the-badge&logo=go&logoColor=white">&nbsp;
    <img  src="https://img.shields.io/badge/JavaScript-fcba03?style=for-the-badge&logo=javaScript&logoColor=white">&nbsp;
</p>

<h3 align="center">Operating system Software ❤️</h3>
<br>
<p align="center">
<img  src="https://img.shields.io/badge/-LINUX-000000?logo=linux&logoColor=white&style=for-the-badge">
<img  src="https://img.shields.io/badge/-ANDROID-82d986?logo=android&logoColor=white&style=for-the-badge">
<img  src="https://img.shields.io/badge/-MacOS-5e9ef7?logo=apple&logoColor=white&style=for-the-badge">
</p>

<h3 align="center">Spotify 🎧</h3>
<br>
<p align="center">            
    <a href="https://github.com/kittinan/spotify-github-profile">
        <img align="center" src="https://spotify-github-profile.vercel.app/api/view?uid=genio.py&cover_image=true&theme=default&show_offline=false&bar_color=ff9300&bar_color_cover=false"/>
    </a>
</p>
