# Simple-DB-of-Online-Auctions
Simple Database (PL)  for online auctions: Manage users, items, bids &amp; auto-update "Buy Now" prices. Seamlessly integrate with web/mobile apps. Built with Microsoft SQL Server. Ideal for e-commerce platforms, ensuring reliable transaction processing.

Database of Online Auctions
This database project is tailored for managing online auction systems, facilitating efficient user management, item listings, bid submissions, and automatic updates of "Buy Now" prices based on auction activity. Crafted with seamless integration in mind, it serves as the backbone for web and mobile applications dedicated to conducting online auctions.

Key Features:
- **Users:** Streamlined management of user accounts, encompassing authentication credentials and activity logs.
- **Items:** Comprehensive registration of auctioned items, offering categorization and reserve price settings.
- **Auctions:** Seamless handling of auction sessions, including scheduling, and the provision of a "Buy Now" option.
- **Bids:** Intuitive system for users to place bids, featuring automatic validation against reserve prices.

Functionalities:
- **SearchAuctionsByCategory function:** Enables dynamic exploration of auctions based on item categories.
- **SubmitBid procedure:** Facilitates bid submission with automatic validation and acceptance of bids surpassing the current highest bid.
- **UpdateBuyNowPriceAfterBidTrigger:** Automatically adjusts the "Buy Now" price, increasing it by 5% for each new bid to incentivize swift purchases.

Technologies:
Implemented utilizing Microsoft SQL Server, harnessing advanced T-SQL capabilities for managing business logic, encompassing functions, stored procedures, and triggers.

Applications:
Ideal for seamless integration with e-commerce platforms and dedicated online auction applications, serving as a robust backend solution for systems necessitating reliable transaction processing and real-time auction data management.
