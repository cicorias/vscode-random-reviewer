# Random Reviewer (rr)
Picks a random name from the MAINTAINERS file in the local project.

## duties of rr
- initialize a toml file like this using the information from local git config 

```toml

[people]
    [people.cicorias]
        name = "Shawn Cicoria"
        email = "github@cicoria.com"
        login = "cicorias"
        current = true
        [areas]


    [people.bradrydzewski]
        name = "Linda Ortega"
        email = "linda.ortega@mail.com"
        login = "lindaortega"

    [people.mattnorris]
        name = "Matt Norris"
        email = "matt.norris@mail.com"
        login = "mattnorris"
```


### gitconfig sample entries
the following is what a git config file has once a user has run `git config --global user.name` and `git config --global user.email`.  This can be retrieved 

```toml
 $ cat ~/.gitconfig
[user]
	name = Shawn Cicoria
	email = github@cicoria.com

```