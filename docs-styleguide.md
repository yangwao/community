# Documentation Styleguide

This is the documentation styleguide for our natural language descriptions used in the CLI tools, and elsewhere. Please conform to this spec.

## Code references

* Use `backticks` for every code example inside of a normal description. In the CLI, where you cannot use backticks, use 'single quotes' for commands.
* Default settings should always be specified in a new sentence, not in parentheses, at the end. Default: like this.
* For command line arguments, do not include a `$` before commands in man pages. A `$` may be included in READMEs.

### Acronyms

* IPFS is always capitalized if it is not referring to an `ipfs` CLI command.
* DAG is always capitalised unless it is used in the first instance.

#### Accepted forms:

- merkle-dag
- trickle-dag

## Linguistic rules

* End phrases with a period. (Like that one).
* Capitalize the first letter of a phrase or sentence.

## Headings

* Single word headings in man pages should be capitalized. They should not be followed by a colon. Enumerated examples:
  - `EXAMPLES`
  - `NOTES`
  - `WARNING`
