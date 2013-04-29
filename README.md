# Orno\Db [In Development]

[![Build Status](https://travis-ci.org/orno/db.png?branch=master)](https://travis-ci.org/orno/db)

A simple database abstraction layer.

### Support

- Oracle OCI8
- PDO

## Testing

### Oracle

Testing for oracle integration requires the `OCI8` extension to be loaded and for you to provide your connection details in the `phpunit.xml.dist`.

Add the following to the `phpunit.xml.dist` configuration file to be able to connect for testing Oracle integration.

    <php>
        <var name="OCI8_DATABASE" value="CONNECTION_STRING" />
        <var name="OCI8_USERNAME" value="username" />
        <var name="OCI8_PASSWORD" value="password" />
    </php>
