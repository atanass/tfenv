Just a simple script for switching local terraform versions

## Prerequisites
- wget, unzip, curl
- put `tfenv` in your $PATH


## Usage

`tfenv` - shows currently installed versions
`tfenv <version>` - use specific version.

## Behind the scenes

- If there is no terraform installed, the initial invocation will install version 0.14.0.
- If the version in the argument is not locally installed it will be downloaded.
- Terraform versions are stored in `/usr/local/bin/` and controlled with a symbolic link.