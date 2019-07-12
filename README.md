# foundation-level-testing

1 Fundamentals of Testing 175 minutes
Keywords
coverage, debugging, defect, error, failure, quality, quality assurance, root cause, test analysis, test basis,
test case, test completion, test condition, test control, test data, test design, test execution, test execution
schedule, test implementation, test monitoring, test object, test objective, test oracle, test planning, test
procedure, test suite, testing, testware, traceability, validation, verification 



Having testers involved in requirements reviews or user story refinement could detect defects in
these work products. The identification and removal of requirements defects reduces the risk of
incorrect or untestable functionality being developed.
 Having testers work closely with system designers while the system is being designed can
increase each party’s understanding of the design and how to test it. This increased
understanding can reduce the risk of fundamental design defects and enable tests to be identified
at an early stage.
 Having testers work closely with developers while the code is under development can increase
each party’s understanding of the code and how to test it. This increased understanding can
reduce the risk of defects within the code and the tests.
 Having testers verify and validate the software prior to release can detect failures that might
otherwise have been missed, and support the process of removing the defects that caused the
failures (i.e., debugging). This increases the likelihood that the software meets stakeholder needs
and satisfies requirements.

1.3 Seven Testing Principles
A number of testing principles have been suggested over the past 50 years and offer general guidelines
common for all testing.
1. Testing shows the presence of defects, not their absence
Testing can show that defects are present, but cannot prove that there are no defects. Testing reduces
the probability of undiscovered defects remaining in the software but, even if no defects are found, testing
is not a proof of correctness.
2. Exhaustive testing is impossible
Testing everything (all combinations of inputs and preconditions) is not feasible except for trivial cases.
Rather than attempting to test exhaustively, risk analysis, test techniques, and priorities should be used to
focus test efforts.
3. Early testing saves time and money
To find defects early, both static and dynamic test activities should be started as early as possible in the
software development lifecycle. Early testing is sometimes referred to as shift left. Testing early in the
software development lifecycle helps reduce or eliminate costly changes (see section 3.1).
4. Defects cluster together
A small number of modules usually contains most of the defects discovered during pre-release testing, or
is responsible for most of the operational failures. Predicted defect clusters, and the actual observed
defect clusters in test or operation, are an important input into a risk analysis used to focus the test effort

5. Beware of the pesticide paradox
If the same tests are repeated over and over again, eventually these tests no longer find any new defects.
To detect new defects, existing tests and test data may need changing, and new tests may need to be
written. (Tests are no longer effective at finding defects, just as pesticides are no longer effective at killing
insects after a while.) In some cases, such as automated regression testing, the pesticide paradox has a
beneficial outcome, which is the relatively low number of regression defects.
6. Testing is context dependent
Testing is done differently in different contexts. For example, safety-critical industrial control software is
tested differently from an e-commerce mobile app. As another example, testing in an Agile project is done
differently than testing in a sequential lifecycle project (see section 2.1).
7. Absence-of-errors is a fallacy
Some organizations expect that testers can run all possible tests and find all possible defects, but
principles 2 and 1, respectively, tell us that this is impossible. Further, it is a fallacy (i.e., a mistaken belief)
to expect that just finding and fixing a large number of defects will ensure the success of a system. For
example, thoroughly testing all specified requirements and fixing all defects found could still produce a
system that is difficult to use, that does not fulfill the users’ needs and expectations, or that is inferior
compared to other competing systems. 


Errors may occur for many reasons, such as:
 Time pressure
 Human fallibility
 Inexperienced or insufficiently skilled project participants
 Miscommunication between project participants, including miscommunication about requirements
and design
 Complexity of the code, design, architecture, the underlying problem to be solved, and/or the
technologies used
 Misunderstandings about intra-system and inter-system interfaces, especially when such intrasystem and inter-system interactions are large in number
 New, unfamiliar technologies
In addition to failures caused due to defects in the code, failures can also be caused by environmental
conditions. For example, radiation, electromagnetic fields, and pollution can cause defects in firmware or
influence the execution of software by changing hardware conditions.
