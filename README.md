# Cross-chain Rebase Token

1. A protocol that allows user to deposit into a vault and
   in return receive rebase tokens that represent the underlying balance.

2. Rebase token -> balanceOf function is dynamic to show the changing balance
   with time.

- Balance increases linearly with time.
- mint tokens to our users every time they perform an action (mint, burn, transfer, bridge)

3. Interest rate

- Individidually set an interest rate for each user
  based on some global interest rate of the protocol at the time the user deposits into the vault.
- This global interest rate can only decrease to incentivize early adopters.
- Increase token adoption
