# rp2040-space-truck

An RP2040 embassy test firmware for any puspose.

So, flashing & debugging via `probe-rs` works. The issue was [this](https://github.com/probe-rs/probe-rs/pull/3137). The fix is this:

```cargo install probe-rs-tools --git https://github.com/probe-rs/probe-rs --locked```

add a `--forced` argument if this causes issues with overwriting and permissions.
