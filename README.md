## Hi there, I' am joburgos alias "Ángel" 👋
<h3>I'm webdesigner since 2010, now at 42 Campus to improve my skills!</h3>
#include <stdbool.h>

#include <stdbool.h>

struct about_me {
    char *name;
    char *pronouns[2];
    int age;
    bool student;
    bool hired;
    char *contact;
    char *website_url;
};

struct student {
    bool is_student;
    char *status[3];
    char *campus_42;
    char *login_42;
};

int main(void) {
    struct about_me joburgos = {
        .name = "José Ángel Burgos Mellado",
        .pronouns = {"he", "him"},
        .age = 47,
        .student = true,
        .hired = true,
        .contact = "disenosuweb@gmail.com",
        .website_url = "https://www.abcreationes.es"
    };

    struct student my_studies = {
        .is_student = true,
        .status = {"42 Student", "Freelance", "Abcreations"},
        .campus_42 = "Málaga",
        .login_42 = "joburgos"
    };

    return 0;
}


<h3>More about me</h3>
<p>Since 2010 I have been a freelance professional web designer. Since then I have carried out more than 300 web projects for all types of clients. In addition to being specialized in natural web positioning with SEO, SEM and social media management, my passion is graphic design, brand and product design, web design in general has marked my path throughout these years and now as a student from campus 42 in Malaga, I hope to be able to learn to develop more and better with new tools and knowledge that will help me improve every day.</p>

<a href="https://git.io/streak-stats"><img src="https://streak-stats.demolab.com?user=joburgos77&theme=dark&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub Streak" /></a>
