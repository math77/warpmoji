# farmoji

An onchain sticker protocol for decentralized social network farcaster.


### Devlog

#### 05/05/2025

Drafting an initial version of the protocol's possible architecture and deciding what features it should have. Researching the best file types for storing the stickers. Deciding between stickers being NFTs or coins. Talking to Jesse, he suggested that as coins they would be more interesting, while I think they might be better as NFTs - deciding between offering both options or being opinionated.

The final project will probably consist of:
- Protocol deployed on base
- Webapp to create sets and upload/manage stickers
- API (easier querying the stickers) 
- SDK that allows searching for available stickers for an specific address/fid
- Decided that there will be static and animated stickers. 
- There's no need for a dedicated web editor at first. Provide an adobe tools plugin that exports the animated file to our custom data type and then the creator uploads it on the webapp and then store this file onchain together with the rest of the information associated with the sticker/set
- The stickers will either be APNG or a customized compressed lottie file type (to reduce the size). Investigating this


#### 05/26/2025

- Still trying to raise funds to develop this project. 
- Renaming to farmoji