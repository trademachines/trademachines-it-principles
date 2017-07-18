# trademachines-it-principles

## Strategic Goals

### Reduce Time To Market
[We want to close our feedback loops as soon as possible. Therefore we deliver value to our users rather sooner than later.]
-- needs rephrasing

### Scale for Next Step
Our business keeps growing, so we make sure that our infrastructure is always one step ahead of sales/business.

### Make Data Driven Decisions
We base our decisions on data rather than beliefs.

### Aim for Cost Efficiency
Find the correct balance between cost and value.

### Care About Our Customers
We feel responsible for our clients' happiness.

### Constantly learning
We don't know everything. That's why constantly learning is important to us.


## Architectural

### AWS First
We prefer AWS Services over self-hosted over self-built solutions to keep us focused on our domain.

### Immutable Infrastructure
To avoid snowflakes, do not change your services replace them. Optimize for rebuilding not for repairing.

### Decoupled - ?? 
[Note: Not all of us have the common understanding about the term 'Decouple' - though a general notion about it is understood, a discussion was raised concerning some specific case/scenario. At least it is agreed that a failure in a service should not lead to cascading failures in other services.]
If a service is not available, it's impact on other services should be minimum.

### Avoid Complexity
Software development is hard enough. Thats why we wanna do things simple.

### Monitor The Business
Business decisions need data to back them up, so we monitor.

### Be Reactive
We develop systems according to the Reactive Manifesto. That makes us more flexible and scalable.


## Design And Delivery

### Make Local Decision
Then promote them globally. We don't want to put more constraint on our teams than necessary.

### Measure All Things
Decoupled architectures are hard to understand. By measuring all of that we try understand and anticipate.

### You Build It. You Run It.
Its hard to throw things over the fence when there is no one at the other side. Therefore we feel responsible from the beginning to the end.

### API First
We design our APIs and don't improvise them.

### Automate Everything
We keep reptitive work to a minimum and build automation into our tools whenever and wherever its feasible.

### Start With Plan A
We are bold and start with something that works right now. From there we inspect and adapt to our needs.

###  Challenge The Product Owner
We ask questions, because we don't want to follow blindly but find a balance between user value and technical feasibility.
