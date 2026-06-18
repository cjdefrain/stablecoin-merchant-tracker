https://merchant-tracker.streamlit.app/

Data Collection
Overview
Real merchants were identified by analyzing 1.1 million active receiving addresses from June 3-10, 2025. I applied behavioral filters based on patterns typical of actual businesses.

Merchant Identification Criteria
To qualify as a merchant, an address needed to meet ALL of the following criteria:

Minimum 5 transactions - Excludes one-time or rarely used wallets
Minimum 5 unique customers - Ensures actual business activity vs personal transfers
$75+ in total volume - Filters out test transactions and micro-payments
Average payment size between $1-100 - Typical retail transaction range
Maximum 80% customer concentration - Excludes personal wallets receiving from single sources
Geographic Estimation
I analyzed peak transaction hours for each wallet to estimate time zones:

Calculated hourly transaction distribution for each merchant
Identified peak activity hours (when most transactions occurred)
Assumed merchants operate during typical business hours (9 AM - 5 PM local time)
Mapped peak UTC hours to likely time zones and regions
Distributed merchants within regions based on crypto adoption rates from industry reports
Network Scaling
With approximately 3 million daily active addresses on TRON as of June 2025, my analysis covered roughly one-third of all transactions. I applied a 2.5x multiplier to estimate total network activity:

Analyzed: ~3,400 merchants from 1.1M addresses
Estimated Total: ~8,500 USDT merchants on TRON globally
Data Sources
Blockchain Data: TRON mainnet via Bitquery API
Transaction Period: June 3-10, 2025
Crypto Adoption Rates: Chainanalysis Global Crypto Adoption Index 2024
Analysis Date: June 2025
Limitations
Currency Scope: Analysis limited to USDT transactions only
Geographic Accuracy: Time zone estimation may not reflect actual physical locations for all merchants
Temporal Snapshot: Data represents one week in June 2025; adoption patterns evolve rapidly
Exchange Exclusion: Methodology filters out centralized exchanges but may include some P2P traders
Payment Processors: Some identified "merchants" may be payment aggregators serving multiple businesses
