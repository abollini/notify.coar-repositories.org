---
title: Announce Relationship
description: 'This pattern is used to announce a relationship between two resources'
date: "2021-03-08"
type: patterns
event_notifications_pattern: []
pattern_category: announcements
payload:
  id: "urn:uuid:94ecae35-dcfd-4182-8550-22c7164fe23f"
  type: ["Announce","coar-notify:RelationshipAction"]
  actor:
    lookup: "research-organisation"
  origin:
    lookup: "repository"
  target:
    lookup: "repository_2"
  object:
    lookup: "relationship with target-hosted resource"
  context:
    lookup: "remote-resource"
---

