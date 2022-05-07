---
layout: essay
type: essay
title: "Future Work on Akamy-Rentals"
date: 2022-05-06
labels:
  - Meteor
  - Ethereum blockchain
  - Smart contracts
---

<img class="ui large image" src="https://th.bing.com/th/id/R.9d31e91124d36bb581f26990e4591390?rik=W3opzTamDU73Eg&riu=http%3a%2f%2fmediad.publicbroadcasting.net%2fp%2fkhpr%2ffiles%2fstyles%2fx_large%2fpublic%2f201802%2fIMG_7345.jpg&ehk=D%2bTe%2fVkT77fMqsmcV8piy5t0nhoMPL7sBWG9xG9zr5M%3d&risl=&pid=ImgRaw&r=0">

The current state of the Akamy-Rentals project is incomplete. However, great progress was made on implementing the website that users will interact with to lead to the creation of a smart contract. All the steps and UI components leading up to the deployment of a smart contract inside a blockchain are completed and functional. Specifically, new users can create and sign into their accounts, edit their profiles, learn about smart contracts, and create and edit smart contracts.

Specific functionalities are described below
- Landing page describing smart contracts
- New users can register for a new account
  - Accounts are stored in a MongoDB collection
- Log in and out of their account
- Edit account/profile details
- Learn about smart contracts
- Navbar provides links to other pages
- Dashboard shows important information
  - View select smart contract information on the dashboard
  - Number of active smart contracts
  - Monthly income and payment
  - Links to edit/view smart contracts
  - Transaction log
- Create smart contract drafts (creators are the homeowners)
  - New smart contract drafts are saved to a MongoDB collection
  - The tenant can view the proposed smart contract on their account
- Edit smart contract drafts
  - Edit button link is only visible to homeowners of smart contracts
  - Only homeowners of smart contracts can edit smart contracts
- View smart contract drafts
  - Tenant only feature
  - Tenants can declare if they agree with the smart contract, which the homeowner will be able to see
- Sign smart contracts
  - Tenants and homeowners can electronically sign smart contracts
  - Signature must be the user’s full name
  - When both tenant and homeowner sign the smart contract, then the smart contract can be created in the blockchain (not implemented)
- Transaction log of viewing past payments
- Messenger to contact other users

When the project is completed, publication would be the next step. A workshop would be an ideal venue for publication. The target audience would be homeowners and leasers. Homeowners have a property they are looking to rent out to a tenant and leasers may have a space they are looking to lease to companies as office spaces or restaurants, for example.

The incomplete parts of the project that need to be completed before publication involve the Ethereum blockchain. There are additional improvements that could be made to the UI, but since they are mostly refining the existing functionality to make it easier to create smart contracts, it is not necessary to complete them before publication. However, the audience’s first impressions of the project would be more positive if the improvements were completed before publication. Creation of a smart contract in the blockchain absolutely needs to be completed before publication. The blockchain ensures that the smart contracts are immutable, rent comes in on time and is fully paid, and provides a greater level of assurance for both homeowners and renters. The blockchain is what makes Akamy-Rentals appealing to its target audience due to its uniqueness and automation.

In an enhanced version of the project, user feedback from people who did not contribute to the development of Akamy-Rentals would be needed to assess the strengths and weaknesses of the project. Specifically, feedback from homeowners would be most desired because tenants do not choose whether or not they want to create a smart contract. However, tenant feedback would be useful in ensuring that the UI is easy to use and intuitive. Similarly, since one of the goals of Akamy-Rentals is to make the contract process easier between homeowners and tenants, it is important that the process to create a smart contract is easy and its use of blockchain understood. If the process to create a smart contract is more difficult that the current process to establish a homeowner tenant contract, there will be no appeal to use Akamy-Rentals. On the other hand, user feedback can also help identify components that users like. For example, from our user feedback on the current project iteration, many stated that they liked the large font of the monthly income component at the top of the dashboard page. After obtaining feedback, the project would be enhanced further to polish it for publication. The more polished the project is, the more presentable and appealing it will be to the target audience.
