#kbz-codebase-m

Self documenting codebasee


#settings

### maintainability: 

Possible Values: triumvirate | none | url DEFAULT: time-to-market
   
A url points to a formal definition of what your team defines as a maintainable strategy.  This must be
on a per-team basis only.  A single Maintenance strategy may not be used across teams as the strategy will change 
over time.
   
### tdd

Possible Values: true | false DEFAULT: false
  
Test Driven Development is turned off by default as it has benefits and detriments.

### tech-debt

Possible Values: amortize | reduce | prevent DEFAULT: amortize

amortize:   record all technical-debt.  Reduce that debt when practical or when there is no choice.  Otherwise leave it 
            until you are bored and have nothing else to do.

reduce:     record all tech debt and schedule in to sprints.

prevent:    when technical debt occurs resolve it there and then.  This could make very long running cards. Such cards 
            must be backported per sprint.
