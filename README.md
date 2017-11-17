# LSU-Latex-Beamer
A Latex template using Beamer class for LSU dissertation/thesis defense presentation.

This template uses Berlin Beamer theme and [tigers][] colortheme.

## Prerequisites
A reasonably up-to-date and working TeX distribution is required to be installed on your local laptop/computer. The only
officially supported distributions are [TeX Live][], and [MiKTeX][]. Although,
the latter is not as well tested and supported as TeX Live, hence using TeX Live
is highly recommended.

## Installation 
Clone the repository from github. For example, we clone LSU-Latex-Beamer to $HOME/LSU-Latex-Beamer:
  ```sh
  $ cd $HOME
  $ git clone https://github.com/shuzhan2015/LSU-Latex-Beamer.git
  ```

## Usage
The following commands assume you are using Linux/MacOS. You can type bash command using a terminal emulator Putty if you are using Windows.

1. Edit the `slides.tex` file to your liking:
  ```sh
  $ cd $HOME/LSU-Latex-Beamer
  $ vim slides.tex
  ```
2. Run the `make` command to generate the pdf and delete all the other intermediate/temporary files:
  ```sh
  $ make
  ```
3. You can then view the pdf file and make further changes if you need

<!--refs-->
[MiKTeX]: http://miktex.org/
[TeX Live]: https://www.tug.org/texlive/
[tigers]: http://www.alexpacheco.net/LSUBeamer/
