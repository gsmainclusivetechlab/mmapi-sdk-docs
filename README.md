# Documentation

Documentation for the SDK Productisation Project

## Introduction

### What is Mobile Money API?

The Mobile Money API is an initiative developed through collaboration between the mobile money industry and the GSMA, which provides a harmonized API Specification for all the common mobile money use cases which is both easy to use and secure.

<a href="https://developer.mobilemoneyapi.io/">Learn more »</a>

### What is the MMAPI SDK?

The GSMA MMAPI SDKs provides separate use cases to handle necessary MMAPI functionality including Merchant Payments, Disbursements, International Transfers, P2P Transfers, Recurring Payments, Account Linking, Bill Payments and Agent Services (including Cash-In and Cash-Out). Each use case exposes use case scenarios to customize your application integrations as needed. The SDK also includes samples, so you can test interactions before integration, which defines use cases to communicate with the Mobile Money providers. 

### Supporting Platforms

- PHP - PHP 5.4+ , cURL PHP Extension, JSON PHP Extension
- Node.JS - Version v16.13.0 or higher
- Java - Java JDK Version 8 or higher, No platform dependency, Apache Maven 3 or higher
- Javascript - Versions and supported platforms
- Android - Android Studio 4.0 or newer, Android Platform Version: API 31, Build gradle:4.2.1 minSdkVersion:16, targetSdkVersion:31 and  java version:1.8

### Security

SDK provides 3 levels of security

- <b>No Authentication</b> - Available only for Sandbox account. No access keys required for communiction. Developer can access functions that doesn't require authentication from window.gsma.noAuth
- <b>Basic Authentication</b> - Basic level of authentication. Requires Consumer key and Consumer secret key.
- <b>OAuth2 based Authentication</b> - Standard level of authentication Requires encryption of username, pass, apiKey

## SDKs are available in the following Languages

- <a href='https://github.com/gsmainclusivetechlab/mmapi-php-sdk/blob/develop/README.md'>PHP</a>
- <a href='https://github.com/gsmainclusivetechlab/mmapi-java-sdk/blob/develop/README.md'>Java</a>
- <a href='https://github.com/gsmainclusivetechlab/mmapi-nodejs-sdk/blob/develop/README.md'>NodeJS</a>
- <a href='https://github.com/gsmainclusivetechlab/mmapi-javascript-sdk/blob/development/README.MD'>JavaScript</a>
- <a href='https://github.com/gsmainclusivetechlab/mmapi-android-sdk/blob/develop/README.md'>Android</a>
