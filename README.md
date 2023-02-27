# Ethereum transactions crawler

Application that allows a user to view transaction data from the Ethereum blockchain associated with a specific wallet address W that the user inputs, starting with block B. The application can get information on:
    <ul>
        <li>wallets (addresses) and amounts of ETH associated with transactions             made to and from the given wallet W </li>
        <li>show them in a simple human-readable way       </li>
    </ul>
The application collects and displays ALL transaction data starting from the given block B. 

<h4>Example:</h4> 

If a user requests to view transactions associated with the address **0xaa7a9ca87d3694b5755f213b5d04094b8d0f0a6f** from block **9000000** to the current block, your application should be able to crawl and visualize all transaction data (addresses that have sent and received tokens from the address 0xaa7a9ca87d3694b5755f213b5d04094b8d0f0a6f, and how much ETH was used for a given transaction) in that period of time.

    
## ----------------------------------------------------------------------------------------- ##
Transactions crawler was written in Python, using Jupyter notebook. Libraries needed to run this script:
- requests
- pandas
- numpy
- seaborn 
- json
- datetime
- matplotlib  
- IPython.display

All libraries can be installed by running _pip install **library_name**_ command in your terminal.
### Also, you can run it immediately by using Google Colab:
https://colab.research.google.com/drive/1e0cSV1ddvXmzGNlSJaM8ipvv7bSZRGXM?usp=sharing
