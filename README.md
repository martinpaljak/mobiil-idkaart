# Mobile-ID as EstEID over NFC

> Use your **phone** with a [Mobile-ID SIM card](http://mobiil.id.ee/) just **like a regular ID-card** on a PC with [zee Baastarkvara](https://github.com/martinpaljak/idkaart_public#github-mirror-of-zee-baastarkvara)<sup>*</sup> and a decent contactless reader, thanks to the [Host Card Emulation](http://developer.android.com/guide/topics/connectivity/nfc/hce.html) in the latest Android release. This is like [FakeEstEID](https://github.com/martinpaljak/AppletPlayground/wiki/FakeEstEID) but with real and valid certificates!

**UPDATE 06.03.2014**: Due to missing features in the current [DigiDocService](https://www.sk.ee/en/services/validity-confirmation-services/digidoc-service/), this project is put on hold until an update is available that allows to directly control the input to authentication/sign operations. A minimalistic software-only implementation running the [FakeEstEID applet](https://github.com/martinpaljak/AppletPlayground/wiki/FakeEstEID) in Android-hosted [Virtual Java Card Runtime Environment](https://github.com/martinpaljak/vJCRE#import-projavacardvre) might still be released before that time. 


#### Jump to ...
 * [Download](#get-it-now)
 * [Contact](#contact)

## How does it work?

![Like this](http://martinpaljak.net/kitkat_with_vjcre.png)

You can choose between a 100% faked card (FakeEstEID through [JavaCard VRE](https://github.com/martinpaljak/vJCRE)) or one backed by Mobile-ID during application startup.

## How does it look like?

![Like this](http://martinpaljak.net/mobiil-idkaart-in-action.jpg)

# Get it now!
Application will be released ~~to Google Play and Github early March 2014~~ when DigiDocService supports necessary features.

# Contact
* martin@martinpaljak.net

----
All about the [EstEID](http://esteid.org)
