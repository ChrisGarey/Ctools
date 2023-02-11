# Cosmo's Crypt Tools

Cosmo's Crypt Tools is a bash script that provides a simple and easy-to-use command line interface for encrypting and decrypting files using OpenSSL. It also includes an option to generate a random 12-character password.

**Requirements**

In order to use Cosmo's Crypt Tools, you need to have the following installed on your system:

*   OpenSSL

**Usage:**

## Installation

To install Cosmo's Crypt Tools, follow the steps below:

1. Clone the repository or download the ZIP file and extract it.

2. Run the following command to copy the script to `/usr/bin`:

`sudo cp ctools /usr/bin/ctools`

3. Make the script executable by running the following command:

`sudo chmod +x /usr/bin/cosmo-crypt-tools`

## Usage

After installation, you can run the script by typing `cosmo-crypt-tools` in the terminal and following the prompts.

`ctools [OPTION] [FILE]`

**Cosmo's Crypt Tools has the following options:**

*    -h, --help: Display the help message with all available options
*    -g, --generate: Generate a random 12-character password
*    -e, --encrypt [FILE]: Encrypt a file
*    -d, --decrypt [FILE]: Decrypt a file
*    -q, --quit: Quit the program

**Examples**

Generate a random password:

`ctools -g`

Encrypt a file:

`ctools -e [FILE]`

Decrypt a file:

`ctools -d [FILE]`

**Limitations**

*    Cosmo's Crypt Tools uses AES-256-CBC encryption, which is widely used but not considered to be the most secure encryption method available.
*    The password entered during encryption is used as the encryption key, so it's important to choose a strong password and keep it secure.You can use the included password generator to accomplish this.

**Contributing**

Contributions to Cosmo's Crypt Tools are welcome and encouraged. If you would like to contribute, please fork the repository, make your changes, and submit a pull request.

**License**

Cosmo's Crypt Tools is released under the [MIT LICENSE](https://opensource.org/licenses/MIT "MIT License")
