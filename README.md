# Mandelbrot Set

This is a repo for the Mandelbrot bitmap building project of math soft lecture.

The code is mainly from [@wangheyu](https://github.com/wangheyu) and slightly modified by me. ~~Ignore his typo:dog:~~

## How to use

### Compile & run

You can generate a bmp file with the following command under directory `/src`

```shell
./run.sh filename ox oy dimension
```

by which you'll create a bitmap image called _filename_ with the origin point of the complex plain on location(_ox_, _oy_), and the window size _dimension_.

### Compile $\LaTeX$ files

Just run the following command under directory `\doc`

```shell
make report
```

and you'll generate a `hw4.pdf` file under the same directory, which is my essay.

## Want to know more?

My essay is in the directory `/doc`, with both `.tex` files and the generated `.pdf` file.

