

PDApp_Interface folder represents dApp UI.
Contracts folder represents smart contract codes for dApp

## pDapp_Interface

-- Install Dependencies

yarn

-- Run

yarn start

##  Contract

- How to Build -
   - cd to 'build' directory
   - run the command 'cmake ..'
   - run the command 'make'

 - After build -
   - The built smart contract is under the 'pDapp' directory in the 'build' directory
   - You can then do a 'set contract' action with 'cleos' and point in to the './build/pDapp' directory

 - Additions to CMake should be done to the CMakeLists.txt in the './src' directory and not in the top level CMakeLists.txt

## License

MIT


