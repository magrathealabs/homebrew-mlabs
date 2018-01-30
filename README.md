# Homebrew MLabs

A centralized repository for our custom brews.

## Requirements

* [Homebrew](https://github.com/Homebrew/brew)
* El Capitan, Sierra and High Sierra. Untested everywhere else.

## Installation

Run the following in your command-line:

```sh
$ brew tap magrathealabs/homebrew-mlabs
```

## Usage

Once the tap is installed, you can install the packages using the `brew install` command:

```sh
brew install chromedriver@2.35
brew install icu4c@58.1
```

That's it!

Please also follow the instructions from `brew info` at the end of the install to ensure you properly installed the package.

## Troubleshooting

First, please run `brew update` (twice) and `brew doctor`.

Second, read the [Troubleshooting Checklist](https://docs.brew.sh/Troubleshooting.html).

**If you don’t read these it will take us far longer to help you with your problem.**

## Homebrew documentation

`brew help`, `man brew`, [Homebrew/brew's README](https://github.com/Homebrew/brew#homebrew) or check [Homebrew's documentation](https://github.com/Homebrew/brew/tree/master/docs#readme).

## License

See [LICENSE](LICENSE).
