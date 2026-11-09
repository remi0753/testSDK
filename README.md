# testSDK

A source SDK for Rinzu 0.5. It exports `add(left: Int, right: Int) -> Int`.

Download [testSDK-1.0.0.tar.gz](https://github.com/remi0753/testSDK/releases/download/v1.0.0/testSDK-1.0.0.tar.gz)
from GitHub Releases and extract it under your application's `vendor/` directory.
Add the extracted package to the application's `rinzu.toml`.

```toml
[dependencies]
"remi0753.test_sdk" = { path = "vendor/testSDK-1.0.0" }
```

Import the package with `import remi0753.test_sdk as test_sdk;` and call
`test_sdk.add(20, 22)`. Build from the application directory with `rinzu build .`.
