# DotEnv configure

Interactively configure your .env files. Without schema, just use your .env or .env.example as
schema!


## Installation

npm install --save [--global] dotenv-configure 


## Usage:

`dotenv-configure <file> [output]`

For in place editing:
`dotenv-configure .env`

For example -> output editing:
`dotenv-configure .env.example .env` 



## Tips & Tricks:

Add this to your project's package.json:

```
"scripts" : {
    "configure" : "dotenv-configure .env.example .env"
}

```

And run npm run configure after updating your code.


