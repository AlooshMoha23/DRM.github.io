# Mini OTT Platform using Encrypted Media Extensions (EME)

This project explores and implements a mini Over-The-Top (OTT) platform utilizing Encrypted Media Extensions (EME) for secure video content delivery. The platform utilizes the MediaSource API and EME API to handle media streams and DRM-protected content directly within the browser.

Key features:

1. Encryption: We used Shaka Packager to encrypt video content using Widevine DRM, ensuring secure distribution and protection of intellectual property.
2. Decryption: The platform employs the EME API to decrypt encrypted video content using two methods:
Method 1: Providing the MPD URL and utilizing Shaka Player for decryption.
Method 2: Providing the encrypted file (using Widevine) and utilizing our own implementation of Widevine DRM for decryption.

Conclusion

This OTT platform project significantly enhances content security by implementing Widevine DRM, a robust digital rights management system. Widevine DRM protects copyrighted video content from unauthorized access, distribution, and modification, ensuring content integrity and access control.
