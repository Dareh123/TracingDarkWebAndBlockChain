# Unveiling Offshore Banking and Dark Web Operations via Blockchain Analysis: An OSINT Case Study

### Cryptocurrency Crimes and Dark Web Links
Cryptocurrency scams and crimes are becoming common, and the dark web often serves as a hub due to its anonymity. But even on the dark web, onion sites can leave behind clues, or 'digital fingerprints,' that help uncover hidden connections.

***In this case study, we’ll cover:***

- Finding Links Between Onion Sites: How to spot connections between dark web platforms.
- Tracing Bitcoin Transactions: How to connect two Bitcoin addresses.
- Tracking to Exchanges: How to trace transactions back to registered cryptocurrency exchanges.

## Here’s a visual overview of what we’ll be exploring:
![image](https://github.com/user-attachments/assets/24c4880d-c10a-448d-8899-d9ca386c113b)

---

**Dark Web Services — Two Examples**  

In this case study, we’ll focus on three dark web services:  

1. **[BancoPanama](http://bancopanuemswrrz.onion/index.html)** : A banking site offering anonymous offshore accounts in exchange for Bitcoin.  
2. **[UnlockDevices](http://unlockdehrka3cbn.onion/#home)** : A service that lets users unlock phones anonymously by paying with Bitcoin.  
3. **[Dark Web](http://unlockdehrka3cbn.onion/#home)** : The Onion Site.  

---  
![image](https://github.com/user-attachments/assets/8d2f44d1-ada0-458e-a3b0-8a8c29eb1422)

![image](https://github.com/user-attachments/assets/f2749a6b-8316-421d-be58-b8fcab778dfb)

- This case study is not to identify whether these are scam sites or not. Rather, it is to identify the relationship between them, to show that they are owned by the same person, and to trace their blockchain fingerprints to a registered cryptocurrency exchange.
---

**Analysis Tools for Dark Web Onion Sites**  

In this case study, we will utilize the following four tools for analysis:  

1. **[Fresh Onions](http://zlal32teyptf4tvi.onion/)**: A directory of newly discovered onion sites on the dark web.  
2. **[Wallet Explorer](https://www.walletexplorer.com/)**: A tool to analyze and trace Bitcoin transactions and wallets.  
3. **[Blockchain Explorer](https://www.blockchain.com/explorer)**: A comprehensive tool for exploring blockchain transactions and addresses.  
4. **[Tor Browser](https://www.torproject.org/)**: A privacy-focused browser for accessing onion sites on the dark web.  

Among these, the two most critical tools are **Fresh Onions** and **Wallet Explorer**, as they play a pivotal role in uncovering relationships and transactions tied to onion sites.  

---

**Tool Descriptions**  

1. **Fresh Onions**  
   Fresh Onions is a web crawler designed specifically for onion sites. It helps uncover hidden information that might not be immediately visible on these sites, making it invaluable for identifying the "digital fingerprints" we are looking for in this investigation.  

2. **Wallet Explorer**  
   Wallet Explorer is an excellent tool for analyzing cryptocurrency wallets. It identifies all Bitcoin addresses owned by a single wallet, which is crucial when tracing transactions and understanding the relationships between multiple addresses.  

3. **Blockchain Explorer**  
   Blockchain Explorer is a platform you might already be familiar with. It allows for a detailed examination of blockchain transactions and Bitcoin addresses, providing transparency and traceability in cryptocurrency activities.  

4. **Tor Browser**  
   Tor Browser is essential for accessing onion links and navigating the dark web securely. It is required to open the onion links mentioned in this case study.  

---  

### Identifying ‘Fingerprints’ Of Dark Web Services
![image](https://github.com/user-attachments/assets/76f568d7-2f36-4937-b8c6-817c40469069)

- The relationship between these two dark web onion sites can identified using the Fresh Onion crawler.

- The relevant details we are looking for is an ‘SSH Fingerprint’. Essentially it is a unique marker a site will carry. With Fresh Onions, we can see all of the other sites that hold that same fingerprint.

![image](https://github.com/user-attachments/assets/82ead337-b2a6-46eb-9ea5-81bd529a20f8)

- This shows that there is a SSH relationship between the two onion sites we identified earlier.

***Now let’s take a look at the blockchain evidence.***
---

**How to Use Blockchain Forensics on Transactions**  

The first step in analyzing a dark web site is identifying its cryptocurrency address.  

While various cryptocurrencies might be in use, Bitcoin remains the most popular and, fortunately, has a transparent and public blockchain.  

From a single Bitcoin address, you can uncover valuable insights, including:  
- The total number of transactions.  
- The origins and amounts of incoming funds.  
- The destinations and amounts of outgoing funds.  
- A complete historical timeline of all transactions.  
- Other Bitcoin addresses associated with the same wallet.  

This last point is where **Wallet Explorer** proves to be particularly useful. With this tool, you can identify all Bitcoin addresses linked to a single wallet, making it easier to track and analyze transactions.  

---  
![image](https://github.com/user-attachments/assets/1771908c-83fc-44b6-b000-798e16bea1d7)
- So what’s the relationship between the two sites I mentioned?
---

**Identifying Bitcoin Addresses and Their Relationship**  

When we examine the Bitcoin addresses through the ‘purchase’ section of the websites, we can identify two main addresses:  

- The Bitcoin address of the **BancoPanama** site, ending in **XZ4jo**.  
- The Bitcoin address of the **Dark Web UnlockDevices** site, ending in **KUrE**.  

The key observation here is that both addresses belong to the same wallet, indicating that they are owned by the same entity or individual.  

I discovered this relationship using **Wallet Explorer**. By entering one of the Bitcoin addresses into the search bar, we can access the entire wallet and reveal both addresses. A simple ‘CTRL+F’ search highlights that both addresses are part of the same wallet.

---  

![image](https://github.com/user-attachments/assets/0b071ca4-a106-4143-b726-e0a0f6052026)
- Now let’s take a look at the specific transactions of each of these bitcoin addresses.
---

**Tracing the Payments Through to an Exchange**

The transactions made to these accounts are typical of normal blockchain transactions.

For example, in the **[transaction below](https://www.blockchain.com/btc/tx/ee323b528c63bdd9c92ec1ddb4f7ef55bb2545da65e573e19e136046f754148d)**, we see money being transferred from one Bitcoin address to the Dark Web UnlockDevices address, which ends in **KUrE**.

![image](https://github.com/user-attachments/assets/fd3dd67b-9d95-4b14-a4e6-0e4a71683d06)


---
But following the **[outgoing transactions](https://www.blockchain.com/btc/tx/3ca9cc1700f95ffab2751b268cffc4c36194d3678b12fc7f836120b9d0556e35)** use more addresses:

![image](https://github.com/user-attachments/assets/2e98b610-e6c0-427f-ad4d-386edc0a4c86)
- As you can see in the screenshot above, there are a number of addresses included in the same exchange.

For this transaction, the key recipient address ending in Ndpe can be one of two things:

- A bitcoin mixing service, or
- An exchange

For many vendors on the dark web, a mixing service, or cryptocurrency tumbler, guarantees anonymity as it essentially scrambles the addresses and the payments made — perfect for illegal vendors and scammers, not for law enforcement.

- Ndpe is a unique address as the majority of its payments are made into bitcoin address 1NDyJtNTjmwk5xPNhjgAMu4HDHigtobu1s.

***You can see this in the screenshots below***:

![image](https://github.com/user-attachments/assets/52220169-007b-4c7c-9962-83e83bbbaf12)
![image](https://github.com/user-attachments/assets/07cb9278-536f-4419-bed7-b4f19185dd04)
![image](https://github.com/user-attachments/assets/fb4c1be9-10a6-4e2b-9581-a0b3b7292a66)
![image](https://github.com/user-attachments/assets/0a0024e5-5d0f-40e5-b465-1a5a3899bb39)
- This bitcoin address ending in bu1s belongs to Binance, a registered cryptocurrency exchange.
We can see this through a simple Google search, which also reveals the following Tweet from Binance themselves.

---

**Blockchain Analysis of the Ndpe Address**

The **Ndpe** address belongs to the wallet **000030bc2e**.

As shown in the screenshot below, this wallet contains over **120,000 Bitcoin addresses**, many of which are involved in large volumes of transactions on a daily basis.

Given the volume and nature of the transactions, it’s likely that **Ndpe** is associated with a cryptocurrency exchange, or it could be a **Bitcoin tumbling service**. The large number of addresses within this wallet could suggest that it is used to mix or "scramble" transactions, a common practice for enhancing privacy by obfuscating the transaction's original source.

![image](https://github.com/user-attachments/assets/dbd04eae-8d98-456f-9f7b-d96ecb411711)
- Each one of the addresses in this wallet use Binance as the final source of all of their transactions.

In the above screenshot, the top five addresses all show their largest payouts to Binance. We can see this on the blockchain.

Here is a recent outgoing transaction to Binance from Fnhy:

![image](https://github.com/user-attachments/assets/c0842c3d-76ca-4bf4-ad3c-74d03440481a)
- Here is a recent outgoing transaction to Binance from sjjd:

![image](https://github.com/user-attachments/assets/06d77044-0fad-4f38-b2b3-355ec28e9bec)
- Here is a recent outgoing transaction to Binance from d6E1:

![image](https://github.com/user-attachments/assets/48cbec3e-420b-402e-9280-8939768dd1c7)
Here is a recent outgoing transaction to Binance from 3R3r:

![image](https://github.com/user-attachments/assets/3fc1faa8-f6f0-4053-8107-ffe5ce88bbbc)
- Here is a recent outgoing transaction to Binance from hEe9:

![image](https://github.com/user-attachments/assets/a4b041c6-e91c-4b10-b4b5-bb4a5c9083ee)

- As you can see, there is a relationship of funds from these two dark web onion sites, to the Ndpe address on the blockchain. Since we have established that these two dark web onion sites are ran by the same owner, it is likely the person is using a single tumbler or exchange. There is also an ongoing financial relationship between the Ndpe address, and other addresses in the same wallet, and Binance’s address ending in bu1s.

---
### Where Open-Source Methods Stop

***While open-source tools and methods can provide valuable insights into activities on the dark web and the blockchain, they have their limitations. At a certain point, further investigation requires more than just publicly available information. This is where law enforcement agencies, regulatory bodies, and cryptocurrency exchanges play a critical role. These entities have access to private data and the ability to work with legal authorities to trace and uncover the registration details of accounts linked to illicit activities on the dark web.***

### Conclusion and Insights
This case study demonstrates how open-source intelligence (OSINT) and blockchain forensics can help uncover illicit activities on the dark web. By linking dark web sites to cryptocurrency addresses and tracing the flow of funds, investigators can uncover relationships between seemingly unrelated sites and services. However, the involvement of privacy-enhancing technologies like mixing services and the need for private data access underlines the importance of collaboration between law enforcement and cryptocurrency exchanges for comprehensive investigations.

This investigation showcases the potential of blockchain analysis for tracking illegal activities, but also highlights the challenges of dealing with privacy-enhancing technologies and the need for further cooperation between public and private entities in cybersecurity investigations.

## Contributing

Contributions are welcome! To contribute, fork the repository and submit a pull request with your improvements.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [E-Mail Me](mailto:fk776794@gmail.com?subject=Feedback%20on%20Faizan%20Net&body=Hello%20Faizan,%0A%0AI%20have%20some%20feedback%20to%20share%20about%20your%20Faizan%20Net%20tool.%0A%0A%2D%20Issue%2FComplaint%3A%20[Please%20describe%20the%20issue%20or%20complaint]%0A%2D%20Suggestions%2FChanges%3A%20[Please%20provide%20your%20suggestions%20or%20changes]%0A%0AThank%20you!%0A%0ARegards,%0A[Your%20Name])

<!-- display the social media buttons in your README -->

[![instagram](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Instagram.png (Instagram))][2]
[![twitter](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Twitter.png (Twitter))][3]
[![linkedin](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/LinkedIn.png (LinkedIn))][4]
[![github](https://github.com/shikhar1020jais1/Git-Social/blob/master/Icons/Github.png (Github))][5]

<!-- To Link your profile to the media buttons -->

[2]: https://www.instagram.com/EthicalFaizann
[3]: https://www.twitter.com/EthicalFaizan
[4]: https://www.linkedin.com/in/EthicalFaizan
[5]: https://www.github.com/faizan-khanx

## GITHUB STATS

![Faizan's GitHub stats](https://github-readme-stats.vercel.app/api?username=faizan-khanx&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&theme=dark#gh-dark-mode-only)



















