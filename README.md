# Docker Perl Critic

## What it does

Runs Perl::Critic using Docker and outputs a HTML report.

## Pre-requisites

- Docker

## Usage instructions

1. Navigate to the directory containing the code you want to run perlcritic against.
1. Next, run the following command in your terminal and perlcritic will be run against your code.
	```
	docker run -v $PWD:/tmp/workspace avastsoftware/perl_critic
	```
1. The resulting html report(s) are now accessible in `./critic_html`.

## Acknowledgements

perl_critic is based on
http://blogs.lessthandot.com/index.php/webdev/perl/create-html-from-output-of/
