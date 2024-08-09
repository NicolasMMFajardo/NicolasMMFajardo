<h2 align="center">About Me </h2>

```go

package NicolasMMFajardo

func getAttributes() (Contact, Life, Coding) {
	contact := Contact{
		Email:   "nicolasfajardo123@gmail.com",
		Discord: "nicofajardo",
	}

	life := Life{
		Name:    "nicolas",
		Alias:   "nick",
		Langs:   []string{"english", "portuguese"},
		Country: "br",
		Age:     20,
	}

	coding := Coding{
		Langs: map[string][]string{
			"expert":       {"c++, python"},
			"intermediate": {"c#"},
			"hasExperience": {"c++", "python"},
		},
		Databases:    []string{"sql server", "mysql", "sqlite"},
		Specialities: []string{"fullstack", "software engineering", "apis"
		,"games"},
		Ide:          []string{"vscode", "visual studio"},
	}

	return contact, life, coding
}
```

<h2 align="center">Skills </h2>

<div align="center">
  <a href="https://skillicons.dev" style="display: inline-block; margin-right: 20px;">
    <img src="https://skillicons.dev/icons?i=dotnet,c,cpp,cs" />
  </a>
  <a href="https://skillicons.dev" style="display: inline-block;">
    <img src="https://skillicons.dev/icons?i=postgres,mysql,vscode,visualstudio" />
  </a>
</div>

<p></p>
