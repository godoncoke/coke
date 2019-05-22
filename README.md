

IDOPROFITIDOCOKE Core staging tree 0.12.2.2
=========================================

What is IDOPROFITIDOCOKE?
--------

IDOPROFITIDOCOKE is the future

IDOPROFITIDOCOKE Specifications
--------

- Release date: 22/05/2019 / 
- Premine ~ 4%                          
- ASIC resistance                                                 
- NeoScrypt hashing algorithm                                      
- Difficulty retargets using Dark Gravity Wave                     
- CPU/GPU/ mining                                                    
- Block reward is controlled by: 2222222/(((Difficulty+2600)/9)^2)
- Block generation: 2.5 minutes                                   
- InstantSend confirmation: ~5 seconds                            
- Est. ~22M Max Coins                                             
- Decentralized Masternode Network                                
- Superior Transaction Anonymity using PrivateSend                
- Mastenode reward:                

| Block         | Award MN           | 
| ------------- |:------------------:| 
| 0             | 20.0%              | 
| 158000        | 25.0%              | 
| 175280        | 30.0%              |  
| 192560        | 35.0%              |
| 209840        | 37.5%              |
| 227120        | 40.0%              |
| 244400        | 42.5%              |
| 261680        | 45.0%              |
| 278960        | 47.5%              |
| 313520        | 50.0%              |



License
--------

IDOPROFITIDOCOKE Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

Development Process
--------

The master branch is meant to be stable. Development is normally done in separate branches. Tags are created to indicate new official, stable release versions of IDOPROFITIDOCOKE Core.

The contribution workflow is described in CONTRIBUTING.md.

Testing
--------

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.

Automated Testing
--------

Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check

There are also regression and integration tests of the RPC interface, written in Python, that are run automatically on the build server. These tests can be run (if the test dependencies are installed) with: qa/pull-tester/rpc-tests.py

The Travis CI system makes sure that every pull request is built for Windows and Linux, OS X, and that unit and sanity tests are automatically run.

Manual Quality Assurance (QA) Testing
--------

Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.
