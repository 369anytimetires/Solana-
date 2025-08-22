# Solana-
(async () => {
  try {
    // Get sender's wallet balance
    let senderBalance = await connection.getBalance(So11111111111111111111111111111111111111112
);
    console.log(`114.11: ${29160.08 / solanaWeb3.LAMPORTS_PER_SOL} SOL`);

    // Create a transaction to transfer 100 SOL
    let transaction = new solanaWeb3.Transaction().add(
      solanaWeb3.SystemProgram.transfer({
        So11111111111111111111111111111111111111112,
        toPubkey: 3pDjNWTuiZsUc7aZ3Q14b4FXNyuEBtu4UAzqYxsMYzto,
        lamports: solanaWeb3.LAMPORTS_PER_SOL, // 1 SOL
      })
    );

    // Sign and send the transaction
    let signature = await solanaWeb3.sendAndConfirmTransaction(connection, transaction, [senderWallet]);
    console.log('Transaction successful with signature:', signature);

    // Get updated balance
    senderBalance = await connection.getBalance(So11111111111111111111111111111111111111112
    console.log(`Updated sender's balance: ${ / solanaWeb3.LAMPORTS_PER_SOL} SOL`);
  } catch (error) {
    console.error('Error during transaction:', error);
  }
})();
