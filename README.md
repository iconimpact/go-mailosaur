# Mailosaur Go Client Library

[Mailosaur](https://mailosaur.com) allows you to automate tests involving email. Allowing you to perform end-to-end automated and functional email testing.

Feel free to add new functions or improve the existing code.

## Install

```bash
go get github.com/iconmobile-dev/go-mailosaur
```

## Documentation and usage examples

[Mailosaur's documentation](https://mailosaur.com/docs) includes all the information and usage examples you'll need.

## Running tests

Once you've cloned this repository locally, you can simply run:

```
export MAILOSAUR_API_KEY=your_api_key
export MAILOSAUR_SERVER=server_id

go test ./... -v -count=1
```


## How to Contribute

This project is maintained by [Sebastian Kreutzberger (@skreutzberger)](https://github.com/skreutzberger)

Please create a pull request which fulfills the following conditions:

1. is of general interest and to be used in more than one project
2. includes a README file which documents the purpose, each public function with an example and how to run and test it
2. contains inline code comments which make it clear what the logic does (the more comments the better)
3. has a unit test code coverage of at least 90%
4. does not violate any patents or copyrights
5. has the Apache 2.0 copyright statement at the top of each file with icommobile GmbH as copyright holder

<br>


## License
This project is licensed under the Apache 2.0 License (see file `LICENSE`).

<br>

## Copyright
© 2020 iconmobile GmbH