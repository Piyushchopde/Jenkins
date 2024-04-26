Referance : https://medium.com/@harshBlogs/jenkins-interview-questions-99e2c7f1c005
- CI : Developer merge change sevarl times in a day called as continus integration 
- Continous deployment : Software is deployed to a production env automatically when ever chnages is made in codebase 
- Continous delivary : Software is build tested and packed so that it can be deployed to the production env 

1) Explain different stages in CI-CD setup ?
   - source code management
   - Build
   - test
   - deploy release
2)  What is Jenkins Pipeline?
A Jenkins pipeline is a set of instructions that define the steps involved in building, testing, and deploying software. Jenkins pipeline is written in a Groovy DSL, which makes it easy to read and understand

3) What is an agent, stage, and step in a Jenkins pipeline?
  -  Agent: An agent is a machine that executes the pipeline steps. Agents can be physical machines, virtual machines, or cloud-based machines.
  -  Stage: A stage is a logical grouping of steps that are executed together. Stages are typically used to group steps related to a specific task, such as building, testing, or deploying software.
  -  Step: A step is a single unit of work that is executed by the agent. Steps can be used to run commands, scripts, or plugins.
4) What are the different types of Jenkins agents?
  - Built-in agents & Remote agents
5) Where do you find errors in Jenkins?
  - We can find errors in the console output, in the build log, and in the Jenkins dashboard

6) How will you handle secrets in Jenkins?
        There are many ways:
         - Using Jenkins Credentials Plugin.
        - Using a third-party plugin like Vault
7) How can you secure Jenkins and manage user permissions?
      - Use strong passwords.
      - Enable two-factor authentication.
      - Use a firewall.
      - Update the Jenkins software timely.
      - Use a security plugin.
8) 
