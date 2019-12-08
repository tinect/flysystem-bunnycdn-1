<img src="https://dka575ofm4ao0.cloudfront.net/pages-transactional_logos/retina/20630/bunnycdn-logo-dark.png" width="300"/>

# Flysystem Adapter for BunnyCDN.

[![Build Status](https://travis-ci.com/PlatformCommunity/flysystem-bunnycdn.svg?branch=master)](https://travis-ci.com/PlatformCommunity/flysystem-bunnycdn)

## Installation

```bash
composer require platformcommunity/flysystem-bunnycdn
```

## Usage

```php
use BunnyCDN\Storage\BunnyCDNStorage;
use League\Flysystem\Filesystem;
use PlatformCommunity\Flysystem\BunnyCDN\BunnyCDNAdapter;

$client = new BunnyCDNAdapter(new BunnyCDNStorage('storage-zone', 'api-key'));
$filesystem = new Filesystem($client);
```

## Contributing

Pull requests welcome. Please feel free to lodge any issues as discussion points.
 
## Licence

The Flysystem adapter for BunnyCDN is licensed under MIT. 
