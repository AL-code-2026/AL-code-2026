public class DeveloperProfile {

    public static void main(String[] args) {
        
        // 🛠️ Profile Definition
        String role = "Dual Enrollment IT Student";
        String institution = "Community College of Allegheny County (CCAC)";
        String currentGrade = "12th Grade Senior (Fall 2026)";
        double gpa = 4.0;

        System.out.println("Hi there, I'm a " + role + " 👋");
        System.out.println("Status: Rising " + currentGrade + " completing advanced college courses.");
        System.out.println("Passions: Software Engineering | Networking Infrastructure | Frontend Web Dev");

        // 🎯 Current Focus & Next Steps
        String[] upcomingCourses = {
            "CIT-130: Advanced Java / Computer Science II (Data structures, OOP design, custom algorithms)",
            "CIT-145: Programming in C++ (Systems programming, memory management)"
        };
        
        String longTermGoal = "Systems analysis, advanced structures, and enterprise portfolio building.";

        // 🎓 College Coursework Completed (CCAC) — GPA: 4.0 / 4.0
        String[] completedCourses = {
            "CIT-111: Intro to Programming (Java OOP, logic, GUI troubleshooting)",
            "CIT-115: IT Fundamentals (Workstation setup, security risks, hardware)",
            "CIT-120: Networking Concepts (Device configuration, mobile infra, cloud virtualization)",
            "CIT-125: Web Design & Development (Flexbox/Grid, HTML5, responsive layout)"
        };

        // 🛠️ Stack & Core Skills
        String[] languages = {"Java", "HTML5", "CSS3"};
        String[] tools = {"NetBeans", "Git", "GitHub"};
        String[] concepts = {"Networking", "Cloud Basics", "Tech Security", "OOP"};

        // 📁 Featured Projects
        String project1 = "Mixup - Creative Coding Platform (Responsive Flexbox showcase layout)";
        String project2 = "CIT-111 Java Assignments (Console programs, math algorithms, custom GUI)";

        System.out.println("Building a strong foundation in CIS, one repository at a time. 🚀");
    }
}
