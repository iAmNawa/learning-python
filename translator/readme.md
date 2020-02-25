$ translate-cli --help
Usage: __main__.py [OPTIONS] TEXT...

  Python command line tool to make on line translations

  Example:

       $ translate-cli -t zh the book is on the table
       碗是在桌子上。

  Available languages:

       https://en.wikipedia.org/wiki/ISO_639-1
       Examples: (e.g. en, ja, ko, pt, zh, zh-TW, ...)

Options:
  --version                 Show the version and exit.
  --generate-config-file    Generated the config file using a Wizard and exit.
  -f, --from TEXT           Sets the language of the text being translated.
                            The default value is 'autodetect'.
  -t, --to TEXT             Sets the language you want to translate.
  -p, --provider TEXT       Set the provider you want to use. The default
                            value is 'mymemory'.
  --secret_access_key TEXT  Set the secret access key used to get provider
                            oAuth token.
  -o, --output_only         Set to display the translation only.
  --help                    Show this message and exit.
