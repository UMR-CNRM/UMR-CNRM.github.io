UMR-CNRM Forge documentation
============================

For newcomers:
--------------

1. set a github.com personal account (e.g. "PrenomNomMF") with your MF e-mail address
2. send an e-mail to ???? asking to become a member of the organization, providing your github.com account user id.
3. you will receive an invitation to join the organization, that you will have to accept.

Connectivity:
-------------

To set your connectivity with your local repository clones (i.e. git commands such as `clone, fetch, pull, push`), two
connection protocols are available: SSH and HTTPS. From MF HPC, only HTTPS is allowed for now.

### SSH

* go to your account *Settings* > *SSH and GPG keys*
* set the public SSH key from the host you want to connect from
* (repeat for as many hosts)

### HTTPS
* go to your account *Settings* > *Developer settings* > *Personal access tokens*
* *Generate new token*
* set this token in any host `.netrc` file:
  `machine github.com login <your github userid> password <the generated token>`

To set a new repository on the UMR-CNRM forge:
----------------------------------------------

Contact the admins of the forge (????) with the precise name of the repository (case sensitive).
Once created, the admins will give you admin rights on the repository.

