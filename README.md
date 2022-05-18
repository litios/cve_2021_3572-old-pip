# CVE-2021-3572 POC for older pip

## Instructions

Run:

`pip3 install git+https://github.com/litios/cve_2021_3572-old-pip.git@good`

When listing the installed modules with `pip3 list`, the output should be:

`cve-2021-3572 (1.2)`

if the package is affected, otherwise, you should get:

`cve-2021-3572 (1.0)`
