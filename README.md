# Caviar Drug Racket Network Ananlysis
## _Network Ananlysis for CAVIAR_

## What are we trying to find?
- Understand about the criminal network with data gathered in 7 different datasets with investigation spanning 2 years.
- Who are the most important personnel to break the chain.
- Understand the importance of these people along the timeline of 2 Years, who became important, who became less important, who stepped away from the network.

## About Dataset
### You can find this dataset in Kaggle 
https://www.kaggle.com/datasets/chiragtagadiya/caviar

Here is some information on the CAVIAR project and the role of certain individuals arrested following the investigation. This investigation lasted two years and ran from 1994 to 1996. The operation brought together investigation units of the Montr´eal police and the Royal Canadian Mounted Police of Canada. During this two year period, 11 wiretap warrants, valid for a period of about two months each, were obtained (11 matrices match these phases). This case is rather unique, because unlike other investigative strategies, the mandate of the CAVIAR project was to seize the drugs without arresting villains. During this period, imports of the trafficking network were hit by the police on eleven occasions. The arrests took place only at the end of the investigation. Monetary losses for traffickers were estimated at 32 million dollars. Eleven seizures took place throughout the investigation. Some phases included no seizures, and others included multiple. Here is what they represent in terms of the amount of money:
- Phase 4 1 seizure 2,500,000 Dollars, 300 kg of marijuana
- Phase 6 3 seizures 1,300,000 Dollars, 2 x 15 kg of marijuana + 1 x 2 kg of cocaine
- Phase 7 1 seizure 3,500,000 Dollars, 401 kg of marijuana
- Phase 8 1 seizure 360,000 Dollars, 9 kg of cocaine
- Phase 9 2 seizures 4,300,000 Dollars, 2 kg of cocaine + 1 x 500 kg marijuana
- Phase 10 1 seizure 18,700,000 Dollars, 2200 kg of marijuana
- Phase 11 2 seizures 1,300,000 Dollars, 12 kg of cocaine + 11 kg of cocaine
This allows us to analyze changes in the network structure and to survey the reaction and adaptation of the participants while they were subjected to an increasing number of distressing constraints.

The network consists of 110 (numbered) players. Players 1-82 are the traffickers. Players 83-110 are the non-traffickers (financial investors; accountants; owners of various importation businesses, etc.). Initially, the investigation targeted Daniel Serero, the alleged mastermind of a drug network in downtown Montréal, who attempted to import marijuana to Canada from Morocco, transiting through Spain. After the first seizure, happening in Phase 4, traffickers reoriented to cocaine import from Colombia, transiting through the United States.

According to the police, the role of 23 of the players in the “Serero organization" are the following, listed by name (unique id):

Daniel Serero (n1) : Mastermind of the network.

Pierre Perlini (n3) : Principal lieutenant of Serero, he executes Serero's instructions.

Alain (n83) and Gérard (n86) Levy : Investors and transporters of money.

Wallace Lee (n85) : Takes care of financial affairs (accountant).

Gaspard Lino (n6): Broker in Spain.

Samir Rabbat (n11): Provider in Morocco.

Lee Gilbert (n88): A trusted man of Wallace Lee (became an informer after the arrest).

Beverly Ashton (n106): Spouse of Lino, transports money and documents.

Antonio Iannacci (n89): Investor.

Mohammed Echouafni (n84): Moroccan investor.

Richard Gleeson (n5), Bruno de Quinzio (n8) and Gabrielle Casale (n76) : Charged with recuperating the marijuana.

Roderik Janouska (n77): Individual with airport contacts.

Patrick Lee (n87): Investor.

Salvatore Panetta (n82): Transport arrangements manager.

Steve Cunha (n96): Transport manager, owner of a legitimate import company (became an informer after the arrest).

Ernesto Morales (n12): Principal organizer of the cocaine import, an intermediary between the Colombians and the Serero organization.

Oscar Nieri (n17): The handyman of Morales.

Richard Brebner (n80): Was transporting the cocaine from the US to Montréal.

Ricardo Negrinotti (n33): Was taking possession of the cocaine in the US to hand it to Brebner.

Johnny Pacheco (n16): Cocaine provider.


## Final Insights Derived from the dataset
- As the degree of centrality and degree of betweeenness of Node 1 our kingpin decreased Node 3 (the Lieutenant) rose up. This signified that as police were concentrating on the Kingpin, he delegated parts of his tasks to liutenant and started to lie low.
- Another important insight is as the context suggests, slowly the flow has shifted towards Cocain smuggling from Columbia and the principle guy rose to power and started to become the hub for interactions.
- As we approach the end of year 2, we see, even the lieutenant started to decrease his connectedness and started lying low.

#### To disrupt this chain, Along with 1 and 3 who are the principals from starting, the rising start the Cocain Import Organizer should be targeted and arrested.

## License

MIT

**Free Software, Hell Yeah!**
