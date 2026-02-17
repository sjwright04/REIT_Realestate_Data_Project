This project is an end-to-end REIT risk-scanning pipeline that builds a REIT universe, stores it in a SQLite database, and continuously enriches it with SEC and market data.
It downloads recent 10-K and 10-Q filings, extracts key financial metrics, and computes leverage/liquidity-based risk scores for each company. It also pulls text sections
(like MD&A and Risk Factors) and applies NLP analysis to detect distress signals such as covenant pressure, liquidity concerns, and forced asset-sale risk. The final outputs
are structured tables and export files that support ranking and monitoring potentially distressed REITs.
