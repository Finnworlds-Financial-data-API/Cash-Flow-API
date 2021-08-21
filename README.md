
<h1>Cash Flow API - Finnworlds</h1>

<p><a href="https://finnworlds.com/finance-data/cash-flow-api/">The Cash Flow API</a> is available through JSON REST API and our databases are also downloadable as an excel or csv file.  We have historical cash flow statements in our database from the IPO of all publicly traded companies. Through our API you can request individual components of the cash flow reports over the history of a company, or you can request the entire cashflow based on ticker symbol or ISIN number of a company. The API is very intuitive and easy to use</p>



<p><a href="https://finnworlds.com/">Finnworlds</a> Our clients are big enterprises as well as individual developers who use the financial data to develop their platforms without having to worry about maintaining an actual database. We take this worry away so that you can focus on your core business.</p>




<p><a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the data right away. We don't have free packages on the website but for students we can do something. Just email us and lets talk about it.</p>



<h2>API Features</h2>



<ul><li><strong>Historical Cash flow statements</strong></li><li><strong>Current cash flow statements</strong></li><li><strong>Filter by individual components</strong></li><li><strong>Extract Cash Flows from multiple companies at once</strong></li><li><strong>Request more features from us</strong></li></ul>


<h2>How to access the data</h2>



<ul><li><strong>JSON rest API</strong></li><li><strong>Excel CSV download</strong></li><li><strong>PDF reports</strong></li><li><strong>Email link</strong></li></ul>



<h2>Documentation</h2>



Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. On top of this we have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>


<h2>Examples</h2>




<p>https://finnworlds.com/api/v1/cashflows?key=YOUR-KEY&stock_ticker_symbol=aapl</p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
        },
        "output": {
            "operating_cash_flow": "104,414,000",
            "investing_cash_flow": "-9,849,000"
            "financing_cash_flow": "-94,328,000"
            "end_cash_position": "35,276,000"
            "income_tax_paid_supplemental_data": "19,627,000"
            "interest_paid_supplemental_data": "2,597,000"
            "capital_expenditure": "-9,646,000"
            "issuance_of_capital_stock": "1,011,000"
            "issuance_of_debt": "22,370,000	"
            "repayment_of_debt": "-7,500,000"
            "repurchase_of_capital_stock": "-83,410,000",
            "free_cash_flow": "94,768,000"
        }
    [





<p>https://finnworlds.com/api/v1/balancesheets?key=YOUR-KEY&sector=technology&industry=consumer_electronics&cash_flow=operating_cash_flow&year=2021</p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "104,414,000",
            },
        "basics": {
            "name": "Microsoft Corporation",
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US5949181045"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "76,740,000",
            },
        "basics": {
            "name": "Dell Technologies Inc",
            "stock_ticker_symbol": "DELL"
            "isin_identifier": "US24703L2025"
            "exchange": "NYSE"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "14,441,000",
            },
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "...",
            }
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "operating_cash_flow": "...",
            },
        }
    [





<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">Finnworlds terms &amp; Conditions</a></p>
