# awesome-yubikey [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> awesome Yubikey resources, open source projects, tools and tutorials

## Contents

- [Configuration Guides](#configuration-guides)
- [Tools](#tools)
- [Standards / Protocols](#standards--protocols)
- [Libraries / Clients](#libraries--clients)

## Configuration Guides

List of guides / documents help setting up Yubikey.

- [YubiKey-Guide](https://github.com/drduh/YubiKey-Guide) - Guide to using YubiKey for GPG and SSH
- [YubiKey - ArchWiki](https://wiki.archlinux.org/index.php/Yubikey)
- [YubiKey at Datadog](https://github.com/DataDog/yubikey)
- [secure-mac-guide](https://github.com/pasientskyhosting/secure-mac-guide) - How to secure your Macbook with Yubikey and use it for SSH auth.
- [ubuntu-yubikey-setup](https://github.com/carniz/ubuntu-yubikey-setup) - A guide for setting up Yubikey support on an Ubuntu 18.04-based distribution (such as elementaryOS 5.0 "Juno")

## Tools

List of tools to use with Yubikey.

- [awsu](https://github.com/kreuzwerker/awsu) - Enhanced account switching for AWS, supports Yubikey as MFA source.
- [Purse](https://github.com/drduh/Purse) - GPG asymmetric (YubiKey) password manager
- [rage](https://github.com/str4d/rage) - A simple, secure and modern encryption tool with small explicit keys, no config options, and UNIX-style composability.
- [Yubico Authenticator](https://developers.yubico.com/yubioath-desktop/) - Cross-platform application for generating Open Authentication (OATH) time-based TOTP and event-based HOTP one-time password codes, with the help of a YubiKey that protects the shared secrets.
- [YubiKey Manager CLI](https://developers.yubico.com/yubikey-manager/) - Python library and command line tool for configuring a YubiKey.
- [yubikey-agent](https://github.com/FiloSottile/yubikey-agent) - yubikey-agent is a seamless ssh-agent for YubiKeys.
- [yubikey-luks](https://github.com/cornelinux/yubikey-luks) - Two factor authentication for harddisk encryption.
- [yubikey-touch-detector](https://github.com/maximbaz/yubikey-touch-detector) - A tool to detect when your YubiKey is waiting for a touch (to send notification or display a visual indicator on the screen).
- [yubico-pam](https://github.com/Yubico/yubico-pam) - The Yubico PAM module provides an easy way to integrate the YubiKey into your existing user authentication infrastructure. PAM is used by GNU/Linux, Solaris and Mac OS X for user authentication, and by other specialized applications such as NCSA MyProxy.
- [yubikeylockd](https://github.com/shtirlic/yubikeylockd) - Simple daemon for locking and unlocking macOS with Yubikey

## Standards / Protocols

List of standards / protocols Yubikey implements.

- [CCID: Chip Card Interface Device](<https://en.wikipedia.org/wiki/CCID_(protocol)>)
- [FIDO2 / FIDO UAF / FIDO U2F](https://fidoalliance.org/specifications/)
- [HOTP: HMAC-Based One-Time Password Algorithm](https://tools.ietf.org/html/rfc4226)
- [OATH](https://openauthentication.org/specifications-technical-resources/)
- [OpenPGP](https://www.openpgp.org/)
- [PIV: Personal Identity Verification](https://en.wikipedia.org/wiki/FIPS_201)
- [TOTP: Time-Based One-Time Password Algorithm](https://tools.ietf.org/html/rfc6238)
- [WebAuthn](https://webauthn.io/)

## Libraries / Clients

- [python-yubico-client](https://github.com/Kami/python-yubico-client) - Python library for validating Yubico Yubikey One Time Passwords (OTPs) based on the validation protocol version 2.0.
- [yubikey.rs](https://github.com/iqlusioninc/yubikey.rs) - Pure Rust YubiKey host-side driver for PIV-based RSA/ECC key storage + signing/encryption support.
- [yubico-rs](https://github.com/wisespace-io/yubico-rs) - Yubikey client API library, Challenge-Response & Configuration
- [yubigo](https://github.com/GeertJohan/yubigo) - Yubigo is a Yubikey client API library that provides an easy way to integrate the Yubico Yubikey into your existing Go-based user authentication infrastructure.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, nozaq has waived all copyright and
related or neighboring rights to this work.
