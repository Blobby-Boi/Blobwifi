# https://blobby-boi.github.io/Blobwifi/
## Blobwifi
Blobwifi is an exploit that allows Chromebook users to bypass Wi-Fi restrictions.

### How does it work?
Managed networks connect you to a specific DNS server that contains restrictions in it. So can't you just change that DNS server to one without those restrictions? The answer is no. Networks that are pre-installed don't let you change the DNS servers. So what is the solution to this problem? When you download a network using a .onc file that has the same GUID that a managed network has, the Chromebook replaces the original network with the new network. Since the new Wi-Fi was added by you, it does not force you to use the DNS server with all of those restrictions in it. This means that if you import a .onc file that contains a modified version of a managed network, it will completely remove those restrictions allowing you to set the DNS servers. Chrome happens to have a very convenient way to get all of the network data that you need in order to create that .onc file with the modified DNS servers. Blobwifi automatically creates a .onc file with the unrestricted DNS servers.</p>

##### I am NOT responsible for any trouble that this might get you into.
