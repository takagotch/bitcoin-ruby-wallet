### bitcoin-ruby-wallet
---
https://github.com/mhanne/bitcoin-ruby-wallet

```rb

name_update d/foo '{"foo":"baz"}'
```

```sh
git clone https://github.com/mhanne/bitcoin-ruby-wallet.git; cd bitcoin-ruby-wallet
ruby bin/bitcoin_wallet
balance xxx
list xxx
send xxx
send op_return:deadbeef:0
new
import xxx
export xxx
name_list
name_show d/foo
name_history d/foo
neme_new d/foo
name_firstupdate d/foo xxx '{"foo":"bar"}'
name_update d/foo '{"foo":"baz"}'


rake doc
rake
rspec spec/wallet/wallet_spec.rb
```

```
```


