# nobluecheckfor.me

A cypherpunk advocacy site against paid verification with NIP-05 Nostr identity verification.

## What's Inside

- **index.html** — Main website (black/white/green cypherpunk aesthetic)
- **.well-known/nostr.json** — NIP-05 identity verification endpoint
- **vercel.json** — Vercel configuration for static site deployment

## Your Nostr Identity

```
Handle:      tonysly@nobluecheckfor.me
Public Key:  npub146j2myq28t6nw87e0v89q0tq47wcmsvkpdxszc5wkyqtgfsvuh7q8k2jsd
```

## Features

- Fully responsive design
- 15 Nostr clients (Web, iOS, Android) with direct links
- NIP-05 verification support
- No fabricated statistics
- Cypherpunk aesthetic (monospace, black/white/green)

## Deployment

This site is deployed to Vercel. DNS points to Vercel via Namecheap.

### Local Testing

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
# Check http://localhost:8000/.well-known/nostr.json
```

## NIP-05 Verification

Once deployed, add `tonysly@nobluecheckfor.me` to your Nostr client profile to verify your identity.

---

Built with no corporate approval. Just cryptography. ✓
