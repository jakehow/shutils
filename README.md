# shutils

Catch all for utilities to handle missing Shopify API functionality.

## Requirements

This has been tested with Node v12.13.1, NPM 6.12.1, and yarn 1.19.2

## Setup

1. Clone the repo

`git clone git@github.com:jakehow/shutils.git`

2. Install dependencies

```shell
cd shutils
yarn
```

3. Run the command

```shell
./shutils -h
```

### Available commands

### Upload

Uploads a file to the settings/files are of the Shopify Admin.  This process uses headless chrome and creates a session for each file you upload, so may trigger reCaptcha.  A future version may take a list of files to upload in order to mitigate this issue and upload multiple files for one session.

Usage: `./shutils upload $FILEPATH -s $SHOP_NAME -u $USERNAME -p $PASSWORD`


