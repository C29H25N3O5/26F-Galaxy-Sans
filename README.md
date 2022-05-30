# 26F-Galaxy-Sans

# 26F Galaxy Sans

# ***NOTICE: This typeface is currently under development and has not been finished yet.***

26F Galaxy Sans is an open-source typeface featuring elements from space and the universe. It is designed for the game [Techmino Galaxy](https://github.com/26F-Studio/Techmino_Galaxy) (which is currently under development).

## Features (Planned)

- Multiple weights
  
- Variable fonts
  
- Some OpenType Features
  

## Build from source

You can either build the fonts from Glyphs or other font editing programs directly, or you can choose to build them in the command line using the Google Font Tools (`gftools`). Notice that you have to install Python 3.7 or later to use `gftools`.

1. Install `gftools` by executing the following command:
  
  ```
  $ pip install gftools
  ```
  
2. Navigate to `../Source/glyphs/` in the command line.
  
3. Execute the following command:
  
  ```
  gftools builder config.yaml
  ```
  
4. Find the compiled fonts in the `fonts` folder.
  

## License

26F Galaxy Sans is under a [SIL Open Font License, Version 1.1](https://github.com/26F-Studio/26F-Sans/blob/main/OFL.txt). You can use, modify, redistribute the compiled fonts and the source files free of charge and you do not need to attribute to 26F Studio (But we would really appreciate that if you do so).

The [build.yml](https://github.com/26F-Studio/26F-Sans/blob/main/.github/workflows/build.yml) files was adapted from the [JetBrains Mono Repository](https://github.com/JetBrains/JetBrainsMono/blob/master/.github/workflows/build-fonts.yml), which was under a [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

The other part of the source code in this repository is under a [MIT License](https://github.com/26F-Studio/26F-Sans/blob/main/MIT.txt).
