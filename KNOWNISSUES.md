# Known Issues

## v1.0 (November 10, 2015)

The following is a list of the known issues in the November 10, 2015 release of the self-certification tools:

1. The test suite requires support for the document-number member attribute (only needed for multiple document jobs).

2. The test suite requires that printers follow the best practice of using "/ipp/print" in the printer URI(s) (not required by IPP Everywhere).

3. The test suite matches any substring of the service instance name.

4. The test suite does not handle service instance names starting with an underscore.
