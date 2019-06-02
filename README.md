# Mini CTF tool

Mini CTF tool is a quick and easy tool to manage the challenges for a CTF in
a controlled, automated fashion.

It cleanly handles challenge creation and deployment scripts as well as
integrating with the [CTFd](https://github.com/CTFd/CTFd) platform as a
scoreboard.

## Installation

Simply copy the `ctftool` script into the root directory of your CTF
challenge directory.

To upgrade your existing installation (and overwrite the existing script):

	$ ./ctftool upgrade

## Usage

Create a challenge:

    $ ./ctftool create SampleName SampleCategory

List all challenges:

    $ ./ctftool list

Refresh and reformat all challenge configs:

    $ ./ctftool refresh

Deploy the challenges:

    $ ./ctftool start

Upload the challenges to CTFd with a session key:

    $ ./ctftool upload https://demo.ctf.io deadbeef-1337-1337-1337-deadbeef1337
