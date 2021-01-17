## Events in CI/CD
</br>
</br>

### Andrea Frittoli
#### IBM, Tekton

<br/>
FOSDEM | CI/CD Devroom | 07.02.2021

---

## The Single Tool

![](images/single_tool.svg) <!-- .element height="30%" width="30%" -->

notes: Organizations often find one single tool that satisfies all their needs of CI/CD... or not really

-----

<!-- .slide: data-transition="zoom-in fade-out" -->

![](images/single_platform.svg) <!-- .element height="80%" width="80%" -->

-----

<!-- .slide: data-transition="fade" -->
<!-- .slide: data-transition-speed="fast" -->

### The Single Protocol

![](images/single_protocol.svg) <!-- .element height="60%" width="60%" -->

notes: And these different platforms all speak the same language... or not really again. The data model is different, platforms can range from generic to very opinionated and so their dictionaries can be very different.

-----

### An Heterogeneous Landscape

* Different data models
* Varying scope
* From generic to specific

---

## Event based integration

* Decoupling
* Scalability
* Resiliency

notes: Discuss the benefits of event driven integration between the various platforms.

-----

It still requires point to point integrations
</br>
<span class="fragment fade-up">
...as we may get lost in translation

<br/>

<div id="left" class="fragment fade-up">

* Activity
* Pipeline
* Workflow

</div>

<div id="right" class="fragment fade-up">

* Build
* Task
* Step

</div>
</span>

notes: Platform X reacts to events from platform Y
Platform X understand terminology from platform Y

-----

### How can we solve this?

* Collaboration
* Standardization

notes: collaboration may help, standardization were possible

---

### Continuous Delivery Foundation
![](images/cdf_logo.svg) <!-- .element height="40%" width="40%" -->

(Since 2019)


notes: Enter CDF, a neutral home of CI/CD projects. A good place for collaboration.

-----

![](images/cdf.svg)

-----

## Interoperability SIG

(Since 2020)

see [The road to interoperability in CI/CD](https://fosdem.org/2021/schedule/event/the_road_to_interoperability_in_ci_cd/) @ FOSDEM 2021

> highlight and promote the needs of the users who face challenges constructing complex end-to-end CI/CD flows and pipelines by employing different tools and technologies

notes: one of the objectives of the interop SIG highlights the need for a focus group on events

-----

## Events in CI/CD subgroup

</br>
Open source technologies represented:
</br>

![](images/events_in_cicd_opensource.svg)<!-- .element height="30%" width="30%" -->


notes: While the group is hosted @ CDF, its scope is not limited to CDF hosted projects

-----

* Interoperability between CI/CD systems
* Common protocol
* Common terminology

notes: The events in CI/CD group was initially created to evaluate how events can be used in the context of interoperability

-----

![](images/xkcd_standards.png)<!-- .element height="40%" width="80%" -->

notes: We want to avoid creating a new standard. Cloud events + metadata

-----

### Events?

We currently stick with the [definition by CloudEvents](https://github.com/cloudevents/spec/blob/v1.0/spec.md#terminology):

> An *event* is a data record expressing an *occurrence* and its context, where *occurrence* is the capture of a statement of fact during the operation of a software system.

We plan on using [CloudEvents](https://cloudevents.io/) (CNCF) as the base protocol.

![](images/cloudevents.svg)<!-- .element height="20%" width="20%" -->

-----

### Problems we are working on

</br>

* Shared Vocabulary
* Structure: lightweight vs. "complete"
* Relations: links, order, uniqueness
* Patterns: descriptive vs. prescriptive events

<br/><br/>
<span class="fragment">
→ More than interoperability ←
</span>

---

## Events in CI/CD SIG

* Proposed in 2021
* Charter in progress (at the time of writing)

* Extend the scope beyond interoperability
* Give more visibility, attract contributions

-----

### Charter (provisional)

> Research how events can be used to advance CI/CD systems (...)

* Common format for integration
* Decoupled architecture, resilient and scalable

-----

### Areas of investigation

* Events as triggers, decoupled workflows
* Events for monitoring and auditing
* Orchestration and tracing for events based workflows
* Best practices

-----

### How to contribute

* Join the [#events-in-cicd channel](https://cdeliveryfdn.slack.com/archives/C0151BTKEJX) on CDF Slack
* Bi-weekly [meetings](https://github.com/cdfoundation/sig-interoperability/blob/master/workstreams/events_in_cicd/meetings.md)
* Group [README](https://hackmd.io/AnVkdMb3QEeVQXKfIj4tNQ)
* We welcome uses cases, ideas, collaboration, code and positive vibes

---

## Thank You

#### Come and join us!

-----

## References

* CD Foundation: https://cd.foundation/
* Interoperability SIG: https://github.com/cdfoundation/sig-interoperability
* Events in CI/CD work-stream: https://github.com/cdfoundation/sig-interoperability/tree/master/workstreams/events_in_cicd