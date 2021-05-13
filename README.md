│   build.gradle
│
└───src:
    ├───main:
    │   ├───java:
    │   │   └───com:
    │   │           └───forum:
    │   │               │   ForumApplication.java
    │   │               │
    │   │               ├───configuration:
    │   │               │       AdditionalLoginConfiguration.java
    │   │               │       SecurityConfiguration.java
    │   │               │
    │   │               ├───controllers:
    │   │               │       AnswersController.java
    │   │               │       IndexController.java
    │   │               │       LoginController.java
    │   │               │       ProfileController.java
    │   │               │       RegisterController.java
    │   │               │       TopicController.java
    │   │               │       TopicsController.java
    │   │               │
    │   │               ├───entities:
    │   │               │       Answer.java
    │   │               │       Topic.java
    │   │               │       User.java
    │   │               │
    │   │               └───repositories:
    │   │                       AnswerRepository.java
    │   │                       TopicRepository.java
    │   │                       UserRepository.java
    │   │
    │   └───resources:
    │       │   application.properties
    │       │
    │       └───templates:
    │           │   answers.html
    │           │   error.html
    │           │   index.html
    │           │   login.html
    │           │   profile.html
    │           │   register.html
    │           │   topic.html
    │           │   topics.html
    │           │
    │           └───layout:
    │                   offline.html
    │                   online.html
    │
    └───test:
        └───java:
            └───com:
                    └───forum:
                            ForumApplicationTests.java
```
