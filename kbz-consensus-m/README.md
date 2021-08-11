#kbz-consensus-m

Kanban-Zai is an ethical consensus algorithm.


# SETTINGS


## quorum

Possible Values: any number value smaller than your team size, but greater than 1.  DEFAULT: 2

Determines if a vote can be held or not.  You must have at least a quorum to hold a vote.  

Except where it is specified that you must have a full consensus.


## harmony

Possible Values: positive | negative  DEFAULT: positive

A team reaching consensus can solve many  of the problems that arise but sometimes it is hard to reach consensus.  
The sole purpose of this setting is tie breaking.  It is a pre-determined agreement to gain consensus if there is a tie
in the voting.  If someone chooses to abstain, this becomes their vote.  

Note, this means that there is no way in Kanban-Zai to abstain. BUT harmony votes must be journaled as dissent.

## dissent

Required Value: censoring the dissenting opinion is not allowed (READONLY)

A dissenting opinion is an opinion that disagrees, with one part of the majority position.
 
    

# NORMS

## CONSENSUS

To move forward, on anything, a consensus must be achieved.  Effectively this means at least quorum of people.   If a 
quorum cannot be achieved by the presence of enough voting members a vote MUST not be taken. 

This is not to say action cannot be taken if a vote cannot be taken.  But a journal of that action must be recorded as
it is a deviation from consensus.

## INDIVIDUALISIM

A team is made up of individuals.  They all bring their own uniqueness to the team. Each person should be treated as an
individual.  In light of this everyone on the team must have a voice and a vote at the table. 
If they choose not to use their voice or vote then their vote should default to the harmony setting. 

Votes cannot not be proxied.

## DISSENT

In groups of humans, there are psychological implications to dissent and not all participants are equal, they may:

* be unequally affected by the decision, especially, disadvantaged
* be called upon to make unusual sacrifices or take unusual tasks on to implement the decision
* represent opinions or affected parties not actually present in the decision making process
* have more knowledge than the other participants, or so much less that they add noise to decisions

Kanban-Zai requires to have all dissenting opinion or negative outcome predictions, and the reasoning behind the dissent
recorded.

Dissent is always recorded.  If, for no other reason so that accuracy of predictions can be examined later so the group 
can learn

 


## VIGILANCE

Team members must maintain constant vigilance against the anathema.


# ANATHEMA

The Anathema are part of the core only and may not be added in any extension or module.  

Anathema represents the opposite ethos of Kanban-Zai.

## unanimity

"unanimity"  is not synonymous with a consensus and is considered to be a sign of a weak decision reached without
debate and does not provide objectivity.  But not in every case.  Its a tricky one.

 
## group think
Groupthink is a psychological phenomenon that occurs within a group of people in which the desire for harmony or 
conformity in the group results in an irrational or dysfunctional decision-making outcome. 

Cohesiveness, or the desire for cohesiveness, in a group may produce a tendency among its members to agree at all costs.
This causes the group to minimize conflict and reach a consensus decision without critical evaluation.

Groupthink requires individuals to avoid raising controversial issues or alternative solutions, and there is loss of
 individual creativity, uniqueness and independent thinking.
 
 Groupthink also prohibits an organization from moving forward and innovating if no one ever speaks up and says 
 something could be done differently.

## Abilene paradox
In the Abilene paradox, a group of people collectively decide on a course of action that is counter to the preferences 
of many or all of the individuals in the group. It involves a common breakdown of group communication in which
 each member mistakenly believes that their own preferences are counter to the group's and, therefore, does not raise 
 objections. A common phrase relating to the Abilene paradox is a desire to not "rock the boat". This differs from 
 groupthink in that the Abilene paradox is characterized by an inability to manage agreement.

## Groupshift
Groupshift is a phenomenon in which the initial positions of individual members of a group are exaggerated toward a 
more extreme position.[a] When people are in groups, they make decisions about risk differently from when they are
 alone. The decision made tends to be even more risk-averse if the group members' opinions are risk-averse on average, 
 and even more risk-seeking if the group members' opinions are risk seeking on average.[2] In a group, people are 
 likely to exhibit a slight preference towards riskier decisions, as the shared risk makes the individual risk less.

# argumentum ad populum
An argumentum ad populum is a fallacious argument that concludes that a proposition must be true because many or 
most people believe it, often concisely encapsulated as: "If many believe so, it is so".

## eristic
Eristic aims to resolve a situation of antagonism through verbal fighting.

## silos

Not all silos are a bad thing but generally they should be regarded as suboptimal.

More specifically there are some types of silo that must be gurard against.

Impostor Syndrome
    -Perfectionist
    -The Superwoman/man
    -The Natural Genius
    -The Rugged Individualist
    -The Expert


(a) Sybil: forging identities or creating multiple false accounts by one player. - silo
(b) Lag: cooperating for some time to gain a high trust value and then cheat. - silo
(c) Re-Entry: corrupted players return to the scheme using new identities. - silo
(d) Imbalance: cooperating on cheap transactions; defecting on expensive ones. - silo
(e) Multi-Tactic: any combination of attacks mentioned above. - silo

## cliques ( are a group silo )

Typically, people in a clique, or more formally a cabal, will not have a completely open group and can, therefore, "ban" 
members if they do something considered unacceptable, such as talking to someone disliked.
 
Cliques tend to isolate themselves, usually to promote their private views or interests usually unbeknownst to those 
who are outside their group and view themselves as superior to others.

The difference between a coven and a clique is that a coven is INCLUSIVE and anyone can join a clique is EXCLUSIVE
only some certain people are accepted in.


(f) Ballot-Stuffing: fake transactions among colluders to gain a high trust value. - clique
(g) Bad-Mouthing: submitting negative reviews to non-coalition members.- clique
