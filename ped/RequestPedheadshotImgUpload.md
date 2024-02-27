---
ns: PED
aliases: ["0xf0daef2f545bee25"]
---
## REQUEST_PEDHEADSHOT_IMG_UPLOAD

```c
// 0xF0DAEF2F545BEE25
bool REQUEST_PEDHEADSHOT_IMG_UPLOAD(int id);
```

Upload a headshot texture to the cloud. [`IS_PEDHEADSHOT_IMG_UPLOAD_AVAILABLE`](#_0xEBB376779A760AA8) should be called first to ensure the upload feature is not already in use, otherwise the request will fail. The user must ensure that the headshot remains active during the upload process. The upload is asynchronous so the user must query the status of the request to know whether it's failed or succeeded. The request must be explicitly released by the user by calling [`RELEASE_PEDHEADSHOT_IMG_UPLOAD`](#_0x5D517B27CF6ECD04), regardless of whether the request failed or succeeded; otherwise, no further requests will be processed.

