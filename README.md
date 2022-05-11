# Streamlabs C++ Project

Hi there! Thank you for your interest in joining the C++ team working on the Streamlabs Desktop streaming application. Thank you so much for taking the time to read through and complete this project.

At Streamlabs we are committed to building a talented, empathic, and passionate team, which is made possible by your investment in this process. We are deeply grateful for your time, passion, and interest.

# The project

You will be building a C++ program and an external shared library that interacts with each other. The goal is to create customers that will be buying products from a store.

# Description:

 - The library should expose a store containing different products (microphones, webcams, keyboard, etc…)
 - Each product should be under a specific product family and have specific information such as a retail price, name, id, number of sales, etc ..
 - The C++ program should be able to make calls to the library and be viewed as customers. Two customers should be spawned and making simultaneous calls to the store (i.e the library) and buy products
 - The state of the store should be managed from the library itself and loaded/saved from the assets/store.json file
 - A sale should result in the creation of a receipt saved locally on the disk

# Please consider the following requirements:

 - The preferred operating system should be Windows 10/11
 - CMAKE should be used to configure the projects
 - GIT should be used along with github
 - 2 git repositories should be used (1 for each entity). The C++ program should integrate the C++ library as a git submodule
 - The runtime should be explicitly linked dynamically
 - This assignment should use the C++ 17 standard
 - No extra dependencies should be used other than the standard, the native OS APIs and https://github.com/nlohmann/json to parse JSON

# High level API that the library should expose:

 - Fetch the list of all product families
 - Fetch all products in the store for a given product family
 - Fetch the information of a specific product given its ID
 - Purchase a product

# Documentation & Thought process

Please include a README.md file that includes the following information:

 - Instructions on how to run your application
 - Your brief answers to the following questions:
   - How long did it take you to complete this assignment?
   - What about this assignment did you find unclear?
   - Do you feel like this assignment has an appropriate level of difficulty?
   - Briefly explain the technical decisions you made in this project, i.e. architecture, code-splitting, librairies, or other decisions and tradeoffs.

# Questions

Please email us if you have any questions along the way. We will try our best to help guide you through any confusion. Feel free to make assumptions and document them as you go as well.

# Submissions

Please submit your completed assignment via email to the recruiter who sent it to you. You can submit your assignment by pushing it to a Github repository and include a link to the repository.

We want to thank you again for your time and for your interest in joining the engineering team at Streamlabs!


   


