# Executable Architecture

_Context:_  Your team should have a design concept and reuse plan documented in your team confluence space. You need to flesh out this design concept to define, construct and test your system architecture as completely as possible with the constraints of the sprint.

_Your aim is to ensure that:_

1.  All of the high-level subsystems and components of your architecture are identified (high-level here requires judgement and justification). This includes:
    1.  External subsystems
    2.  Components you plan to re-use
    3.  Components you plan to develop
2.  All the interfaces between these components should be defined: which operations are supported, what data is transferred, which component controls the interaction.
3.  Your bitbucket repository should contain a tagged, runnable build which can exercise, in a manner similar to that required by the target system:
    1.  All re-use components
    2.  All external subsystems
    3.  Drivers/stubs, or limited capability versions, of all subsystems/components that you plan to develop
4.  Your repository should also include a suite of system and integration tests which exercise all the interfaces in a manner similar to that required by the target system, as well as
    1.  expected test results, and
    2.  actual test results from running the tests (build version used in running test should be clearly identified).
5.  Where your executable architecture does not support the full interface required of the target system, a (concise) justification should be provided in terms of risk, difficulty/complexity, and scope.