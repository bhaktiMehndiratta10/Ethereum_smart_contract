# Ethereum smart contract

The MyToken contract is an Ethereum smart contract that implements a basic token functionality. It allows for the creation, minting, and burning of a custom token.

FEATURES-

1.TOKEN INFORMATION: tokenName: A public variable storing the name of the token. tokenAbbrv: A public variable storing the abbreviation or symbol of the token. totalSupply: A public variable storing the total supply of the token.

2.BALANCES MAPPING: balances: A mapping of Ethereum addresses to their respective token balances.

MINT FUNCTION: mint(address _address, uint _value): A function that mints new tokens and assigns them to a specified address. Increases the total supply by the given _value. Increases the balance of the specified _address by _value.

BURN FUNCTION: burn(address _address, uint _value): A function that burns (destroys) tokens held by a specified address. Requires that the balance of the _address is greater than or equal to _value. Decreases the total supply by the given _value. Decreases the balance of the specified _address by _value.

BALANCE INQUIRY: getBalance(address _address): A function to retrieve the token balance of a specified address. Returns the token balance of the given _address.

TOTAL SUPPLY INQUIRY: getTotalSupply(): A function to retrieve the total supply of the token. Returns the total supply of the token.

USAGE: Deploy the MyToken contract on an Ethereum network.

INTERACT with the contract using the following functions: function mint(address _address, uint _value) public; - Use the mint function to create and distribute new tokens to addresses
    
    function burn(address _address, uint _value) public; - Use the burn function to destroy tokens held by addresses
    
    function getBalance(address _address) public view returns (uint); - Use the getBalance function to query the balance of a specific address
    
    function getTotalSupply() public view returns (uint); - Use the getTotalSupply function to query the total supply of the token


