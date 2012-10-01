# puppet-httpfile

Usage:

```puppet
httpfile { '/tmp/myfile.deb':
  ensure => present,
  source => 'https://cloud.github.com/whatever.deb',
  hash   => 'hex form SHA2 hash OR an URL to the .sha file with that hash'
}
```


