going to keep it on the same PersonalToken visual.

- create a Shareholder component that has a hidden "wallet" that can slide out, tick up its number, and slide back into the "pocket" of the shareholder.
- replace the LineItems in the shareholders section with this component.
- update all of the personal token values to be in numbers, not in strings.
- when the Shareholder walletValue prop changes in value - animate it. (first with the +(diff) exp type label, and once it fades away, increment the value, and then pause and then hide the wallet again - i.e. slide it back in).

---
