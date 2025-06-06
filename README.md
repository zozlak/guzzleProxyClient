# guzzleProxyClient

A tiny wrapper for the Guzzle Client applying proxy settings from the `http_proxy`, `https_proxy` and `no_proxy` environment variables.

## Installation

```bash
composer require zozlak/guzzle-proxy-client
```

## Usage

```php
// without Guzzle Client options
$guzzleClient = \zozlak\ProxyClient::factory();
// with some Guzzle Client options
$guzzleClient = \zozlak\ProxyClient::factory(['auth' => ['foo', 'bar']]);
```
