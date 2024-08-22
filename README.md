# leo-rust

The bootcamp was created on Coin Ex and Aleo to introduce developer to Leo Programming Language which is built on Rust.
The programme was divided into three workshop as follows:


## Workshop 1
The following processes were followed:

### Process
1. Install rust on your user computer. This is after Microsoft Visual Studio Code has been downloaded.
2. Next, clone the leo repo from their official github page. `git clone https://github.com/AleoHQ/leo`
3. Leo Wallet extension was also installed. 
4. Leo Wallet Discord Channel joined and tokens acquired.
5. Next `cd leo`
6. `cargo install --path .` to install the dependencies.
7. `leo new michaelnewexample`. **Note:** The name of your project must be in lowercase and can be any random name.
8. `cd todolist`
9. Next, change the `PRIVATE_KEY` in your `.env` file to your PRIVATE_KEY. PRIVATE_KEY is available on the wallet.
10. `leo run`
11. `leo deploy`

**Transaction ID Generated after deployment was:** at1vwyfnpfgdwu3a2hmqx6jfsnerlye2fjd223qtpeqtpntnxvjacqq20yvuf

![Screenshot 1](https://github.com/user-attachments/assets/e272fc91-da48-4b8f-afd8-06c9dc424040)


## Workshop 2

### Process
1. This workshop served to introduce the transfer process on leo.
2. Create a new project in examples `leo new newproject`. **Note also:** The name of your project must be in lowercase and can be any random name.
3. Next process is to input the following commands:
4. `cd newproject`
5. Change the PRIVATE_KEY in your .env file to as in Workshop one to yours.
6. `leo run mint yourwalletaddress 1000u64 --network testnet`
7. `leo run transfer "token" yourwalletaddress 100u64 --network testnet`
8. `leo deploy`

**Transaction ID:** at1fh9j568zl9d05wewd32hhsezsrn2rpeywk3ep7dlwj7dp5htacgqajm0nc

![Screenshot 2](https://github.com/user-attachments/assets/93d11e10-f754-453f-aab4-ec9d6bf1b6ca)
![Screenshot 3](https://github.com/user-attachments/assets/e1937165-6382-4c2d-92f3-62abdadb47d3)


## Workshop 3

### Process
1. The final project was to demonstrate how an actual transfer works across sender and receiver wallets.
2. Create a new project in examples `leo new newproject`. **Note also:** The name of your project must be in lowercase and can be any random name.
3. `cd newproject`
4. Change the PRIVATE_KEY in your .env file to yours
5. `leo run combine_hash_owner_reciever yourwalletaddress receiverwalletaddress`
6. `leo run`
7. `leo deploy`

**Transaction ID:** at12rykd2swq6tmv9eaheqxfwyyszzddqd5zdqw4gme9tt4u2paryyqc36nst

![Screenshot 4](https://github.com/user-attachments/assets/a7b1dc95-3518-4413-9276-db3d095f100b)
![Screenshot 5](https://github.com/user-attachments/assets/f7a1f34a-2849-41d2-b2bf-1e8ad2b81bed)
![Screenshot 6](https://github.com/user-attachments/assets/efa4bd69-0435-4a26-9d94-a17761d0afb0)
![Screenshot 7](https://github.com/user-attachments/assets/ff755a74-ca5a-410c-a4da-f6b13009a958)


