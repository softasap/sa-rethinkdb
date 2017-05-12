# sa-rethinkdb


[![Build Status](https://travis-ci.org/softasap/sa-rethinkdb.svg?branch=master)](https://travis-ci.org/softasap/sa-rethinkdb)


#Usage:

Simple:

```

- {
    role: "sa-rethinkdb"
  }


```

Advanced:

```


roles:
  - {
      role: "sa-rethinkdb"
    }


```


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-rethinkdb role using the command

`
   ansible-galaxy install softasap.sa-rethinkdb
`

the role will be available in the folder library/softasap.sa-mailhog
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-rethinkdb"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

