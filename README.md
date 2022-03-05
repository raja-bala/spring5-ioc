# spring5-ioc

# What are beans in spring?
- In Spring, the objects that form the backbone of your application and that are managed by the Spring IoC container are called beans
- A bean is an object that is instantiated, assembled, and managed by a Spring IoC container

# What is a Spring IOC container
The **org.springframework.context.ApplicationContext** interface represents the Spring IoC container and is responsible for instantiating, configuring, and assembling the beans.

# What are the two basic packages needed to Spring IOC container to work?
The two packages basis for the Spring Framework IoC container are
  1. org.springframework.beans
  2. org.springframework.context

# What is BeanFactory interface?
The bean factory provides an advanced configuration mechanism capable for managing any type of object. 

# What is ApplicationContext interface?
  - **ApplicationContext** is a sub-interface of **BeanFactory**  
  - **BeanFactory** provides the configuration framework and basic functionality, and the **ApplicationContext** adds more enterprise-specific functionality. 
  - (**ApplicationContext**) It adds the followings:
    - Easier integration with Spring’s AOP features
    - Message resource handling (for use in internationalization)
    - Event publication
    - Application-layer specific contexts such as the **WebApplicationContext** for use in web applications.

# What is Configuration metadata?
Instructions provided to the Spring IOC container, on what objects to instantiate, configure, and assemble

# What are the three ways Configuration metadata can be represented?
  - XML
  - Java annotations
  - Java code

# List some of the implementations available in spring for ApplicationContext interface?
  - ClassPathXmlApplicationContext
  - FileSystemXmlApplicationContext
  - 

  
