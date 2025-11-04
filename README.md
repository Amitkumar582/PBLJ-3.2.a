## Part A: Dependency Injection in Spring

### Description

- Demonstrates **Dependency Injection** using Spring annotations.  
- `Student` depends on `Course`.  
- Java-based configuration using `@Configuration` and `@Bean`.

### How to Run

1. Navigate to `PartA_SpringDI/src/main/java`.  
2. Compile all Java files:

```bash
javac -cp "path_to_spring_jars/*" com/example/di/*.java com/example/di/config/*.java com/example/di/model/*.java
````

3. Run the application:

```bash
java -cp ".:path_to_spring_jars/*" com.example.di.MainApp
```

**Expected Output:**

```
Student Name: John Doe
Enrolled in course: Artificial Intelligence
