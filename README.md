# qosf-mentorship-cohort4
The implemented tasks for the mentorship program application. I've attempted two tasks: Task1 and Task2.
Task1:
The main idea is to mark down the qubits values combination corresponding to the winning number then amplify their probability using Grover Algorithm.
I made two versions of the solution: qosf_screenning_task1_index_output is the special case solution for the fixed sizee input of 4 numbers and variable bitstring size m.
The generic solution: qosf_screenning_task1_generic_v2.0.ipynb is the generic solution for any input list size n and any bitstring size m.

Task2:
The implementation generates 4 binary values then selects based on it one of the 4 allowed output quantum states. The estimated output is an approximation of the desired output for example for the state [0 1 0 1] the output will be [0.03  0.9  -0.07  0.7].
I tried out different ansatz designs for the training circuit and found slight improvment in the prediction accuracy, I tried circuit 15, 9, 2, and 4 from Sim's paper: https://onlinelibrary.wiley.com/doi/pdf/10.1002/qute.201900070
Due to time limit, I am delivering my solution in incomplete state. The last output value in the vector is not updated. 
Solution files : qosf_screenning_cohort4_task2, qosf_screenning_cohort4_task2_ansatz2
