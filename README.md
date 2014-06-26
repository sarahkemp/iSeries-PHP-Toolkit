Introduction
----------------------------
Lets PHP access IBM i resources either on the same machine or over the network. 

The code hosted here is one part of two required to access programs and information on the iSeries. The second part is XMLSERVICE which must be installed on the iSeries you will be interfacing with.

More information available here: http://youngiprofessionals.com/wiki/XMLSERVICE

Dependencies
----------------------------
* XMLSERVICE library installed on IBM i machine.
* PHP

Versions
----------------------------
This repo contains the latest (as of June 2014) PHP Toolkit 1.5.0

**Branches**
* master: unedited Toolkit straight from YiPs site
* format: toolkit that has been autoformatted but otherwise unchanged
* validate: toolkit that has been autoformatted and had basic validation features added

Ideally all changes will fork from the format branch. New versions of the Toolkit will overlay the master branch, the format branch will be updated to reflect the new version (but formatted), and all changes will merge with the format branch to keep feature branches up to date.
