# qosf-mentorship-cohort4
The implemented tasks for the mentorship program application
The main idea is to mark down the qubit corresponding to the digit 1 in the winning number.
This implementation is for 3 qubits so the winning numbers are 010 and 101 so we have to add a phase on the no 1 qubit in the "010" case and qubit 0 and 2 in the "101" case.
We then use Grover Search to amplify the desired output.
We assume that there must be two numbers among the input verctor satisfying the alternating bits value condition.
