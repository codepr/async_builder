# async_builder
A simple asynchronous .tex compiler with concise error output, i was tired of scanning all logs for errors in tex compilation with
pdflatex, this allow to parallelyze the compilation of lot of .tex and get a concise error report by line number.

## Usage

```pl
async_build path/to/.tex
```

If no arguments are specified it build all .tex recursively found on current directory.

## License

See the [LICENSE](LICENSE) file for license rights and limitations (MIT).
