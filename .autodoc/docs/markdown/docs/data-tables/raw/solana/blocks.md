[View code on GitHub](https://dune.com/docs/data-tables/raw/solana/blocks.md)

# Blocks

## Solana.blocks

This section of the app technical guide covers the `Solana.blocks` table, which contains block data within Solana's blockchain. The purpose of this table is to identify block activity and transaction changes over time. The table includes several columns such as `hash`, `height`, `slot`, `time`, `date`, `parent_slot`, `previous_block___hash`, `total_transactions`, `successful_transactions`, and `failed_transactions`. Each column has a specific data type and description, which is explained in the table.

For example, the `hash` column is a string that represents the hash of the block, base-58 encoded. The `height` column is a bigint that represents the number of blocks beneath this block. The `time` column is a timestamp that represents the estimated time this block was produced. The `total_transactions` column is a bigint that represents the total number of transactions in this block. The `successful_transactions` column is a bigint that represents the number of successful transactions in this block. The `failed_transactions` column is a bigint that represents the number of failed transactions in this block.

The guide also provides two Solana Query examples that can be used with the `Solana.blocks` table. The first example is "Solana blocks over time," which can be found at [https://dune.xyz/queries/389979](https://dune.xyz/queries/389979). This query shows the number of blocks produced over time. The second example is "Transactions per day," which can be found at [https://dune.xyz/queries/390045](https://dune.xyz/queries/390045). This query shows the number of transactions produced per day.

Overall, this section of the app technical guide provides a detailed explanation of the `Solana.blocks` table and its columns. It also provides useful examples of Solana Queries that can be used with this table.
## Questions: 
 1. What is the purpose of the `hash` column in the `Solana.blocks` table?
- The `hash` column in the `Solana.blocks` table contains the hash of each block in Solana's blockchain, encoded in base-58. A blockchain SQL analyst might want to know how this hash is generated and how it is used within the blockchain.

2. How can the `Solana.blocks` table be used to analyze transaction activity over time?
- The `Solana.blocks` table can be used to identify block activity and transaction changes over time. A blockchain SQL analyst might want to know how to join this table with other tables in order to analyze transaction activity in more detail.

3. Are there any limitations to the data provided in the `Solana.blocks` table?
- The `Solana.blocks` table provides information on the number of successful and failed transactions in each block, but it does not provide details on the specific transactions themselves. A blockchain SQL analyst might want to know if there are any other limitations to the data provided in this table, and if there are other tables or data sources that can be used to supplement this information.