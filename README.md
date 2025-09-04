# IDnow iOS SDKs

This repository hosts all iOS SDKs developed and maintained by IDnow under a single umbrella.

Each SDK is provided as a Git submodule to allow flexible integration into your iOS projects via Swift Package Manager or direct source checkout. The umbrella repository lets you pin and update SDK versions centrally across projects.

**Available SDKs in this repository**

- sunflower-sdk → Design System SDK (submodule: sunflower-sdk-ios)
- eid-sdk → eID product SDK (submodule: eid-sdk-ios)
- docidv-sdk → DocIDV product SDK (submodule: docidv-sdk-ios)

**Repository structure**

idnow-ios-sdk/

- .gitmodules
- sunflower-sdk/        (submodule)
- eid-sdk/              (submodule)
- docidv-sdk/           (submodule)
- README.md

**Cloning with submodules**

Recommended:

`git clone --recurse-submodules git@github.com
:idnow/idnow-ios-sdk.git`

If already cloned:

`git submodule update --init --recursive`

**Integration options**

Choose the method that fits your project setup and dependency policy. For exact steps and version-specific notes, see each SDK’s README inside its folder.