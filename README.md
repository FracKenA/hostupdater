# hostupdater
Updates objects in OP5 Monitor

## Usage

hostupdater.py <https://server.domain.tld> <account> <password> <jsontemplate> <hostsfilename>

### Options

* --nossl
    * Disables SSL checking.
* --lower
    * Sets hostname to lowercase.
* --upper
    * Sets hostname to uppercase.
* -h,--help
    * Displays help message.

## JSON Template

Needs to be valid JSON with all the changes which need to be made.

