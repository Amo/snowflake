## ⚠️ Heads up: Doctolib isn’t using this tool anymore, but you’re welcome to!

[Read more about our current thinking around engineer growth](https://Doctolib.engineering/engineering-growth-at-Doctolib-4935b3234d25).

# Snowflake

Snowflake is Doctolib's tool for planning and supporting our engineers' career development. You can read more
about how we use this tool in our [growth framework documentation](https://Doctolib.com/s/engineering-growth-framework).
Our growth tool is hosted [publicly](https://snowflake.Doctolib.com).

![The Lannisters send their regards](https://i.imgur.com/e9DYLBr.png)

## Contributions

You are free to use, change and build on this work to make it useful for your organisation. We will happily consider
unencumbered code contributions to improve functionality, but as this is the actual tool we use within Doctolib, acceptance is likely to be intentional, and deliberate. Meaning, slow. As such, you may prefer to fork the codebase for your own needs. We will not accept any contributions that modify the text of the application (but, thank you in advance for pointing out any typos).

## Installation

Get yarn if you don’t have it already:

`npm install -g yarn`

Install dependencies:

`yarn`

### Running the dev server

`yarn dev`

### Building

`yarn export`

This will put a static version of the site in `out/`.

## Future work

- Load initial data from a file, to improve flexibility.
- Add restricted job title selection and validation.
