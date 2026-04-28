# Performance Testing and Profiling


## Endpoint `/all-student`

**JMeter (GUI)**
![Test Plan 1 JMeter GUI](assets/images/test_plan_1_JMeter_GUI.png)

**JMeter (CLI)**
![Test Plan 1 JMeter CLI](assets/images/test_plan_1_JMeter_CLI.png)
- Before Optimizing: Average Response Time = 82812 ms
  ![Test Plan 1 JMeter CLI result](assets/images/test_plan_1_JMeter_CLI_result.png)
- After Optimizing: Average Response Time = 712 ms
  ![Test Plan 1 JMeter CLI result after](assets/images/test_plan_1_JMeter_CLI_result_after.png)
- Improvement: ~99.1% faster

**IntelliJ Profiler (Before Optimizing vs After Optimizing)**
![IntelliJ Profiler 1](assets/images/IntelliJ_Profiler_1.png)


## Endpoint `/all-student-name`

**JMeter (GUI)**
![Test Plan 2 JMeter GUI](assets/images/test_plan_2_JMeter_GUI.png)

**JMeter (CLI)**
![Test Plan 2 JMeter CLI](assets/images/test_plan_2_JMeter_CLI.png)
- Before Optimizing: Average Response Time = 2197 ms
  ![Test Plan 2 JMeter CLI result](assets/images/test_plan_2_JMeter_CLI_result.png)
- After Optimizing: Average Response Time = 32 ms
  ![Test Plan 2 JMeter CLI result after](assets/images/test_plan_2_JMeter_CLI_result_after.png)
- Improvement: ~98.5% faster

**IntelliJ Profiler (Before Optimizing vs After Optimizing)**
![IntelliJ Profiler 2](assets/images/IntelliJ_Profiler_2.png)


## Endpoint `/highest-gpa`

**JMeter (GUI)**
![Test Plan 3 JMeter GUI](assets/images/test_plan_3_JMeter_GUI.png)

**JMeter (CLI)**
![Test Plan 3 JMeter CLI](assets/images/test_plan_3_JMeter_CLI.png)
- Before Optimizing: Average Response Time = 139 ms
  ![Test Plan 3 JMeter CLI result](assets/images/test_plan_3_JMeter_CLI_result.png)
- After Optimizing: Average Response Time = 23 ms
  ![Test Plan 3 JMeter CLI result after](assets/images/test_plan_3_JMeter_CLI_result_after.png)
- Improvement: ~83.5% faster

**IntelliJ Profiler (Before Optimizing vs After Optimizing)**
![IntelliJ Profiler 3](assets/images/IntelliJ_Profiler_3.png)
