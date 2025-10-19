# Hospital-Scheduler
The Hospital Scheduler project aims to model real-world hospital queue management using CPU scheduling algorithms from Operating Systems. The system treats each patient like a “process” with attributes such as arrival time, treatment duration, and priority (severity). These attributes are processed by scheduling algorithms like First Come First Serve (FCFS), Shortest Job First (SJF), and Priority Scheduling to determine the most efficient order of patient treatment.

The system has been designed with a C++ backend that performs the core scheduling logic, a Flask (Python) server to communicate with the frontend, and a web interface that allows users to input patient details, choose an algorithm, and visualize the result using charts and tables.

The main objective is to reduce waiting times and improve efficiency in patient handling by simulating real-time scheduling behavior. The project also serves as a learning bridge between Operating System process scheduling concepts and their practical healthcare applications.
