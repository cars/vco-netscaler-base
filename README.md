vco-netscaler-base
==================
Basic vCenter Orchestrator Rest Operations setup

This project uses vFLOWer (https://github.com/ByteLife/vFLOWer) toolkit for package generating.

Build requirements:
- Git for Windows: https://msysgit.github.io
- Apache Ant for Windows: http://ant.apache.org
- OpenSSL for Windows: http://gnuwin32.sourceforge.net

Include Ant and OpenSSL binary paths to Windows PATH environment variable
and openssl.cnf -file path to OPENSSL_CONF environment variable.

Build:
git clone https://github.com/cars/vco-netscaler-base.git
ant build

Install:
Install using vCO client from inout folder

Exporting package back to sources:
Export package using vCO client to inout folder
Update sources using command:
ant precommit