# Halo

Halo is an interpretted programming language that interprets code written in the form of natural language. Halo is built on top of Python and so retains full backward compatibility with python and all of python's packages and libraries.

## ChatGPT Virtual Machine Runtime

Halo is a Virtual Program that only runs within an instance of the [ChatGPT](https://chat.openai.com/chat) Virtual Machine. See [Jonas Degrave's blog post ](https://www.engraved.blog/building-a-virtual-machine-inside/) for the prompts needed to boot one up within a ChatGPT session.

## Installation

To install Halo, simply run the following command:
```
{Halo is an interpretted programming language that interprets code written in the form of natural language. Halo is built on top of Python and so retains full backward compatibility with python and all of python's packages and libraries. The file extension for Halo source code is .halo. Halo can be installed with the command `pip install halo`}
pip install halo --quiet
```
## Example

To use Halo, you will need to create a file with the `.halo` extension and write your code in the form of natural language. For example:
```
echo "Do a google web search for the first command line argument. display the url, title and first paragraph of content for the top 3 results" > search.halo
```
Once you have written your code, you can run it using the `halo` command:
```
halo search.halo "Halo lang”
```
which prints
```
Searching for "Halo lang"...

1. https://halo-lang.org/
  - Halo lang: a natural language programming language
  - Halo is a programming language that interprets code written in the form of natural language. The goal of Halo is to make programming accessible to a wider audience by removing the need for users to learn a specific syntax.

2. https://www.github.com/halo-lang/halo
  - halo-lang/halo: A natural language programming language built on top of python.
  - Halo is an open-source, natural language programming language built on top of Python. It allows users to write code in the form of natural language, making it easier for non-programmers to get started with coding.

3. https://www.reddit.com/r/HaloLang/
  - r/HaloLang - A subreddit for the Halo programming language
  - This is a subreddit for the Halo programming language, a natural language programming language built on top of Python. Here, users can discuss the language, share code snippets, and get help with their projects.
```
## Contributions

We welcome contributions to Halo! If you have an idea for a new feature or have found a bug, please open an issue on our GitHub repository.
