The Sia Foundation, Inc. is a registered 501(c)(3) non-profit dedicated to revolutionizing data storage through decentralization. 

We believe that the success of Sia relies on a positive feedback loop involving:
- **Developers** who improve the Sia protocol and create products, tools, and services that support its use.
- **Research** that enhances the ability to use Sia and the Sia network for a broader range of data storage.
- **Adoption** of Sia as a performant and scalable storage platform
- **Users** who are attracted by Sia's utility and the services entrepreneurs build on the Sia network.

Our objectives are to:
- **Support the Sia ecosystem** - We aim to provide resources and remove obstacles that discourage developers, entrepreneurs, and others from building, adopting, or supporting Sia.
- **Maintain and Build the Sia network** - We aim to create a user-friendly, fast, scalable decentralized storage network through cutting-edge research on peer-to-peer networks, blockchains, and storage protocols.
- **Educate Users** - We create content, organize events, and host workshops. 

## Our GitHub
Our GitHub repos contain the code that powers the Sia network, SDKs that make it easier to interact with it, and open-source extensions we have built on top of it.

The Sia repos are organized by their role in the ecosystem

### SiaFoundation/mux 
A privacy-focused e2e encrypted connection multiplexer. `mux` is the default transport for renter-host protocols 3 and 4.

### SiaFoundation/core 
Provides low-level core types, encoding, transport implementations, and consensus validation code in Go. It contains the primary implementation of Sia's consensus validation.

### SiaFoundation/coreutils 
Builds on `core` by providing component implementations such as the p2p syncer, chain manager, and single-address wallet.

### SiaFoundation/hostd
The primary storage provider software on the Sia network. Enables users to sell their storage space to consumers.

### SiaFoundation/renterd
The primary storage consumption software on the Sia network. Enables users to rent storage from providers. It is designed to be highly customizable, performant, and scalable to fit the needs of the diverse community utilizing the Sia network.

## Contributing
As an open-source project, we value all contributions highly. If you're looking for ways to contribute, look for the good-first-issue tag on our repos. 
