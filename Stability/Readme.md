One sure way to make a software component hard to change is to make lots of components dependent on it. A component with lots of incoming dependencies is very stable because it requires a great deal of effort to reconcile any changes with all dependent components.


![Stable component](stable_component.png)
In above image X is a very stable component. Three components depends on X, so it has three good reasons not to change.X is responsible to those 3 components.
Conversely X depends on nothing, so it has no external influence to make it change. X is independent
