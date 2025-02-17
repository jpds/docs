Eucalyptus Walrus
====

> [Eucalyptus Walrus](http://open.eucalyptus.com/) is an open source implementation of S3. 

## Connecting 

- {download}`Download<http://profiles.cyberduck.io.s3.amazonaws.com/Eucalyptus%20Walrus%20S3.cyberduckprofile>` the *Eucalyptus Walrus S3 Connection Profile* for preconfigured settings.

Choose *Eucalyptus Walrus S3* from the protocol dropdown menu in the [Open Connection](../../cyberduck/connection.md) or [Bookmark](../../cyberduck/bookmarks.md) settings and enter the hostname of your installation. Refer to [S3](index.md) in general.

The only difference to regular S3 is that the storage path (endpoint) is assumed to be `/services/Walrus` instead of `/`.

### Login Credentials

Download your credentials ZIP from `ecc.eucalyptus.com`. You can find the access key and secret in the file *eucarc*.

## Distribution

You can enable [Amazon CloudFront (Content Delivery Network) distribution](../../protocols/cdn/cloudfront.md) using *File → Info → Distribution (CDN)*.

## Limitations

- No content distribution ([CDN](../../protocols/cdn/index.md)) configuration.
- No bucket logging configuration.
- No bucket location support.
- Storage class options are not available.