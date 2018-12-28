# Item Catalog Hosted on Amazon Lightsail Instance

## IP Address:
35.172.137.85

## SSH Port
2200

## URL
http://35.172.137.85.xip.io

## Configuration changes
  - Added user grader
  - Added user grader to the sudoers list
  - Removed non public key authentication
  - Removed root ssh authentication
  - Updated software package list with apt-get update
  - Upgraded software with apt-get upgrade
  - Activated the ubuntu firewall and configured it to only allow ports (80, 2200, and 123)
  - Installed and configured the item-catalog project
  - Modified the google_secrets.json file with the correct URL for this newly hosted web application to allow for OAuth login

## Additional software/resources
  - Used the [mod_wsgi package](https://pypi.org/project/mod_wsgi/) to build and install python3.7 compatible version of mod_wsgi for Apache.
