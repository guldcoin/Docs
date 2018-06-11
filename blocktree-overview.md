# Guld and the Blocktree

The Guld ecosystem is constructed around the concept of a _blocktree_. To quote the Guld whitepaper, a blocktree is "[a] polytree with signed, typed, symmetrical nodes [that] can be used to represent, record, compare, and perform operations on individual and group perspectives on any topic describable in a digitized record." In other words, it's a tree structure to hold all manner of data.

This is a _consensus-based_ system. That means that, at some level (really, at various levels), users/participants in the system need to come to agreement on what is _true_ within the system.

So how does this relate to the idea of _digital identity management_? At a practical level, it means that you are the sole arbiter of truth for everything contained in your part of the blocktree. For a group, truth is determined by consensus of equity-holders in the group.

The Guld ledger is designed for identity management, rather than privacy; thus, all usernames and transactions are public records.

.

## Blocktree vs Blockchain

For those familiar with the _blockchain_ concept, the blocktree serves a similar purpose in some regards, but goes much further.

First off, what's the same?

**Immutability**  Both are immutable, and each change builds off the previous change over linear time.

**Public records** Both are public records. Not all parts of the Guld _blocktree_ are public, but the _ledger_ is public.

Now, how do they differ?

**Branching structure** A blockchain is _linear_, whereas a blocktree is, in data-structure terms, a tree. The tree has a root, and it has an arbitrary number of branches (folders) and leaves (data items, i.e., files). A given branch can have an arbitrary number of sub-branches, and so on, _ad infinitum_.

As an (very-simplified) example, the files on a computer's hard drive are organized in a tree structure. The root of the structure is usually `C:\` in Windows, `Macintosh HD` on a Mac, and `/` on Unix and Linux. From that starting point, your own home directory might be `C:\Users\allison`, `Macintosh HD/Users/allison`, or `/home/allison`, respectively.
.

## Structure of the Blocktree

.

## Git and the Blocktree

"We definitely need to add the Sub-Module explanation and how dependencies work to create a decentralized internet with version control.

After the call closed, Ira explained to us how dependencies at specific snapshots of commits work to create a local auditable version of that collaborator's perspective."

"The Git mechanics will imply social contracts and organization."

Node operators (curently, Guld officers and executives) need to audit transactions, and make sure their node is up to date so the network can operate correctly.

Observers, witnesses, and validators. In a legal sense, we want to create a platform of data distribution authority that in court can be declared to be "fully witnessed". From the main repo: one snapshot in time (one commit), and that's how you localize the context of a node.

A double-spend is considered malicious activity.

.

### Submodules: Guld's super-power

This is how we identify the state of the world at a specific snapshot. We can acknowledge other repositories at a specific commit, validated and vouching for the information and data within up until that point.

"I acknowledge that I have seen Fernando's state of affairs as of this point." Signing as witness, not vouching for the content. The ledger submodule is a repo in its own right. It is a copy of the ledger at a specific point in time that you acknowledge that you have revised — making any changes to it may be financially and/or legally binding.

Mech of signing as witness is same as that for signee/debtor. Need to differentiate the types of commits to make sure everyone/everything knows what transactions are happening, what a particular transaction was.

"In the end, it's a network of evidence, an electronic paper trail."

.

## Interacting with the Blocktree

Signing the commit that contains a transaction is the method by which you sign the transaction.

Transactions must be signed by the account being _debited_.

.

## Manipulating the Blocktree

Filesystem operations

Exploring: search for commits, search through nodes, search through included software (which is committed in Git) and frameworks and dependencies. "Git was built on all this, and it's all included in the Merkel tree."

Talk about object permanence of the blocktree.

Serving files vs serving commits is an advantage over blockchain: in blockchain, you have to download the full block file. with the tree, you can choose to be witness tot the pertinent information to you; the distributed nature of the network is not dependent on storage limitations. You don't need to keep a full copy of the entire tree, which lowers the resource entry barrier.

.

## Operating a Guld Node

To operate a guld node, need to set up either git cmdline or guldFS.

**Caution!** guldFS automates a lot of things, including signing and committing. There are a lot of details here that need to be worked out, and a lot of things a node operator would need to take into account before opting for guldFS.

.

## Coding for the Blocktree

.

### Guld Libraries

Links to specifically chosen and well documented libraries. :)

.

### Guld Applications

Links to: guld-chrome wallet, gg-chrome.

.

### Available Sample Code

Links to specifically chosen and well documented code.

Maybe it's best to point to the applications? If so, then we'll want to point out particular sections as examples — and make sure that all the code is very thoroughly _and accurately_ documented.

.

### Getting Help

.
