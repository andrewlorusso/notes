# ZSH (Each `##` will be a new file)

## Ideomatic Usage

**Premise**: Try and transition from a loop fork call to 

Transition from imperative loops to stream of data-flow model

**Not ideomatic**: manual state management

```zsh
for file in *; do 
  if...; then 
    var=...
  fi
done) and towards a declarative, 
```

**Ideomaic**

```zsh
(command1 | command2 | command3)
```

## ZSH Functions

### Lambdas

**Definition** Anonomus functions. 
First-Class Functions: Functions can be treated like data—stored in variables, passed to other functions, and stored in data structures.

**Syntax**
- `function { ... }` 
- `() { ... }`

```zsh

```
