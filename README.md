git checkout -b studentid101414445
touch studentid101414445_gb.txt
echo "The George Brown College of Applied Arts and Technology is a public, fully accredited college of applied arts and technology with three campuses in downtown Toronto (Ontario, Canada)." > studentid1_gb.txt
git add studentid101414445_gb.txt
git commit -m "Added George Brown College information"

touch studentid101414445_devops.txt
echo "COMP 2156 DevOps course is a course which will help me to learn what a DevOps Engineer has to bring to the workplace when i enter the professional world.This course will help me effectively carry out the roles of a System or Network engineer with DevOps processes by
utilizing the industry-standard tools and techniques and strategies such as CI/CD, as well as software development lifecycle and containerization for deployment." > studentid101414445_devops.txt
git add studentid101414445_devops.txt
git commit -m "Added COMP 2156 DevOps course information"

touch studentid1_sdlc.txt
echo "Efficiency and Collaboration:

DevOps emphasizes collaboration between development and operations teams. This collaboration streamlines communication and enhances efficiency throughout the entire development process.
Automation and Continuous Integration/Continuous Deployment (CI/CD):

DevOps promotes the automation of manual processes, reducing the risk of errors and increasing the speed of development. CI/CD pipelines automate building, testing, and deployment, ensuring a more reliable and rapid release cycle.
Faster Time to Market:

By automating repetitive tasks and implementing CI/CD practices, DevOps accelerates the development and release cycles. This results in faster delivery of software products to the market, providing a competitive edge.
Improved Quality and Reliability:

Continuous testing and integration in DevOps lead to higher-quality software. Automated testing helps identify and fix bugs early in the development process, ensuring more reliable and stable software releases.
Scalability and Flexibility:

DevOps practices enable better scalability of infrastructure and applications. With automation and cloud technologies, teams can easily scale resources up or down based on demand, ensuring optimal performance." > studentid101414445_sdlc.txt
git add studentid101414445_sdlc.txt
git commit -m "Added SDLI information"
git push origin master
