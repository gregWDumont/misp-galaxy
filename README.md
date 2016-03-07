# misp-galaxy

MISP galaxy is a simple method to express a large object called cluster that can be attached to MISP events or
attributes. A cluster can be composed of one or more elements. Elements are expressed as key-values. There
are default elements available in MISP galaxy but those can be overwritten, replaced or updated as you wish.

Existing clusters and elements can be used as-is or as a template. MISP distribution can be applied
to each cluster to permit a limited or broader distribution scheme.

# Available clusters

- [cluster/threat-actor.json](cluster/threat-actor.json) - Threat Actor

# Available Elements

- [elements/adversary-groups.json](elements/adversary-groups.json) - Adversary groups - Known or estimated adversary groups targeting organizations and employees. Adversary groups are regularly confused with their initial operation or campaign.
- [elements/certainty-level.json](elements/certainty-level.json) - Certainty level of an associated element or cluster.
- [elements/planning-and-operational-support-vocabulary.json](elements/planning-and-operational-support-vocabulary.json) - The PlanningAndOperationalSupportVocab is the default STIX vocabulary for expressing the planning and operational support functions available to a threat actor.
- [elements/threat-actor-motivation-vocabulary.json](elements/threat-actor-motivation-vocabulary.json) - The MotivationVocab is the default STIX vocabulary for expressing the motivation of a threat actor. STIX 1.2.1
- [elements/threat-actor-sophistication-vocabulary.json](elements/threat-actor-sophistication-vocabulary.json) - The ThreatActorSophisticationVocab enumeration is used to define the default STIX vocabulary for expressing the subjective level of sophistication of a threat actor.
- [elements/threat-actor-type-vocabulary.json](elements/threat-actor-type-vocabulary.json) - The ThreatActorTypeVocab enumeration is used to define the default STIX vocabulary for expressing the subjective type of a threat actor.
- [elements/threat-actor-intended-effect-vocabulary.json](elements/threat-actor-intended-effect-vocabulary.json) - The IntendedEffectVocab is the default STIX vocabulary for expressing the intended effect of a threat actor. STIX 1.2.1

## How to contribute?

Fork the project, update or create elements or clusters and make a pull-request.
