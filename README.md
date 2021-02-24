# EthOn Illustrations


## EthOn model of Ethereum (simplified)
Informal and simplified illustration of an Ethereum network and blockchain modeled with EthOn.
![EthOn model](doc_resources/img/EthOn_overview.png)

## Illustration key
The illustrations basically comply with [VOWL](http://vowl.visualdataweb.org/v2/) for concept illustrations
and [QueryVOWL](http://vowl.visualdataweb.org/queryvowl/v1/index.html) for modeling scheme illustrations.

![Illustration key](doc_resources/img/key.png)
### Account concept
![Account concept](doc_resources/img/account_concept.png)
### Block modeling scheme
![Modelling blocks](doc_resources/img/block_modeling_scheme.png)
### Message, Transaction Receipt and Log concepts
![Message concept](doc_resources/img/message_concept.png)
![Transaction concept](doc_resources/img/transaction_concept.png)
![Transaction Receipt concept](doc_resources/img/tx_receipt_concept.png)
![Contract Message concept](doc_resources/img/contract_message_concept.png)
![Log concept](doc_resources/img/log_concept.png)
### State Transition concept and modeling scheme
![State Transition concept](doc_resources/img/transition_concept.png)
![State Transition modeling scheme](doc_resources/img/transition_modeling_scheme.png)
### Network concept and modeling scheme
![State Transition concept](doc_resources/img/network_concept.png)

## EthOn icon set
![Some of the icons](overview.jpg)

The above is an excerpt of the icon set. There are some more icons in this folder.

The icons were designed by @VladTod. Thank you!

Like the rest of EthOn they are licensed CC-BY

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)](https://creativecommons.org/licenses/by/4.0/)

## Post-processing

### Create png files from the svgs

`find ./ -type f -name "*.svg" -exec inkscape -z -e {}.png -w 512 -h 512 {} \;`

`rename .svg.png .png *.svg.png`

### Cleanup
 - Remove Adobe comment
 - Remove ` style="enable-background:new 0 0 106 106;" xml:space="preserve"`
 - change `id=''` to the full EthOn URI

