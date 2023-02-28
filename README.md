# Witnessable Apps

## What is it?

A witnessable app is a type of application that is fully transparent to its
users. Such an application is not just open source, but its execution and the
data it processes are also witnessable. Such complete transparency gives its
users the ability to verify an application's correct and proper execution.

## Why do I want to use a witnessable app?

Using a witnessable app allows the user to inspect every part of an application
and its execution. They can do their own research and conclude for themselves if
an application works correctly and behaves in the anticipated way.

Essentially, a user can check whether an application is truly safe to use. They
do not have to **trust** your word but can see for themselves.

## Should every application be witnessable?

No.

The level of transparency a witnessable app demands is not needed in cases where
users do not have any 'meaningful' interactions with an application. If users
visit a blog or a company's website, they most likely just want to read some
information and do not care about anything else.

On the opposite side, applications that actually matter to users and they
'seriously' interact with should be witnessable. Users want to be sure that
their inputs have the desired effects.

If Alice encrypts a file, she wants to be sure that it is properly encrypted and
that the clear text information is not leaked somewhere. Likewise, if Alice
sends some money to Bob, they both want to be certain that the transfer works as
expected and is not manipulated or diverted.

Consequently, it depends on the type of application and the users' attitude
towards the app.

## Is verifying an application even possible for the average user?

Verifying each line of code, the deployments, and the data of an application is
a huge task for anyone. Verifying specific parts that are of interest for a
given action is much more doable, at least for your average software developer.

Your average Joe is probably not able to do that either. However, we believe
that the process of verifying and reviewing applications is a community effort.
In general, it is interest of both, users and software developers, to create
safe and correct applications.

The [decentralized software repository](http://drepo.eth)
([alternative link](https://drepo.dev)) proposes public verification and review
networks. They steer and manage community resources to important projects that
are in need of verification. The findings are subsequently published. Anyone can
see them and draw their own conclusions.

The management of these processes is automated and reviews are conducted
repeatedly to account for the advancements in technology and to reduce the
factor of human error as system reviews are heavily relying on human labor for
the foreseeable future. Community oversight helps to keep all participants
honest.

## My application was audited by X and is certified as Y compliant, also we are regulated by Z. Is that not enough?

Audits and certifications are typically point-in-time snapshots. Your
application might have changed drastically since then.

Furthermore, such audits or regulations have very little meaning for your users.
They do not know what a certification includes or what the regulation dictates.
Also, you expect your users to trust the word of some 'reputable' auditing firm
or institution they probably have never heard of.

## How do I make the execution of my application witnessable?

If your application runs solely on a users machine, they can run and debug it,
just like you would as a developer.

However, if your application runs on some server the execution is invisible to
the user. They cannot verify that the results were computed correctly or how
they were computed. Users must be able to run the code themselves using all
needed input data and application state.

This concept of public computing is very different from current trends where big
tech and other companies run applications in the cloud behind closed doors.

Web3 dApps that run on public, permissionless smart contract blockchains are a
popular example for public computing. The code and the data are stored on the
blockchain for everyone to see. The computations are processed by a multitude of
participants in the network and verified through a consensus mechanism. Users
can run the application locally at any time to verify the correct processing
themselves.

## Isn't it dangerous to have the internal data of an application visible to users?

Storing your users personal data publicly is of course not a good idea. The
concept of witnessable apps requires a rethinking of what data to store and how
to store it. One must keep in that even storing the data encrypted is not
advisable as every encryption will eventually be cracked.

Thus, a witnessable app should store as little data as possible and embrace
anonymity and a user's control over their own data.

For example, instead of storing a user's data in the cloud an application could
encourage a user to bring their own data from a user defined storage location,
_Bring Your Own Data_. This location could be self-hosted or in a cloud service
the user chose. The application could access the part of the storage it is
allowed to (and able to), process the data, and return the result to the user's
storage.

## But my application cannot be open source?

That is your prerogative. But your application does not have to be open source
in its entirety. Important parts could be designed in a witnessable way, while
others can remain closed source and hosted on your company's servers.

Security aware users might opt out to use a service if they fear that it might
not work in their interest, or they would anticipate.
