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
- [YubiKey - ArchWiki](https://wiki.archlinux.org/title/YubiKey)
- [ubuntu-yubikey-setup](https://github.com/carniz/ubuntu-yubikey-setup) - A guide for setting up Yubikey support on an Ubuntu 18.04-based distribution (such as elementaryOS 5.0 "Juno")

## Tools

List of tools to use with Yubikey.

### Official Tools

- [libfido2](https://github.com/Yubico/libfido2) - Library for communicating with a FIDO2 device over USB or NFC, shipping the fido2-token and fido2-cred command line tools.
- [pam-u2f](https://github.com/Yubico/pam-u2f) - Pluggable Authentication Module (PAM) for U2F and FIDO2.
- [Yubico Authenticator](https://www.yubico.com/products/yubico-authenticator/)([GitHub Repo](https://github.com/Yubico/yubioath-flutter)) - Cross-platform application for generating Open Authentication (OATH) time-based TOTP and event-based HOTP one-time password codes, with the help of a YubiKey that protects the shared secrets.
- [yubico-piv-tool](https://github.com/Yubico/yubico-piv-tool) - Command line tool and shared library for the YubiKey PIV application.
- [YubiKey Manager](https://developers.yubico.com/yubikey-manager/)([GitHub Repo](https://github.com/Yubico/yubikey-manager)) - Python library and command line tool for configuring a YubiKey.

### Third-party Tools

- [age-plugin-yubikey](https://github.com/str4d/age-plugin-yubikey) - YubiKey plugin for age, allowing files to be encrypted to age identities stored on a YubiKey.
- [awsu](https://github.com/kreuzwerker/awsu) - Enhanced account switching for AWS, supports Yubikey as MFA source.
- [piv-agent](https://github.com/smlx/piv-agent) - An SSH and age agent backed by PIV hardware tokens such as the YubiKey.
- [Purse](https://github.com/drduh/Purse) - GPG asymmetric (YubiKey) password manager
- [putty-cac](https://github.com/NoMoreFood/putty-cac) - Windows SSH client based on PuTTY with support for smart cards, certificates and FIDO keys.
- [rage](https://github.com/str4d/rage) - A simple, secure and modern encryption tool with small explicit keys, no config options, and UNIX-style composability.
- [WinCryptSSHAgent](https://github.com/buptczq/WinCryptSSHAgent) - SSH agent for Windows that authenticates with a YubiKey via CryptoAPI, no extra smart card driver required.
- [yubikey-agent](https://github.com/FiloSottile/yubikey-agent) - yubikey-agent is a seamless ssh-agent for YubiKeys.
- [yubikey-full-disk-encryption](https://github.com/agherzan/yubikey-full-disk-encryption) - Use the YubiKey HMAC-SHA1 Challenge-Response mode to unlock a LUKS partition.
- [yubikey-luks](https://github.com/cornelinux/yubikey-luks) - Two factor authentication for harddisk encryption.
- [yubikey-provisioning-scripts](https://github.com/santiago-mooser/yubikey-provisioning-scripts) - A set of scripts to automatically set up your yubikey's OpenPGP applet. Supports Linux and MacOS.
- [yubikey-touch-detector](https://github.com/maximbaz/yubikey-touch-detector) - A tool to detect when your YubiKey is waiting for a touch (to send notification or display a visual indicator on the screen).
- [yubikeylockd](https://github.com/shtirlic/yubikeylockd) - Simple daemon for locking and unlocking macOS with Yubikey
- [yubiswitch](https://github.com/pallotron/yubiswitch) - macOS status bar application to enable/disable a YubiKey, preventing accidental OTP output on touch.

## Standards / Protocols

List of standards / protocols Yubikey implements.

- [CCID: Chip Card Interface Device](<https://en.wikipedia.org/wiki/CCID_(protocol)>)
- [FIDO2 / FIDO UAF / FIDO U2F](https://fidoalliance.org/specifications/)
- [HOTP: HMAC-Based One-Time Password Algorithm](https://www.rfc-editor.org/rfc/rfc4226)
- [OATH](https://openauthentication.org/specifications-technical-resources/)
- [OpenPGP](https://www.openpgp.org/)
- [PIV: Personal Identity Verification](https://en.wikipedia.org/wiki/FIPS_201)
- [TOTP: Time-Based One-Time Password Algorithm](https://www.rfc-editor.org/rfc/rfc6238)
- [WebAuthn](https://webauthn.io/)

## Libraries / Clients

List of libraries / clients to integrate Yubikey into your application.

- [piv-go](https://github.com/go-piv/piv-go) - Go library for managing keys and certificates on the YubiKey PIV application.
- [python-fido2](https://github.com/Yubico/python-fido2) - Official Python library for communicating with a FIDO device over USB and for verifying attestation and assertion signatures.
- [python-yubico-client](https://github.com/Kami/python-yubico-client) - Python library for validating Yubico Yubikey One Time Passwords (OTPs) based on the validation protocol version 2.0.
- [yubico-rs](https://github.com/wisespace-io/yubico-rs) - Yubikey client API library, Challenge-Response & Configuration
- [Yubico.NET.SDK](https://github.com/Yubico/Yubico.NET.SDK) - Official cross-platform YubiKey SDK for .NET developers, covering PIV, FIDO2, OATH, OpenPGP and YubiOTP.
- [yubigo](https://github.com/GeertJohan/yubigo) - Yubigo is a Yubikey client API library that provides an easy way to integrate the Yubico Yubikey into your existing Go-based user authentication infrastructure.
- [yubikey.rs](https://github.com/iqlusioninc/yubikey.rs) - Pure Rust YubiKey host-side driver for PIV-based RSA/ECC key storage + signing/encryption support.
- [yubikit-android](https://github.com/Yubico/yubikit-android) - Official Android SDK for adding YubiKey support over USB and NFC to your app.
- [yubikit-ios](https://github.com/Yubico/yubikit-ios) - Official iOS SDK for adding YubiKey support over Lightning and NFC to your app.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, nozaq has waived all copyright and
related or neighboring rights to this work.
