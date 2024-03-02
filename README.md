# https://blobby-boi.github.io/Blobwifi/
## Blobwifi
Blobwifi is an exploit that allows Chromebook users to bypass Wi-Fi restrictions.

### How does it work?
Managed networks connect you to a specific DNS server that contains restrictions in it. So can't you just change that DNS server to one without those restrictions? The answer is no. Networks that are pre-installed don't let you change the DNS servers. So what is the solution to this problem? When you download a network using a .onc file that has the same GUID that a managed network has, the Chromebook replaces the original network with the new network. It will only do this if it's not the exact same as the original network with that name, though. Since the new Wi-Fi was added by you, it does not force you to use the DNS server with all of those restrictions in it. This means that if import a .onc file that contains a slightly modified version of a managed network, it will completely remove all of those restrictions. Thus allowing you to change those DNS servers. Chrome happens to have a very convenient way to get all of the network data that you need in order to create that .onc file. What Blobwifi does is automatically creates the .onc file with the unrestricted DNS servers.

##### I am NOT responsible for any trouble that this might get you into.
