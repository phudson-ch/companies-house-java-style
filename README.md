# Companies House Java Style for IntelliJ

To use the Companies House Java code style settings:

1) Configure your own personal GitHub settings repository; see [IntelliJ: How to configure a settings repository](https://www.jetbrains.com/help/idea/sharing-your-ide-settings.html#settings-repository)
2) Add this repository as a read-only source in Preferences → Tools → Settings Repository.
3) Check that the CompaniesHouseStyle scheme is selected in Preferences -> Editor -> Code Style -> Java.

BTW: if you have an SSH error [known bug] synchonizing to your personal GitHub settings repository, you may need to convert [take a backup first] your 
ed25519 SSH private key to PEM [old] format using:

`ssh-keygen -p -f <ed25519-file> -m pem -P passphrase -N passphrase`
