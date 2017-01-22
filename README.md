# trademachines-it-principles

## Strategic Goals

### Reduce Time To Market
We want to close our feedback loops as soon as possible. Therefore we deliver value to our users rather sooner than later.

### Assure Scalability
Our business grows fast, so we make sure that our infrastructure never becomes the bottleneck.

### Practice Independent (yet Guided Approach) - Talented People
We know why we do things, we decide how to approach them and deliberately practice our skills.

### Take/Make Data Driven Decisions
We base our decisions on data rather than beliefs.

### Measure Cost Efficiency
Find the correct balance between cost and value.

### Care About Our Customers
Our success depends on our clients' happiness. We feel responsible for providing quality outcome, even though we don't have direct contact with customer.


## Architectural Principles

### AWS First


### Immutable Architecture
To avoid snowflakes, do not change your services replace them entirely by a new version. Optimize for rebuilding not for repairing

### Decoupled Architecture
If a service is not available, it's impact on other services should be minimum (use queue systems and async call)

### Avoid Complexity

### Monitor The Business

### Focus On Our Business

### Reactive Manifesto
Developing systems according to Reactive Manifesto (http://www.reactivemanifesto.org/) allows us to create flexible, loosely-coupled and scalable applications.
Reactive Programming combined with Reactive Systems Design is a main tools for dealing with technical problems on backend which occurs when data and load is constantly growing and high availability is required.


## Design And Delivery

### Make Local Decision
Then promote them globally. We don't want to put more constraint on our teams than necessary.

### Measure All Things


### You Build It, You Run It

### API First

### Automate Everything
We keep reptitive work to a minimum and build automation into our tools whenever and wherever its feasible.

### Start With Plan A
We are bold and start with something that works right now. From there we inspect and adapt to our needs.

###  Challenge The Product Owner
We ask questions, because we don't want to follow blindly but find a balance between user value and technical feasibility.
