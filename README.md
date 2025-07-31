# Action to install EMQX fork of Erlang/OTP on macOS

## Usage

```yaml
    - uses: emqx/macos-erlang@f744c98139c0db83a10619587d4bae4fc49765a8 # v1.0.0
      with:
        otp-version: "27.3.4.2-1"
        install-elixir: true
        elixir-version: "1.18.3"
        rebar3-version: "3.25.0"
```
