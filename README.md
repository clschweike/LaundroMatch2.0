# LaundroMatch2.0
Revamp of Intro to SWE team semester project - reservation system for hypothetical laundromat

Notes to self: 
- Created this GitHub project (**LaundroMatch2.0**), then folder in Fun-CS-Stuff folder (**LaundroMatchRevamp**), then opened that folder as an Eclipse project and created a Dynamic Web Project (**LaundroMatchReservations**)
- First debug: "Cookie not resolved to type" issue, changed Java version from 17 to 11 (select project --> Properties --> Java Build Path --> Libraries, also Project Facets from Java 17 to 11); also Project (on top ribbon) --> clean; also added servlet-api.jar for Tomcat (build path libraries again --> Add External JARs... --> servlet-api.jar, which is currently in apache-tomcat-9.0.58 --> lib), then clean and refresh again
- Second: in Confirmation.jsp file, error on first couple characters of file, saying that, according to dynamic web module facet (4.0), something was wrong with build path or something... selected option to save it as UTF-8 though, so now doesn't matter what pageEncoding says (UTF-8 or ISO-8859-1) - neither causes an error now
