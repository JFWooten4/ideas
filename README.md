Names are not extensively contemplated. 💭

# github work tool 9000

An open-source platform for contributing to open-source projects.

- Triages all issues on GitHub, ideally relatively swiftly.
- Some kind of AI to understand the issue
  - Could analyze the repo
  - Could analyze related docs or GH wiki
  - Could analyze previous commits or their authors
- Earn money, reputation, tenure...

## Implementation site

- Anyone can login/auth they control an org
- Orgs can get "labor tokens" based on DAO alloc
- Distribute to accounts on the platform
  - Accounts are identified as GitHub accounts
  - Tokens can be sent without someone having configured (like early PayPal to an email)
  - To prove it's your account, you make a public gist with your public key (or set `username.xlm`) and then do a crypto proof to some kind of central `legacyDistribution` bot (whereas future transfers are all on-chain for transparency)

# Markdown footnote numeric references

This is far on my back-burned, and I'd appreciate if someone else did it lol

Basically need to impliment a markdown feature where you can reference the number of a [^footnote]

For any sizable docs, this is paramount to being able to edit after a "final" export, or otherwise interoperate between files

My rudamentary idea for the format is something like {{^footnote}} returns the number of FN if ∃^footnote.
