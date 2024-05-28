# iCure

### About iCure
iCure is a secured and distributed healthcare platform that helps you create apps and share data with the healthcare community.

To make it possible, the iCure Data Model focus on the integrity, the anonymization
and the encryption of your data, without forgetting to make it compatible with higher level Medical Data conceptual
Data Models (such as FHIR, Open EHR, ...).

Thanks to this high-level model, iCure will then let you easily manage all your data in a protected way, through a series of APIs.

Following your needs, iCure can either be used in the Cloud or installed locally in a bare metal server or in a personal computer.

iCure is:&#x20;

* Easy to use for web and app developers.
* Secured by an End-to-End encryption.
* Fault-tolerant and highly scalable.
* Compatible with the FHIR.
* Available as an XDS registry/repository.

### iCure Open Source projects

Most of the iCure projects are open source and available here.

iCure is constituted mainly of three parts:

1. The iCure Data Stack, which is the core of the platform. It is called the Kraken (Kotlin Reactive Backend) and is composed of several modules:
   * The [Kraken Lite](https://github.com/icure/kraken-lite/) is the Open Source version of the Kraken.
   * [Kraken common](https://github.com/icure/kraken-common/) is the foundation layer of Kraken Lite and of the closed source Kraken Cloud.
   * The [Kraken Kmehr module](https://github.com/icure/kmehr-module/) is a module that allows to import and export of Kmehr formats for the Belgian market as well as the SAM medication database.

2. The iCure SDKs:
   * [iCure Typescript SDKs](https://github.com/icure/icure-typescript-sdks/): the high level SDKs for web, react-native and node developers
   * [iCure Typescript SDK](https://github.com/icure/icure-typescript-sdk/): the low level SDK for Typescript developers. It is used by the above.

3. The iCure supporting projects:
   * [async-jackson-http-client](https://github.com/icure/async-jackson-http-client/): a simple and efficient reactive HTTP client in Kotlin that uses Jackson in a reactive way for low memory usage JSON de-serialization.
   * [Kryptom](https://github.com/icure/kryptom/): a simple and efficient multiplatform encryption library written in pure Kotlin
   * [Krouch](https://github.com/icure/krouch/): an efficient reactive CouchDB client in Kotlin
   * [Kmap](https://github.com/icure/kmap/): a KSP processor that generates Kotlin Mappers (à la MapStruct)

