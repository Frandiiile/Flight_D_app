Flight Surety Gas Consumption
=============================

.. code-block:: shell

  ·--------------------------------------------|---------------------------|-------------|----------------------------·
  |    Solc version: 0.7.6+commit.7338295f     ·  Optimizer enabled: true  ·  Runs: 200  ·  Block limit: 6718946 gas  │
  ·············································|···························|·············|·····························
  |  Methods                                                                                                          │
  ····················|························|·············|·············|·············|·············|···············
  |  Contract         ·  Method                ·  Min        ·  Max        ·  Avg        ·  # calls    ·  usd (avg)   │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  buyFlightInsurance    ·          -  ·          -  ·     115438  ·          3  ·           -  │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  fetchFlightStatus     ·          -  ·          -  ·      54950  ·          2  ·           -  │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  fundAirline           ·          -  ·          -  ·      71649  ·          2  ·           -  │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  registerFlight        ·          -  ·          -  ·     104269  ·          2  ·           -  │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  registerOracle        ·     143550  ·     150032  ·     145158  ·         20  ·           -  │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  submitOracleResponse  ·      55961  ·     140225  ·      89049  ·          3  ·           -  │
  ····················|························|·············|·············|·············|·············|···············
  |  FlightSuretyApp  ·  withdrawBalance       ·          -  ·          -  ·      30667  ·          1  ·           -  │
  ·-------------------|------------------------|-------------|-------------|-------------|-------------|--------------·