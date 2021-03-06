# What is Golem

Golem is a decentralized marketplace for computing power. It enables CPUs and GPUs to connect in a peer-to-peer network, enabling both application owners and individual users ("requestors") to rent resources from other users’ ("providers") machines. These resources can be used to complete tasks requiring any amount of computation time and capacity.
Nowadays, centralized cloud providers are in control of these services, these platforms are constrained by closed networks, proprietary payment systems, and hard-coded provisioning operations. Golem proposes an open-source, decentralized and user controlled alternative.

One core component to Golem’s built-in feature set is an [**Ethereum-based transaction system**](/About/Payments), which enables direct payments between requestors, providers, and software developers.

#### Who can use Golem

Golem can be used by **everyone who owns a computer**. How you choose to use Golem depends on what you use your computer for. If you want to lease your computing power, you will probably choose becoming a provider. Requestors send tasks to the network, and those tasks are accepted by the providers - then through the app, the provider performs such computations, and upon completion, the requestor issues the payment.  
Golem is aimed for developers as well, who can build their own use-cases and integrations, supported by
[Golem Factory](/About/Use-Cases).

## Vision
> "With Golem, anyone will be able to rent their unused computing resources. Simultaneously, Golem will enable any user to buy computing time from other users to complete virtually any computationally demanding task. Consequently, Golem will create the first global market for idle computing power. Golem is a decentralized P2P network that uses Ethereum and smart contracts for transactions."

Our first live use-case was introduced in Brass Beta for **Blender artists** and has been available for some time now, this was followed by our second use-case, [**gWASM**](Products/gWASM/About). Right now Clay Beta is available to give programmers access to the [**Task API**](https://taskapi.docs.golem.network) that allows them to create their own integrations. If you are a CGI professional scientist, developer, financial market tycoon, cryptocurrency miner or anybody needing to rent our spare computing power to perform tasks - you can join the network as a requestor and start renting computing power. The possibility to develop your own integration straight from the codebase is always open. 
When a task is submitted to the network by the requestors, and later completed by the providers, requestors must pay upon the task completion for the work performed.
In regards of tasks requiring proprietary software - Golem will enable this use-cases via its App Registry.
For owners of open source or proprietary software (rendering engines, analytical packages, trading robots, scientific packages, or dApps): Golem acts as a distribution channel and (upon opting in for charging for usage) as a marketplace.
Golem’s function as the backbone of a decentralized market for computing power can be considered both:

?>**Infrastructure-as-a-Service (IaaS)**

?>**Platform-as-a-Service (PaaS)**

However, Golem’s strongest proposal relies on the addition of *dedicated software integrations* to the equation. [**Any interested party**](/About/Use-Cases) is free to create and deploy software to the Golem network by publishing it to the Application Registry. The Transaction Framework enables developers to extend and customize the payment mechanism resulting in unique new alternatives for software monetization.

#### How Golem will help to build a new Internet of tomorrow

In the future, the Internet will be a truly decentralized network, enabling users to securely and directly exchange content, without third-party involvement. Golem will be used not only to compute specific tasks, but also to bulk-rent machines in order to perform operations within a self-organizing network.
However, the simultaneous development of other technologies is required. Many of such have gained significant traction in recent years. Better p2p networking technologies are necessary. As the Ethereum network becomes more scalable, more efficient, and layer 2 solutions become more functional, Golem is set to be positioned primarily as a platform for services, allowing users to run both small (e.g. a note-taking app) and large (e.g. a streaming service) applications in a decentralized manner.


## How Golem works?

Golem is a p2p network, ie. there is no central server and users are equally privileged. People who want to compute tasks and people who have computer power to rent broadcast their offers in the network. Golem's transaction system matches providers and requestors, taking into account prices, reputations and their machines' performance. Tasks, ie. files needed for computation are sent to the provider's machine. After the computation is completed, the provider's app sends back the results to the requestor's app. If the result passes the verification process, the provider is paid for their work. If someone sends bad results, doesn't pay, or performs in any unacceptable way, their reputation will be impacted, therefore their chances of being chosen for tasks will be reduced. If the user wants an additional layer of security, there is an additional verification solution - [Concent Service](Products/Clay-Beta/Usage?id=concent-service) available.

Check our [blog post](https://blog.golemproject.net/golem-architecture/) to learn more.
