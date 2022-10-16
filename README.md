# Ventoy

<https://www.ventoy.net>

## Secure boot

With secure boot enabled in the BIOS, a key is required for Ventoy to boot: <https://www.ventoy.net/en/doc_secure.html>.

The following blue screen error will be displayed:

```text
Verification failed: (0x1A) Security Violation
```

Perform the following steps:

1. Press any key to perform MOK management.

1. Enroll key from disk.

1. VTOYEFI.

1. `ENROLL_THIS_KEY_IN_MOKMANAGER.cer`.

1. Continue.

1. Yes.

1. Reboot.
