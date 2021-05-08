# NGINXER
Simple tool to automate nginx user creation for HTTP Basic Authentication.

## Usage
´´´bash
nginxer [OPTIONS]
Example: nginxer -u se -p oye -f meoye

OPTIONS
  -u USERNAME      Username for the new user.
  -p PASSWORD      Password for the new user.
  -f FILE          File where to write the new user:passwd.
                    Note that if file does not exist, it will
                    create it.
  -h               Prints this help menu.
´´´

If any of the flags (except -h) is missing, you'll be prompted to introduce it

## Requirements
* openssl
