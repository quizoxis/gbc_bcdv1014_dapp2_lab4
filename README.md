## Lab 4:
### QUESTION 1

1. What problem are you trying to solve? (2 marks)
2. How blockchain will be able to solve this problem? (2 marks)
3. Enlist all user stories of your DAPP. (6 marks)

#### Sample Answer:

DAPP : Marketplace for survey creators
1. I need to conduct a survey to collect information, and I always hit the problem that people would like to get rewarded for the time they spent filling that survey. It would be good if you can compensate them.

2. Blockchain will make sure authenticity of the participants.

3. Follows

3.1 DAPP should allow creator to create the survey

3.2 DAPP should notify the creator when survey is created with contract address

3.3 DAPP should be able to display all the available surveys

3.4 DAPP should allow the participant to start filling the available surveys

3.5 DAPP should ask the participant for the account address at the end of survey

3.6 DAPP should be allow creator of the survey to end.

3.7 DAPP should be able to notify survey creator and participant winner when requested by survey creator.

3.8 DAPP should be able to deposit reward to the winner participant.

----

## Answers:

1. What problem are you trying to solve? (2 marks)
To improve an existing enterprise authentication system by providing better security and reduce fraud.

 2. How blockchain will be able to solve this problem? (2 marks)
In authentication systems a central repository is used to store all information in order to authenticate the end-user or device. Two-factor systems provide a layer of security but stil relies on this central repository to maintain secret user data. This central repository is the single point of failure as well a any cyber attacks, information stored can tampered or corrupted by malious actors.

Blockchain would provide a distributed datastore or for its hashes that are used to authenticate users. It can also provide inherent immutability of data.

 3. Enlist all user stories of your DAPP. (6 marks)

- User Login Request
User goes through initial Single Factor Authentication which is based on knowledge i.e. user knows his/her username and password. User enters user/password and starts the login process. At the backend this starts the two-factor authentication process which utilizes blockchain to create an one-time password and and sends it back to the user.

- User Registration of an two-factor authentication device.
User logs on their account, and registers for a two-factor authentication service.

- Password/Token recovery
