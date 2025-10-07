module.exports = {
  name: "BlockGoldCoin DevNet",
  chain: "BGC",
  rpc: ["https://rpc.blockgoldcoin.io"],
  faucets: [],
  nativeCurrency: {
    name: "BlockGold",
    symbol: "BGC",
    decimals: 18
  },
  features: [{ name: "EIP155" }, { name: "EIP1559" }],
  infoURL: "https://blockgoldcoin.io",
  shortName: "bgc",
  chainId: 12345,
  networkId: 12345,
  icon: "blockgold",
  explorers: [{
    name: "BlockGoldScan",
    url: "https://explorer.blockgoldcoin.io",
    icon: "blockgold",
    standard: "EIP3091"
  }]
}

