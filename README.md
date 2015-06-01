# Markdown with Pandoc and CMake

This project presents a basic thesis-template.
You need Pandoc and CMake installed.

For easy setup use [Homebrew](brew.sh) or checkout my [dotfiles-repository](https://github.com/gismo141/dotfiles).

Thanks to @jeetsukumaran for his [pandocology](https://github.com/jeetsukumaran/cmake-pandocology) for enabling the use of Pandoc via CMake.

## Usage

Clone this repo and its submodule:

```Bash
git clone git@github.com:gismo141/Markdown-CMake-Pandoc
cd Markdown-CMake-Pandoc
git submodule update --init --recursive
```

Create the build-folder and call `CMake`:

```Bash
mkdir build && cd build
cmake ..
make
```

If everything went well, you should have the resulting *.pdf in your `build`-folder.
You can now manipulate all files and folders to your likings!