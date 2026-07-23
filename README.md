class CurrentSemester extends CCAC_DualEnrollment {
    
    // 🍁 Current Enrollment: Fall Semester
    String academicYear = "2026";
    String highSchoolGrade = "12th Grade Senior";
    
    String[] activeCourses = {
        "CIT-130: Advanced Java / Computer Science II",
        "CIT-145: Programming in C++"
    };

    void currentFocus() {
        // CIT-130 Objectives
        implementing("Data structures");
        designing("Advanced object-oriented systems");
        building("Abstract data types & custom algorithms");

        // CIT-145 Objectives
        learning("Systems programming & low-level design");
        managing("Memory allocation & C++ syntax");
    }
}

class AcademicHistory {
    // 🎓 College Coursework Completed (CCAC) — GPA: 4.0 / 4.0
    String[] completed = {
        "CIT-111: Intro to Programming: Java",
        "CIT-115: Information Technology Fundamentals",
        "CIT-120: Networking Concepts",
        "CIT-125: Web Design & Development"
    };
}

class DeveloperSkills {
    // 🛠️ Core Stack & Focus
    String[] languages = {"Java", "HTML5", "CSS3"};
    String[] tools     = {"NetBeans", "Git", "GitHub"};
    String[] concepts  = {"Networking", "Cloud Basics", "Tech Security", "OOP"};
    
    // 📁 Featured Projects
    String project1 = "Mixup - Creative Coding Platform (Responsive Flexbox layout)";
    String project2 = "CIT-111 Java Assignments (Console programs & interactive GUIs)";
}
