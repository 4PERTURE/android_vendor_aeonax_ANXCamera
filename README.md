# ANXCamera
## Getting Started :
### Cloning :
- Clone this repo in vendor/aeonax/ANXCamera in your working directory by :
```
git clone https://github.com/4PERTURE/android_vendor_aeonax_ANXCamera vendor/aeonax/ANXCamera
```
### Changes Required :
- You will need [this change in your device tree.](https://github.com/sarveshrulz/android_device_xiaomi_phoenix/commit/4f8e58a644de2593847c662add77d282b2f998f8)
- You will also [this change](https://github.com/4PERTURE/device_xiaomi_sm6250-common/commit/69b1f3d36e681a75d8743ddb9ed7017881b64820) in case your phone has aux cameras (more than one camera).
- Done, continue building your ROM as you do normally.

### Fork changes :
- Add Camera service blobs to fix portrait on OSS vendors.
- Integrate libcameraservice for 48mp fix.

### Notes :
- This fork has extra proprietary libraries meant for the Redmi Note 9s (curtana), compatibility with other devices is not guaranteed.
