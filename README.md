# Scoop bucket

Add the bucket and install the Open Pact client with:

```powershell
scoop bucket add gaboe https://github.com/gaboe/scoop-bucket
scoop install gaboe/open-pact
```

The manifest downloads the Windows release binary and checks its SHA-256 hash. Update only when you run `scoop update`.

The open-pact release workflow writes the manifest from the signed release `SHA256SUMS` file.
