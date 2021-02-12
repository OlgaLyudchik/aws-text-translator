# AWS Text Translator

This project uses the AWS Cloud9 environment to build a command-line tool with the Click command-line tool library and boto3 that translates text from automatically selected languages back to English. This uses the built-in AWS Comprehend natural language processing libraries.

## Usage
In the command prompt run the following command:

`python3 translate-cli.py`

You can directly specify which phrase you want to translate by passing the --phrase parameter:

`python3 translate-cli.py --phrase "Nur Ruhe bewahren und weitermachen."`
