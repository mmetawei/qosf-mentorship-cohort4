# qosf-mentorship-cohort4
The implemented tasks for the mentorship program application. I've attempted two tasks: Task1 and Task2.
Task1:
The main idea is to mark down the qubits values combination corresponding to the winning number then amplify their probability using Grover Algorithm.
I made two versions of the solution: qosf_screenning_task1_index_output is the special case solution for the fixed sizee input of 4 numbers.
The generic solution: 
This implementation is for 3 qubits so the winning numbers are 010 and 101 so we have to add a phase on the no 1 qubit in the "010" case and qubit 0 and 2 in the "101" case.
We then use Grover Search to amplify the desired output.
We assume that there must be two numbers among the input verctor satisfying the alternating bits value condition.
