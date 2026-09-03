# ChainShield Git LFS E2E fixtures

This repository contains non-sensitive, deterministic fixtures for ChainShield
issue 1471. Both `*.bin` files are tracked by Git LFS.

- `proxy-upstream.bin`: GitHub LFS upstream object for Proxy cold/warm checks.
- `hosted-source.bin`: source bytes to upload to ChainShield Hosted and consume
  through Group after OSV synchronization is stable.

The repository stores only fixtures and Git LFS pointers. ChainShield endpoint
URLs and credentials must be configured locally and must never be committed.


