# scs.nba.fty.customer

Customer-facing ESPN credential helper.

`get_espn_credentials.py` reads the cookies already stored in the customer's
browser for `espn.com` and prints the `SWID` and `espn_s2` values needed to
connect an ESPN fantasy league. It does not send anything anywhere.

```bash
pip install browser-cookie3
python get_espn_credentials.py
```

`docs/index.html` is the hosted instructions page. Credentials are supplied by
the customer; never commit them to a repository or paste them into an issue.
