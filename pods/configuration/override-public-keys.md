# Override public key

We attempt to inject the public key that you configure in your account's settings page for authentication using basic terminal.
If you want to override this at a pod level, you can manually supply a public key as the `SUBMODEL_SSH_PUBLIC_KEY` environment variable.