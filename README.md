# Sintax-Licensed
[![Run on Repl.it](https://repl.it/github/scastradio/Sintax-Licensed)](https://repl.it/github/scastradio/Sintax-Licensed)

If you don's see the above button click [here](https://repl.it/github/scastradio/Sintax-Licensed) to deploy DIRECTLY to your replit account!

Once deployed, please remember to set this replit as an "Always on" replit available on a hacker subscription.

You will need to edit config.ini as follows:

**collection_name** This is your Magic Eden Name you submitted during listing. This can also be retrieved via your listing page (its the last little bit on the URL)

**threshold,2,3** These are the levels at which you would like to apply SinTax. They should be ascending and correspond with the various tax levels. SET THEM ALL TO THE SAME TO DISABLE TIERING TAX

**royalties** This is your original royalty percentage in basis points

**sintax,2,3** These correspond to your thresholds and should be DECENDING. Any NFT found BELOW the matching threshold will be taxed with the. appropriate level. SET THEM ALL TO THE SAME TO DISABLE TIERING TAX. This should be specified in basis points.

**rpc** Quite self explanitory. We have had great success with Quicknode and highly recommend them. Figment datahub works well too.

**wallet** This is the wallet IN SOLANA CLI. ie. it will need to be bytecode not base58 ([234,12,67...])

**sleep** The time waited between cycles

DON'T FORGET. YOU WILL NEED A SINNY IN THE WALLET SPECIFIED TO OPERATE THIS SOFTWARE. They can be purchased off magic eden!

For more info please join http://discord.gg/paperhands and open a support ticket.

Thanks and use responsibly!