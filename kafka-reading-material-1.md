<h1> 1. What is Kafka?</h1>
<b>Kafka Is Like REST but Asynchronous?</b>
 <p>You can build this type of request-response interaction with Kafka using two topics: one that transports the request and one that transports the response. People build systems like this, but in such cases the broker doesn’t contribute all that much. There is no requirement for broadcast. There is also no requirement for storage. So this leaves the question: would you be better off using a stateless protocol like HTTP?
 <br/> <br/>So Kafka is a mechanism for programs to exchange information, but its home ground is event-based communication, where events are business facts that have value to more than one service and are worth keeping around. </p>
