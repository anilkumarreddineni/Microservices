To initialize the repository for the first time
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/anilkumarreddineni/Microservices.git
git push -u origin master


As the repository is already available all we need to do is to check out the repository
git clone https://github.com/anilkumarreddineni/Microservices.git

Actual Kaushikgithubrepository:
https://github.com/koushikkothagal/spring-boot-microservices-workshop.git

Key points:
point1:for the unmarshalling from xml to javaand marshalling to xml the class must have an empty constructor.
microservices looks like SOA but soa is just used to create the utilities than can be used by anyone where as microservices have a pure business.
versioning in rest can be managed with the new versions.
Spring boot provides an asynchronous way of programming through the Reactive.
@Bean is an annotation that can be used on a method which acts as the producer and the executed for only once,autowired is a consumer.
@qualifier is used to name the bean.
Rest template has the low level code to call a rest call and will give the unmarsalled object.
As rest template is going to get deprecated and the alternative class is the web client which is located in the Reactive web of spring.