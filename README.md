# Raydium PumpFun Bot

A Solana DeFi bot for creating and interacting with Raydium liquidity pools.

## Overview

This project implements a Solana program that interacts with Raydium AMM to create liquidity pools, add liquidity, perform swaps, and manage token pairs. The bot is designed to automate various DeFi operations with Raydium on Solana.

## Deployed Program

- Program Address: [3CCu4f3hXKne4i5uE7DHkiA9o4oqeAAFBNxR3BfYLivX](https://solscan.io/account/3CCu4f3hXKne4i5uE7DHkiA9o4oqeAAFBNxR3BfYLivX?cluster=devnet) (Devnet)

## Key Transactions

- Config Transaction: [9977V82eQoGq1GLmcabizpLeVwtG6MjpEyDVvikG4J7VhcawwQ7uxEtJVumj1nCs5nsfDYTFRcRv4pvPyWRFh3a](https://solscan.io/tx/9977V82eQoGq1GLmcabizpLeVwtG6MjpEyDVvikG4J7VhcawwQ7uxEtJVumj1nCs5nsfDYTFRcRv4pvPyWRFh3a?cluster=devnet)

- Token Launch: [2Yc9N9oDQKkh2U89i3r7ciBJEUfSWAeVTVvmrLKs15wfJg1kK4Ax1J8uBxuBSExcQApCQBMw8nzxXLQrE14Ghn61](https://solscan.io/tx/2Yc9N9oDQKkh2U89i3r7ciBJEUfSWAeVTVvmrLKs15wfJg1kK4Ax1J8uBxuBSExcQApCQBMw8nzxXLQrE14Ghn61?cluster=devnet)

- Swap Transaction: [3z9puJ6Jcum1iQ9eA5q6hxoaVAKyKGkFFJuwqBjcrmgrA6xbpiLxwB5GDpD3cD7Wzuo48NViAZKKT9u72N6QSxPS](https://solscan.io/tx/3z9puJ6Jcum1iQ9eA5q6hxoaVAKyKGkFFJuwqBjcrmgrA6xbpiLxwB5GDpD3cD7Wzuo48NViAZKKT9u72N6QSxPS?cluster=devnet)

- Curve Reach: [2QtdKZrhYuwJtWrd7dhja8mnNqZSmR4qbpo9iSLnrhkZADF3zzm8DojYVisvVaiGAkgmoU4ocSyo65EewJkpjvNo](https://solscan.io/tx/2QtdKZrhYuwJtWrd7dhja8mnNqZSmR4qbpo9iSLnrhkZADF3zzm8DojYVisvVaiGAkgmoU4ocSyo65EewJkpjvNo?cluster=devnet)

- Withdraw Transaction: [21VnRkwjGSCgUJY4KUtaNf2Sc13BUpjXp8nCmMhUFn8PPFNMkFywJFY79ZzhdVhuQUwSjmhAbyuhQutamw8Fj27u](https://solscan.io/tx/21VnRkwjGSCgUJY4KUtaNf2Sc13BUpjXp8nCmMhUFn8PPFNMkFywJFY79ZzhdVhuQUwSjmhAbyuhQutamw8Fj27u?cluster=devnet)

## Features

- **Initialize AMM Configuration**: Set up custom AMM parameters and fee structures
- **Create Raydium Pools**: Create new liquidity pools integrated with Raydium AMM
- **Add Liquidity**: Add token liquidity to existing pools
- **Swap Tokens**: Perform token swaps with automated pricing based on the constant product formula
- **Remove Liquidity**: Allow users to withdraw their liquidity from pools

## Key Parameters

- Initial Price: 600 lamports per token
- Default fees: Configurable through the initialization instruction

## Development

This project is built using:
- Anchor Framework v0.29.0
- Solana Program Library
- Raydium Contract Instructions

## Repository

GitHub: [github.com/adamsandler14/raydium-pumpfun-bot](https://github.com/adamsandler14/raydium-pumpfun-bot.git)
