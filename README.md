# Bitcoin Dead Man's Switch

A “dead man’s switch” for self-custody inheritance. A Rust service that holds encrypted PSBT or seed shards, pings you periodically over Nostr/email/Signal, and if you don’t respond within a configurable window, releases instructions or shards to pre-designated recipients. Timelock + Shamir + Nostr.
