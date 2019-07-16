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



A test process consists of the following main groups of activities:
 Test planning
 Test monitoring and control
 Test analysis
 Test design
 Test implementation
 Test execution
 Test completion


Test implementation
During test implementation, the testware necessary for test execution is created and/or completed,
including sequencing the test cases into test procedures. So, test design answers the question “how to
test?” while test implementation answers the question “do we now have everything in place to run the
tests?”
Test implementation includes the following major activities:
 Developing and prioritizing test procedures, and, potentially, creating automated test scripts
 Creating test suites from the test procedures and (if any) automated test scripts
 Arranging the test suites within a test execution schedule in a way that results in efficient test
execution (see section 5.2.4)
 Building the test environment (including, potentially, test harnesses, service virtualization,
simulators, and other infrastructure items) and verifying that everything needed has been set up
correctly
 Preparing test data and ensuring it is properly loaded in the test environment
 Verifying and updating bi-directional traceability between the test basis, test conditions, test
cases, test procedures, and test suites (see section 1.4.4)
Test design and test implementation tasks are often combined.
In exploratory testing and other types of experience-based testing, test design and implementation may
occur, and may be documented, as part of test execution. Exploratory testing may be based on test
charters (produced as part of test analysis), and exploratory tests are executed immediately as they are
designed and implemented



Test completion
Test completion activities collect data from completed test activities to consolidate experience, testware,
and any other relevant information. Test completion activities occur at project milestones such as when a
software system is released, a test project is completed (or cancelled), an Agile project iteration is
finished (e.g., as part of a retrospective meeting), a test level is completed, or a maintenance release has
been completed.
Test completion includes the following major activities:
 Checking whether all defect reports are closed, entering change requests or product backlog
items for any defects that remain unresolved at the end of test execution
 Creating a test summary report to be communicated to stakeholders
 Finalizing and archiving the test environment, the test data, the test infrastructure, and other
testware for later reuse
 Handing over the testware to the maintenance teams, other project teams, and/or other
stakeholders who could benefit from its use
 Analyzing lessons learned from the completed test activities to determine changes needed for
future iterations, releases, and projects
 Using the information gathered to improve test process maturity 
