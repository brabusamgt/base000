# base000
Detecting Wallets That Immediately Interact After Funding
fund_block = funding_block[wallet]
first_tx_block = first_tx_block_seen[wallet]

if first_tx_block - fund_block <= 1:
    print("Instantly active wallet:", wallet)
