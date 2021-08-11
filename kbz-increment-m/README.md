# Increment Model

The Increment Model is a descending, ordered by importance list of incremental units of work called cards.
Each card represents a Value Proposition proposed by the "client" and new cards maybe added at any time. 
A card must pass through a number of gates from which it acquires a state.

# Increment Gates

Gates are an ascending, ordered, list of states that a card in the increment model can acquire.

Each gate has a set of conditions that must be met for a card to acquire the state defined by the gate.  Until all
conditions are met the state may not be changed.  Additionally, all gates must acquire in order.  Higher numbered gates 
cannot acquire before lower numbered gates.

* Every card in the list is labelled with a state.  
* The initial state is always "open".
* There is a middle state called "ready".
* The final state is always "closed".
* Changing the state of a gate without all conditions acquiring is a Journalable action.

# Rational Outcomes.

Cards must have rational outcomes.  These can be one or more Rational Outcome Models which are assigned to a gate or 
ad-hoc outcomes may also be used.

# Settings

#### Cadence

Value: 0
 
Cadence does not define how fast you run or when you change the state of the process.  It defines when you measure your
progress.
 
#### Speed Limit
 
Value: 1
  
How many cards in play simultaneously.


#### deadlines  (READONLY)

Required Value: not-allowed

# TEAM NORMS

#### BACKPORTING

Back porting is a strategy of Kanban-Zai that allows cards to be split or combined rationally to manage scope creep, 
unknown unknowns and early thinking.  This allows justifiable explanations for the delivery runway length.

Unfinished work on a card in a sprint should be split out to one or more cards and those cards prioritized.

#### SLACK

What is slack? In common usage it probably has a negative connotation, as in “he has been slacking off”. But in 
planning for successful sprints that yield consistent, high-quality results, it is essential.

#### PROMOTE

Team members must continuously attempt to promote cards to their next state by trying to make gate conditions acqurie.

### DEMOTE

Team members must continuously attempt to demote cards that fail to keep conditions acquired.

### METHOD

The following process must be run at cadence, completely with all steps considered.  In this context "considered" means 
a step must be attempted, whether it fails to acquire or not.

The team MUST:-

1. Consider the top card in the Increment Model.
3. Backport unfinished work where sensible.
2. Promote or demote and label the card based on the Gate it acquires to.
4. Completed cards must be removed from the list.
5. Repeat at cadence until there are no more cards.
