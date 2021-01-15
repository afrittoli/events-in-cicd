## Events in CI/CD
</br>
</br>

### Andrea Frittoli
#### Tekton, IBM

FOSDEM — CI/CD Devroom — 07.02.2021

---

# The Single Tool

<!-- (diagram with Git*, Tekton, Jenkins, Keptn, ArgoCD) -->

notes: Organizations often find one single tool that satisfies all their needs of CI/CD... or not really

-----

# The single Protocol

<!-- (same diagram plus various protocols) -->

notes: And these different platforms all speak the same language... or not really again

---

## Event driven

* Decoupled integration
* Scalability
* Resiliency

notes: Discuss the benefits of event driven integration between the various platforms.

-----

...but requires point to point integrations

notes: Platform X reacts to events from platform Y
Platform X understand terminology from platform Y

-----

We may get lost in translation

* Workflow or Pipeline?
* Build, task or step?

-----

* Collaboration
* Standardization

notes: collaboration may help, standardization were possible

---

### Continuous Delivery Foundation

notes: Enter CDF, a neutral home of CI/CD projects. A good place for collaboration.

-----

<!-- .slide: data-background="images/cdf.svg" -->

-----

## Interoperability SIG

see [The road to interoperability in CI/CD](https://fosdem.org/2021/schedule/event/the_road_to_interoperability_in_ci_cd/) @ FOSDEM 2021

> highlight and promote the needs of the users who face challenges constructing complex end-to-end CI/CD flows and pipelines by employing different tools and technologies

notes: one of the objectives of the interop SIG highlights the need for a focus group on events

-----

## Events in CI/CD subgroup

<!-- logos of technologies involved -->

notes: While the group is hosted @ CDF, its scope is not limited to CDF hosted projects

-----

* Interoperability between CI/CD systems
* Common protocol
* Common terminology

notes: The events in CI/CD group was initially created to evaluate how events can be used in the context of interoperability

-----

<!-- .slide: data-background="images/xkcd_standards.png" -->

<!-- Add attribution -->

notes: We want to avoid creating a new standard. Cloud events + metadata

-----

* More than interop

---

# Events in CI/CD SIG

---

* Charter / mission (2/3 slides)

---

* Artifacts produced until now

---

* Community how to contribute

---

* Come and join us