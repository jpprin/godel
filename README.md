# godel

An open source fixed income portfolio management and OMS application.

I made this because all of the commercial systems I have seen and used
are either overcomplicated, including every possible type of asset
class - and all of their associated features - or straightforward but
extremely expensive.

This tool is intended for users managing a portfolio of cash bonds -
securities that can be traded on Euroclear, have an ISIN, etc.  The
intial goal is to focus on basic reporting tools for reporting
holdings and risk.  The eventual goal is to include an OMS to model
possible trades and to include a trade blotter.

This project has some severe limitations as a tool.  Most
significantly, GODEL does not include any type of security database,
or pricing source.  So in terms of security information related to an
ISIN (such as the coupon, maturidy date, etc), a commercial system
will need to be used.  There are also third party pricing providers,
the user will also need to find one of these.

This project clearly has a very long way to go, so any contributions
would be greatly appreciated.
