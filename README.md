# LaTeX Thesis Template

Welcome to the LaTeX Thesis Template! This template is designed to help you create a professional and well-structured thesis document with ease. Below are the instructions to get you started.

## Installation

### Step 1: Install LaTeX

To use this template, you need to have LaTeX installed on your system. Follow the steps below to install LaTeX:

#### Windows

1. Download and install [MiKTeX](https://miktex.org/download).
2. During installation, make sure to select the option to install missing packages automatically.

#### macOS

1. Download and install [MacTeX](https://tug.org/mactex/mactex-download.html).

#### Linux

1. Install TeX Live by running the following command in your terminal:
  
  ```sh
  sudo apt-get install texlive-full
  ```
  

### Step 2: Install Latexmk

Latexmk is a Perl script that simplifies the process of building LaTeX documents. To install Latexmk, follow these steps:

#### Windows

1. Open the MiKTeX Console.
2. Go to the "Packages" tab.
3. Search for "latexmk" and install it.

#### macOS

1. Open a terminal.
2. Run the following command to install Latexmk:
  
  ```sh
  sudo tlmgr install latexmk
  ```
  

#### Linux

1. Open a terminal.
2. Run the following command to install Latexmk:
  
  ```sh
  sudo apt-get install latexmk
  ```
  

## Modifying General Settings

The template allows you to customize various settings such as your name, thesis title, and more. To modify these settings:

1. Open the `styling/settings.tex` file in your favorite text editor.
2. Update the custom settings with your information.

## Example Chapters

To see how to format your chapters and use various features of this template, refer to `chapter1.tex`. This file contains examples of different sections, figures, tables, and references to help you get started.

## Building Your Thesis

Once you have installed LaTeX and Latexmk, and customized the settings, you can compile your thesis using the following command in your terminal:

```sh
latexmk -pdf main.tex
```

This command will generate a PDF of your thesis, including all chapters and references.

## Additional Resources

For further assistance with LaTeX, consider the following resources:

- [Overleaf Documentation](https://www.overleaf.com/learn)
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)

Happy writing!