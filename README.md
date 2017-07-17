# How to build the whitepaper
## Install LaTeX
### Windows
1. Download [MiKTeX](https://miktex.org/download)
2. Run the basic MiKTeX installer (see [step-by-step guidance.](https://miktex.org/howto/install-miktex))
3. Open Command Prompt by clicking Start and then typing “cmd” into the search box.
4. You can determine which version is installed by typing`pdflatex --version`

### MacOS
Install MiKTeX via Homebrew package manager (see [step-by-step guidance.](https://miktex.org/howto/install-miktex-mac)):

1. Start Terminal
2. Run `brew tap miktex/miktex`
3. Run `brew install miktex`
3. Start a new Terminal
4. You can determine which version is installed by typing`pdflatex --version`
 	
### Linux (Ubuntu or Debian)
1. Open a terminal
2. Enter the following command: `sudo apt-get install texlive-full`
3. Open a terminal
4. You can determine which version is installed by typing`pdflatex --version`

## Compile whitepaper
1. Open Command Prompt/Terminal
2. Enter the following commands 
   * `cd whitepaper`
   * `pdflatex main.tex`
   * `pdflatex main.tex`
   * `pdflatex main.tex`
3. Open the whitepaper `main.pdf`

You have to run the `pdflatex` command three times to make the table of contents and the index complete.

