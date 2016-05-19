# Homebrew Core
Core formulae for the Homebrew package manager.

## How do I install these formulae?
Just `brew install <formula>`. This is the default tap for Homebrew and is installed by default.

### Installing older formulae
To install an older version of a package, use `brew install <url>`, where `<url>` is the path to the raw formula for that package, at the version you want. For example, the following command will install elasticsearch 2.0.0:

`brew install https://raw.githubusercontent.com/Homebrew/homebrew-core/935d360323965ec31beec774b64d52778c41afdf/Formula/elasticsearch.rb`

If you do not find the version of a package you need in [homebrew-core](https://github.com/Homebrew/homebrew-core), try checking [legacy-homebrew](https://github.com/Homebrew/legacy-homebrew).

## Troubleshooting
First, please run `brew update` (twice) and `brew doctor`.

Second, read the [Troubleshooting Checklist](https://github.com/Homebrew/brew/blob/master/share/doc/homebrew/Troubleshooting.md#troubleshooting).

**If you don’t read these it will take us far longer to help you with your problem.**

## Contributing
Read [CONTRIBUTING.md](/.github/CONTRIBUTING.md).

Creating new formulae, updating existing ones, and fixing build issues is easier than you think!

Try `brew edit $FORMULA` and see how you fare.

## Documentation
`brew help`, `man brew`, [Homebrew/brew's README](https://github.com/Homebrew/brew#homebrew) or check [Homebrew's documentation](https://github.com/Homebrew/brew/tree/master/share/doc/homebrew#readme).

## License
Code is under the [BSD 2 Clause (NetBSD) license](https://github.com/Homebrew/homebrew-core/blob/master/LICENSE.txt).
