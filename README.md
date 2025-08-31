# Nimbus

Nimbus is a **personal cloud platform** that is used to organize your own private cloud without depending on big cloud providers

## Platform architecture

Nimbus is a platform that is based on principles of **modularity and flexibility**. You only use what you need for yourself. But it does not meen it does not care about performance. **Good performance and reliability** are also critical parts of the platform. That is why **rust** is chosen as language for this platform.

## Modules
### Clients
- [**Web**](https://github.com/stkorkuts/nimbus-web) - Web client for the Nimbus platform;
- [**Desktop**](https://github.com/stkorkuts/nimbus-desktop) - Crossplatform desktop client for the Nimbus platform;
- [**Mobile**](https://github.com/stkorkuts/nimbus-mobile) - Crossplatform mobile client for the Nimbus platform.
### Services
- [**Authentication**](https://github.com/stkorkuts/nimbus-auth) - Nimbus module to provide authentication for other nimbus services;
- [**Vault**](https://github.com/stkorkuts/nimbus-vault) - Nimbus module to store objects like files, passwords and so on and track history of their changes.
