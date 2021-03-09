# πzip, the most awesome compression software

πzip is the most awesome compression software in the whole history of mankind. It uses the decimals of pi as table of probabilities. Since π is a disjunctive sequence, all the possible data are in it. This software uses this property of π to store everything that can exist.

## Getting Started

Just download πzip and πunzip and make them executable. πzip and πunzip are Python scripts and works only on Linux or compatibles systems. They need bash and bc.

## How does it work

Two scripts are needed: 
* πzip to compress files
* πunzip to decompress files

Usage of πzip:
πzip INPUT_FILE [π_SIZE]

π_SIZE is the size of the table of probabilities. It must be at least 2330 to cover all possible input datas. It's default value is 2330.

Usage of πunzip:
πunzip INPUT_FILE

## Benchmark

I downloaded several compressions software and use them to compress a tar file containing the source code of bc.

| Compression software | Size after compression | Compression time | Compression ratio | Awesomeness level |
|:--------------------:|:----------------------:|:----------------:|:-----------------:|:-----------------:|
| None                 | 1550 KB                | 0 s              | 0 %               | 1                 |
| zip                  | 414 KB                 | 0.12 s           | 73 %              | 0                 |
| gzip                 | 414 KB                 | 0.11 s           | 73 %              | 7                 |
| 7zip                 | 298 KB                 | 0.28 s           | 81 %              | 42                |
| πzip                 | 8929 KB                | 702 s            | -476%             | OVER 9000         |

## Website

[πzip.com](https://πzip.com/)

## Author

* **Me** - [Fivox](https://github.com/fivox)

## License

This project is licensed under the WTFPL License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

Thanks to Archimedes without whom none of this would have been possible.

Thanks to the Unicode Consortium, allowing me to increase the awesomeness of these scripts by adding the character π everywhere.

Thank to my company. By giving me useless and uninteresting projects they motivated me to make these scripts on my work time.

Thanks to [Sam et Max](http://sametmax.com/) who introduced me to Python (given the quality of my code, I'm not sure it's a compliment).
