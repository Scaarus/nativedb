---
ns: NETWORK
aliases: ["0x16160da74a8e74a2"]
---
## TEXTURE_DOWNLOAD_REQUEST

```c
// 0x16160DA74A8E74A2
int TEXTURE_DOWNLOAD_REQUEST(string cloudPath, string textureName, bool useCacheWithoutCloudChecks);
```

Requests to download a texture from member space. The texture will not be immediately available; the user needs to query its state by calling TEXTURE_DOWNLOAD_HAS_FAILED, TEXTURE_DOWNLOAD_GET_NAME or GET_STATUS_OF_TEXTURE_DOWNLOAD


## Parameters
* **cloudPath**: relative path to the file in the cloud, including the file name and extension
* **textureName**: the name the user wants to give to the texture once it's downloaded; the texture dictionary containing this texture will have the same name
* **useCacheWithoutCloudChecks**: sets whether the request should avoid checking with the server if a locally cached version of the texture (if it exists) is up-to-date. This flag should always be set to TRUE if the user knows there's no need to hit the server.
