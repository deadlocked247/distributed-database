Burak Aslan
Isaac Fernandez

Implements the Raft protocol for distributed key value store system with
quorum. Individual node status is tracked as as a state machine between the
possible states. 

Trial and error solved most problems, although one final hang up causes a test
to fail under different conditions randomly that we have no been able to diagnose.

During development, print debugging was used to attempt to verify correct
behavior, with care to make sure the source of each print statement was 
identifiable to deal with the possible confusion over multiple machines
committing similar actions simultaneously.


