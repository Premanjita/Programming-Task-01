import java.time.LocalDate;
import java.time.Period;
public class EmployeeMain {
    private String name;
    private double salary;
    private LocalDate hireDate;
    public EmployeeMain(String name, double salary, LocalDate hireDate) {
        this.name = name;
        this.salary = salary;
        this.hireDate = hireDate;
    }
    public int getYearsOfService() {
        return Period.between(hireDate, LocalDate.now()).getYears();
    }
    public void printEmployeeDetails() {
        System.out.println("Name: " + name);
        System.out.println("Salary: " + salary);
        System.out.println("HireDate: " + hireDate);
        System.out.println("Years of Service: " + getYearsOfService());
        System.out.println();
    }
    public static void main(String[] args) {
        EmployeeMain employee1 = new EmployeeMain("Roberta Petrus", 50000.0, LocalDate.parse("2021-04-01"));
        EmployeeMain employee2 = new EmployeeMain("Loyd Blair", 70000.0, LocalDate.parse("2015-04-01"));
        EmployeeMain employee3 = new EmployeeMain("Magdalena Artemon", 50000.0, LocalDate.parse("2011-01-15"));
        employee1.printEmployeeDetails();
        employee2.printEmployeeDetails();
        employee3.printEmployeeDetails();
    }
}
